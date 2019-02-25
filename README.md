![demoGIF](https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/Font-Packer/logoDemo.gif)<br>

### 1.2 update:  
> fixed in Sierra(MacOS 10.12) some font can not be found  
> change the output font file name format  
> 解决了 Sierra(MacOS 10.12) 下一些字体找不到导致插件不工作的问题，建议重新下载安装

# Font-Packer
A Sketch plugin to collect font files you used in your Sketch file.  
Works in Sketch 3.9.1 and up (hasn't been tested in lower versions).

中文版介绍[点这里](http://sketch.cm/plugins/28)<br>


## How to install:

1. Download the [Plugin File](https://github.com/bigxixi/Font-Packer/archive/master.zip) and unzip it.  
2. Double click `Font-Packer.sketchplugin.` 

## How to use:  
1. Save your work in Sketch.  
2. Run `Plugins > Font Packer > Collect Font Files` or use shortcut `control`+`shift`+`T`.  
3. Choose a folder and follow the steps.  

![demoGIF](https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/Font-Packer/DEMO.gif)

## More Details:  
This plug-in will help you collect the font files you used in your Sketch file.

Font-Packer will create a folder with the same name as the Sketch file. Inside the folder, there will be both a copy of the `.sketch` file along with a `fonts` folder containing all the font files you used in your document. (Be mindful of any copyright and licensing issues if you want to share the fonts.)

And in case some files share the same name, a prefix like `Font1_、Font2_…` will be added.

> **NOTE:** If a font is split into different styles with different files (e.g `xxxfont-light.ttf`, `xxxfont-bold.ttf`, `xxxfont-italic.ttf`, ...)，but you only used some of them，the plugin would only copy what you used. Easy.

If there are missed fonts in the sketch file, the plugin will generate a list and only copy the available ones.

Special thanks to [utom](https://github.com/utom)  

## Donation - 求打赏:
如果您觉得本插件好用，欢迎打赏，感谢您的支持！  

[<img src="https://raw.githubusercontent.com/bigxixi/bigxixi.github.io/master/donate/index.hyperesources/wechat.png" width="30%" height="30%">](http://bigxixi.com/donate/index.html)
[<img src="https://raw.githubusercontent.com/bigxixi/bigxixi.github.io/master/donate/index.hyperesources/alipay%402x.jpg" width="30%" height="30%">](http://bigxixi.com/donate/index.html)  

也欢迎使用 PayPal：  

[<img src="https://raw.githubusercontent.com/bigxixi/bigxixi.github.io/master/donate/index.hyperesources/paypal.png" width="30%" height="30%">](https://www.paypal.me/bigxixi/)  
