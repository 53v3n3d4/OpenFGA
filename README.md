# OpenFGA

[OpenFGA](https://openfga.dev) syntax for Sublime Text.

![OpenFGA syntax for Sublime Text](assets/screenshot.png)

## Package installation

The recommended way to install is through [PackageControl.io](https://packagecontrol.io/packages/OpenFGA).  
- Menu `Tools > Command Palette > Package Control: Install Package`  
- Type `openfga`, search for `OpenFGA`  
- Click to install it  

To install manually, [download](https://github.com/53v3n3d4/OpenFGA/releases) the latest release version zip file and uncompress it on your Sublime Text `Packages` folder.  
- Download the zip file on [`releases`](https://github.com/53v3n3d4/OpenFGA/releases) page  
- Menu `Sublime Text > Preferences > Browse packages...` to open destination folder  
- Then unzip `OpenFGA zip file` inside `Packages` folder  

## Uninstall

To remove package using Package Control.  
- Menu `Tools > Command Palette > Package Control: Remove Package`  
- Click on `OpenFGA`  

To uninstall manually, go to your Sublime Text folder.  
- Menu `Sublime Text > Preferences > Browse packages...`  
- Then delete `OpenFGA` inside `Packages` folder  

## Customization

If you want it to look more like OpenFGA docs, an easy Mariana customization:
```
{
	"scope": "source.openfga keyword.declaration, source.openfga keyword.operator",
	"foreground": "color(var(white3) a(0.7))"
}
```

![OpenFGA syntax for Sublime Text](assets/screenshot-1.png)
