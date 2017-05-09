# UnityNativeDebugLog
Log plugin that allows you to send Logs to the Unity Editor Console tab from C++ plugin

Usage:

Import the DebugCPP.h header file

#include "DebugCPP.h"

Then use 

```
Debug::Log("Hellow Red", Color::Red);
Debug::Log("Hellow Green", Color::Green);
Debug::Log("Hellow Blue", Color::Blue);
Debug::Log("Hellow Black", Color::Black);
Debug::Log("Hellow White", Color::White);
Debug::Log("Hellow Yellow", Color::Yellow);
Debug::Log("Hellow Orange", Color::Orange);

Debug::Log(true, Color::Black);
Debug::Log(false, Color::Red);

//No Color Specified but black will be used as the default color
Debug::Log("Hellow Default Black Color");
```

Attach DebugCPP.cs from UnityNativeDebugLog/Csharp/ to any empty GameObject that is active. Log should appear on Windows if testing the plugin in the Editor.
