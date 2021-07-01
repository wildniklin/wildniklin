# wildniklin

```csharp
// Put me in a component in unity! Make sure the name of the script is "Wildniklin", it must match the monobehaviour's class name. Then press run.

using UnityEngine;
using System;
using System.Collections.Generic;

public class Wildniklin : MonoBehaviour
{
    public enum indentType { space, tab };

    public static string favoriteIDE = "visual studio and vscode";
    public static string favoriteLanguage = "C#";
    public static string favoriteGameEngine = "Unity";
    public static indentType favoriteIndentType = indentType.space;
    public static int favoriteIndentSize = 4;

    public static int libsCreatedPublicly = 1; // Check my gist github profile!
    public static int libsCreatedPrivately = 4; // Planning to add more public ones

    public static string[] libsOnTheWay = new string[] { "float2, float3, int2, int3 alternatives to unity's \"bad\" Vector classes. (I just don't like unity's vectors. Unity didn't finish the vector classes.)" };
    public static string[] libsPublic = new string[] { "FastMath for faster calculations. Comes with precalculated sine functions with decent precision." };

    private void Start()
    {
        Debug.Log("About wildniklin:" + "\n" +
                  "Favorite IDE: " + favoriteIDE + "\n" +
                  "Favorite Language: " + favoriteLanguage + "\n" +
                  "Favorite GameEngine: " + favoriteGameEngine + "\n" +
                  "Favorite IndentType: " + favoriteIndentType.ToString() + "\n" +
                  "Favorite IndentSize: " + favoriteIndentSize.ToString() + "\n" +
                  "Libraries Created Publicly: " + libsCreatedPublicly.ToString() + "\n" +
                  "Libraries Created Privately: " + libsCreatedPrivately.ToString());

        for (int i = 0; i < libsOnTheWay.Length; i++) Debug.Log("Library on the way: " + libsOnTheWay[i]);
        for (int i = 0; i < libsPublic.Length; i++) Debug.Log("Library currently public: " + libsPublic[i]);
    }
}
```

# Currently working on:
- Currently working on:
- - Currently working on:
- - - Currently working on:

Error: StackOverflowError at line 12, stack count exceeded.

# Currently working on:
- GPU based voxel rendering with realitime reflections.
- Some sort of infinite voxel based game: (it's not minecraft)
![image](https://user-images.githubusercontent.com/20182052/112726030-8567e680-8f1b-11eb-8b70-b98275c2c8e8.png)
