# Unreal Shader Compiler Project
A ue4ss blueprint mod that allows users to compile shaders for materials and Niagara effects in (almost every ) packaged unreal game, and how a unreal developer could easily implement it.


Currently under construction , 1 game has mod files posted.




System Shock 2023 setup :

1. Download UE4SS and install it into the system shock folder

2. You must set the version in UE4SS-settings.ini , for system shock it is as follows :

[EngineVersionOverride]
MajorVersion = 4
MinorVersion = 27

3. Unzip the SystemShock.zip into the main folder of the game

the folder stucture should end up like so : 

System Shock Remake\SystemShock\Content\Paks\LogicMods\ShaderCompliation.pak

4. Due to the shock rifle shader crashing in DX12 mode, ( a problem with the game itself) i would avoid using it with this mod.  i can make a workaround or possibly fix the problematic shader later. For now do not use -dx12 as a launch option ( would of had to manually of set this in steam etc.) 


5. while in game ( not the pause menu for now ) you can press f8 , or left bumper + right bumper + dpad down on a gamepad , to engage the shader compilation.
the widget will take up the whole screen until complation is complete.

(there is also a button to engage the shader compiler in the ue4ss GUI console)


6. shader complation is complete. you can now play the game
