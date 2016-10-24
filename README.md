![demoGIF](https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/Font-Packer/logoDemo.gif)<br>
### 1.2 update:  
>fixed in Sierra(MacOS 10.12) some font can not be found  
>change the output font file name format  
>解决了 Sierra(MacOS 10.12) 下一些字体找不到导致插件不工作的问题，建议重新下载安装

# Font-Packer
A Sketch plugin to collect font files you used in your sketch file.  
Work on Sketch 3.9.1 and up(not test in lower versions).<br>
中文版介绍[点这里](http://sketch.im/plugins/28/)<br>


##How to install:

1.Download the [Plugin File](https://github.com/bigxixi/Font-Packer/archive/master.zip) and unzip.  
2.Double click `Font-Packer.sketchplugin.` 

##How to use:  
1.Save your work on Sketch.  
2.Run `Plugins > Font Packer > Collect Font Files` or use shortcut `control`+`shift`+`T`.  
3.Choose a folder and follow the steps.  
<br>
![demoGIF](https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/Font-Packer/DEMO.gif)
<br>
##More Details:  
This plug-in can help you collect the font files you used in your sketch file.<br>It will create a folder with the name of the sketch file, inside the folder there are a copy of the `.sketch` and a `fonts` folder which collects the font files.(Note on the font copyright issues if you want to deliver them.)<br>Prefix like 'Font1_、Font2_…' would be added in case some files share a same name.<br>NOTE:If a font split different styles in different files(e..g xxxfont-light.ttf, xxxfont-bold.ttf, xxxfont-italic.ttf, ...)，but you just take some of them，the plug-in would only copy what you used.<br>
If there are missed fonts in the sketch file, the plugin will generate a list and only copy the available ones.
<br>
<br>
Special thanks to [utom](https://github.com/utom)
  
