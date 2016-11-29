# Azure App Services demo for HoloLens
Self-contained Azure App Services UI demo for HoloLens contains:
- [Microsoft/HoloToolkit](https://github.com/Microsoft/HoloToolkit-Unity) (master ca49669)
- [Unity3dAzure/AppServices](https://github.com/Unity3dAzure/AppServices) (UnityWebRequest branch)
- [TSTableView](https://bitbucket.org/tacticsoft/tstableview)

# Prerequisites
- Install [Unity Technical Preview with HoloLens](https://unity3d.com/partners/microsoft/hololens)

# Setup
- Follow [Azure App Services Demo setup instructions](https://github.com/Unity3dAzure/AppServicesDemo) and create 'Highscores' and 'Inventory' table.
- Open project in Unity Technical Preview and paste App Service URL into scene's game object. NB: To run the inventory demo requires authentication which is detailed in the [App Services for Unity blog post](http://www.deadlyfingers.net/azure/azure-app-services-for-unity3d/).
- Build for Windows Store app:
  * SDK: Windows 10
  * UWP build type: XAML (to support keyboard text input)

# Credits
Inventory demo uses [pixel art icons designed by Henrique Lazarini](http://7soul1.deviantart.com/art/420-Pixel-Art-Icons-for-RPG-129892453)
