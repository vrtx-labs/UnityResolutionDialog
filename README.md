# UnityResolutionDialog

![Example Image](https://github.com/sitterheim/UnityResolutionDialog/blob/develop/example.png)

Replacement for Unity's built-in resolution dialog (aka Screen Selector) that was removed in Unity 2019.3. Works both up front (simply make it the first scene) and as a popup dialog (default key: ESC). Intended for development / testing purposes but can also be used in production.

# Installation 
Add this dependency to your ``manifest.json`` located at ``/Packages/manifest.json``:
```
{
    ...
    "dependencies": {
        ...
        "com.vrtxlabs.unityresolutiondialog": "https://github.com/vrtx-labs/UnityResolutionDialog#release/stable.git#release/stable"
    }
    ...
}
```

# VRTX Fork
This fork provides some small fixes.