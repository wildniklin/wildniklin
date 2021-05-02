# wildniklin

```csharp
// Put me in a component in unity! Hopefully it works. (Untested, lmk if it doesn't work)

using UnityEngine;

public static class Wildniklin : MonoBehaviour
{
    public enum indentType { space, tab };

    public const string favoriteIDE = "visual studio and vscode";
    public const string favoriteLanguage = "C#";
    public const string favoriteGameEngine = "Unity";
    public const indentType favoriteIndentType = indentType.space;
    public const int favoriteIndentSize = 4;

    public const int libsCreatedPublicly = 1;
    public const int libsCreatedPrivately = 4; // Planning to add more public ones
    
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
    }
}
```

# Currently working on:
- Currently working on:
- - Currently working on:
- - - Currently working on:

Error: StackOverflowError at line 12, stack count exceeded.

# Currently working on:
- Some sort of infinite voxel based game: (it's not minecraft)
![image](https://user-images.githubusercontent.com/20182052/112726030-8567e680-8f1b-11eb-8b70-b98275c2c8e8.png)
