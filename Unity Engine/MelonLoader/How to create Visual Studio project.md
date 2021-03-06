# How to make a project in Visual Studio
Before getting started make sure you have the latest version of [.Net Framework](https://dotnet.microsoft.com/download/dotnet-framework). MelonLoader and NKHook6 require that you have .Net Framework 4.7.2 and above. Next you need to get MelonLoader. You can install it [manually](https://github.com/HerpDerpinstine/MelonLoader/releases/latest), or you can use our [Mod Manager](https://github.com/TDToolbox/BTD6-Mod-Manager) which does everything automatically. We recommend that you use our Mod Manager as it installs MelonLoader and NKHook6 automatically, while also keeping them up to date. You can download the latest version [here](https://github.com/TDToolbox/BTD6-Mod-Manager/releases/latest). If you decide to download MelonLoader manually you'll have to download NKHook6 manually as well. You can get the latest version of it [here](https://github.com/TDToolbox/NKHook6/releases/latest). The last thing you need to do is download [DnSpy](https://github.com/0xd4d/dnSpy/releases/latest) so you can view the game's code and build your mod off of it. 

After doing the steps above you'll need to download [Visual Studio](https://visualstudio.microsoft.com/). We'll be using this program to make our mods. After it's finished installing you are ready to make your first mod.

**TL;DR Get these files:**
1. Get [.Net Framework 4.7.2 or higher](https://dotnet.microsoft.com/download/dotnet-framework)
2. Get our [Mod Manager for BTD6 and BTDAT](https://github.com/TDToolbox/BTD6-Mod-Manager/releases/latest) which comes with all necessary files, **or** download [MelonLoader](https://github.com/HerpDerpinstine/MelonLoader/releases/latest) and [NKHook6](https://github.com/TDToolbox/NKHook6/releases/latest) manually
3. Get [DnSpy](https://github.com/0xd4d/dnSpy/releases/latest)
4. Download [Visual Studio Community](https://visualstudio.microsoft.com/) or better


## Making your first mod in C#
To make your first mod you'll need to start visual studio. Once it's opened click on "Create a new project"

![Create new proj image.png](https://cdn.discordapp.com/attachments/619054151967703061/759096827281932358/unknown.png)


Next you will see this window. At the top searc for "Class Library" and **make sure** to click on the one that says **Class Library (.NET Framework)** and has **C#** below the name. If you chose the wrong one your mod won't work, so make sure to click the correct one. Heres a picture of what it should look like: 

![picture](https://media.discordapp.net/attachments/619054151967703061/759103567562145812/git_test_1.png?width=942&height=651)


**Lastly**, give your project a name, select the location you want it to be at, and **make sure** that **Place solution and project in the same directory** is **CHECKED**. For the most important thing, **make sure you have.NET Framework 4.7.2 or higher selected!!!!!!** BTD6 Mods require that you use at least .NET Framework 4.7.2 and up. When you're ready, click Create and now you're done! 

![CreateProject menu.png](https://cdn.discordapp.com/attachments/619054151967703061/759107756543705148/unknown.png)

### Congrats! You've finished making your first project
You're now ready to start making mods!


## Having issues?
1. Make sure you have the latest [.Net Framework](https://dotnet.microsoft.com/download/dotnet-framework). You need at least .NET Framework 4.7.2 and up
2. Make sure you get [Visual Studio Community Edition](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&rel=16). If you're making your mod using C# and not one of the other scripting methods, you **CAN'T** use Visual Studio Code, and you **HAVE** to use Visual Studio Community and better.
3. If our Mod Manager is not working for you, download MelonLoader [manually](https://github.com/HerpDerpinstine/MelonLoader/releases/latest) and extract all of the files into your BTD6/BTDAT folder, so the files are in the same folder as the EXE for the game. **Please Note:** if you download MelonLoader manually you will also need to download the latest version of NKHook6, which you can get here: https://github.com/TDToolbox/NKHook6/releases/latest
4. Can't find your game's EXE? Check out this [guide](https://steamcommunity.com/sharedfiles/filedetails/?id=760447682) to learn how to access your game's files
5. **Still having issues?** Join our [Discord server](https://discord.gg/VADMF2M) to get more help!
