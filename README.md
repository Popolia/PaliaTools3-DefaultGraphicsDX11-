# PaliaTools3
Fatal error: [File:Unknown] [Line: 868] Output->GetDisplayModeList(Format, 0, &NumModes, ModeList) failed at D:\shared\Palia\Palia-Release_0.167.0\Engine\Source\Runtime\D3D12RHI\Private\Windows\WindowsD3D12Device.cpp:1656 with error E_INVALIDARG

directx 11 will set you free
so you want to go to start menu again and type %appdata% and it will open a file browser
then in address bar - click on the "appdata" part of the address, and then open up the Local Folder
next, find and open Palia folder then Saved folder
and Config folder then WindowsClient folder till you see engine.ini (and open it with notepad) then scroll to bottom and add

[/Script/WindowsTargetPlatform.WindowsTargetSettings]
DefaultGraphicsRHI=DefaultGraphicsRHI_DX11

so the file with the modification is him ![Capture d’écran 2023-09-01 215750](https://github.com/Popolia/PaliaTools3/assets/69745473/a787ccce-d13f-4a4a-9c88-138a445c47ae)
the file I'm supplying has already gone through the procedure, you just need to replace it the file (this is to explain the basic process)
C:\Users\Admin\AppData\Local\Palia\Saved\Config\WindowsClient,
