# Frequently Asked Questions (PC)

Read this section to see a list of Frequently Asked Questions on (PC)

## Quick Access

[Yuuki Launcher](#yuuki-launcher)

- [Cannot Run Launcher](#cannot-run-launcher)
- [Error Patch](#error-patch--patch-userassembly-failed)

[Game](#game)

- [Error 4214](#error-4214)
- [Failed to load il2cpp](#fatal-error--failed-to-load-il2cpp)

## Yuuki Launcher

- ### Cannot Run Launcher

> Make sure you have installed [.NET 6.0 Runtime (Desktop)](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime)

- ### Error Patch : Patch UserAssembly Failed

![error-patch][error-patch]

> This error happens because you are using a patched `UserAssembly`. Revert back to original `UserAssembly` so the launcher can patch it for you. (File is located in `GenshinImpact_Data\Native`)

## Game

- ### Error 4214

![error-4214][error-4214]

1. > This error happens when you are not using patched `UserAssembly` or `global-metadata`. Check [Discord](https://discord.gg/YuukiPS) to get the patch or use [Yuuki Launcher](https://github.com/akbaryahya/YuukiPS-Launcher) instead.

2. > If you already use the patch, then your Proxy Isn't running properly. Check your firewall settings make sure that it is allowed to access.

- ### Fatal Error : Failed to load il2cpp

![error-il2cpp][error-il2cpp]

> This error caused by bad `UserAssembly` file. You may have used the wrong version of the Anime Game's `UserAssembly` which will cause the game failed to launch and shows this error. Verify your game files on the launcher and try to launch the game. (If the problem still persist try re-install the full game)

## Credits

- [mailpakokok](https://github.com/mailpakokok) (TheScore)

> [Back to FAQ](/YuukiPS/docs/FAQ/README.MD)

[error-patch]: /YuukiPS/src/img/yuuki-launcher/error-patch.png
[error-4214]: /YuukiPS/src/img/game/4214.png
[error-il2cpp]: /YuukiPS/src/img/game/il2cpp.png
