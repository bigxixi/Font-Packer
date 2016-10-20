![demoGIF](https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/Font-Packer/logoDemo.gif)<br>
### There are some bugs on Sierra (MacOS 10.12) that if you use some fonts in the sketch file, the plugin will not work.  
### I am working on it, hope to fixed it in some days.  
### 请大家注意，Sierra (MacOS 10.12)下有如果使用了某些字体会出问题，我正在解决，请稍候。  
# Font-Packer
A Sketch plugin to collect font files you used in your sketch file.  
Work on Sketch 3.9.1 and up(not test in lower versions).<br>
中文版介绍及下载[点这里](http://bigxixi.com/fontpacker/)<br>


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
  
