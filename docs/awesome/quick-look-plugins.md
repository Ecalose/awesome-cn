<div class="github-widget" data-repo="sindresorhus/quick-look-plugins"></div>

## Quick Look plugins [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt;有用的清单 [Quick Look](https://en.wikipedia.org/wiki/Quick_Look) 开发人员插件

## Install

### Using [Homebrew](https://brew.sh)

 -运行`brew install<package>  `

#### Install all

```
酿造安装qlcolorcode qlstephen qlmarkdown quicklook-json qlimagesize可疑程序包外观quicklookase qlvideo
```

##### Catalina notes

要使插件在Catalina中正常工作，您需要删除隔离属性.

运行此命令以查看属性：

```
xattr -r〜/库/ QuickLook
```

并运行以下命令删除属性：

```
xattr -d -r com.apple.quarantine〜/ Library / QuickLook
```

### Manually

-点击“手动下载”
-将下载的.qlgenerator文件移动到`〜/ Library / QuickLook`
-运行`qlmanage -r`

## Plugins

### [QLColorCode](https://github.com/anthonygelibert/QLColorCode)

&gt;使用语法突出显示预览源代码文件

运行`brew install qlcolorcode`或 [download manually](https://github.com/anthonygelibert/QLColorCode/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QLColorCode.png)](https://github.com/anthonygelibert/QLColorCode)

### [QLStephen](https://github.com/whomwah/qlstephen)

 &gt;预览没有或带有未知文件扩展名的纯文本文件. 示例：README，CHANGELOG，index.styl等.

运行`brew install qlstephen`或 [download manually](https://github.com/whomwah/qlstephen/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QLStephen.png)](https://github.com/whomwah/qlstephen)

### [QLMarkdown](https://github.com/toland/qlmarkdown)

&gt;预览Markdown文件

运行`brew install qlmarkdown`或 [download manually](https://github.com/downloads/toland/qlmarkdown/QLMarkdown-1.3.zip)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QLMarkdown.png)](https://github.com/toland/qlmarkdown)

### [QuickLookJSON](http://www.sagtau.com/quicklookjson.html)

&gt;预览JSON文件

运行`brew install quicklook-json`或 [download manually](http://www.sagtau.com/media/QuickLookJSON.qlgenerator.zip)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QuickLookJSON.png)](http://www.sagtau.com/quicklookjson.html)

### [BetterZipQL](https://macitbetter.com/downloads/)

&gt;预览档案

&gt;注意：BetterZipQL插件已与BetterZip应用程序集成.

运行`brew install betterzip`以安装BetterZip应用及其快速外观插件，或者 [download manually](https://macitbetter.com/BetterZip.zip)

旧版的BetterZipQL插件可以是 [downloaded here](https://macitbetter.com/dl/BetterZipQL-1.5.zip).

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/BetterZipQL.png)](https://macitbetter.com/BetterZip-Quick-Look-Generator/)

### [qlImageSize](https://github.com/Nyx0uf/qlImageSize)

&gt;显示图像尺寸和分辨率

运行`brew install qlimagesize`或 [download manually](https://github.com/Nyx0uf/qlImageSize#installation)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/qlImageSize.png)](https://github.com/Nyx0uf/qlImageSize)

### [Suspicious Package](https://www.mothersruin.com/software/SuspiciousPackage/)

&gt;预览标准Apple安装程序包的内容

运行`brew install suspicious-package`或 [download manually](https://www.mothersruin.com/software/downloads/SuspiciousPackage.xip)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/SuspiciousPackage.png)](https://www.mothersruin.com/software/SuspiciousPackage/)

### [Apparency](https://www.mothersruin.com/software/Apparency/)

&gt;预览macOS应用程序的内容

运行`brew install apparency`或 [download manually](https://mothersruin.com/software/downloads/Apparency.dmg)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/Apparency.png)](https://mothersruin.com/software/Apparency/)

### [QuickLookASE](https://github.com/rsodre/QuickLookASE)

&gt;预览使用Adobe Photoshop，Adobe Illustrator， [Adobe Color CC](https://color.adobe.com), [Spectrum](http://www.eigenlogik.com/spectrum/mac), [COLOURlovers](https://www.colourlovers.com), [Prisma](http://www.codeadventure.com)等等.

运行`brew install quicklookase`或 [download manually](https://github.com/rsodre/QuickLookASE/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QuickLookASE.png)](https://github.com/rsodre/QuickLookASE)

### [QLVideo](https://github.com/Marginal/QLVideo)

&gt;预览大多数类型的视频文件及其缩略图，封面和元数据

运行`brew install qlvideo`或 [download manually](https://github.com/Marginal/QLVideo/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QLVideo.png)](https://github.com/Marginal/QLVideo)

## More

*这些不包括在 [Install all](#install-all).*

### [ProvisionQL](https://github.com/ealeksandrov/ProvisionQL)

&gt;预览iOS / macOS应用和配置信息

运行`brew install Provisionql`或 [download manually](https://github.com/ealeksandrov/ProvisionQL/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/ProvisionQL.png)](https://github.com/ealeksandrov/ProvisionQL)

### [QuickLookAPK](https://github.com/hezi/QuickLookAPK)

&gt;预览Android APK文件

运行`brew install quicklookapk`或 [download manually](https://github.com/hezi/QuickLookAPK/blob/master/QuickLookAPK.qlgenerator.zip)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QuickLookAPK.png)](https://github.com/hezi/QuickLookAPK)

### [quicklook-pat](https://github.com/pixelrowdies/quicklook-pat)

&gt;预览Adobe Photoshop图案文件

运行`brew install quicklook-pat`或 [download manually](https://github.com/pixelrowdies/quicklook-pat/releases)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/quicklook-pat.png)](https://github.com/pixelrowdies/quicklook-pat)

### [WebP](https://github.com/dchest/webp-quicklook)

&gt;预览WebP图像

&gt;注意：`qlImageSize`已经覆盖了它，因此仅在您不喜欢`qlImageSize`的情况下在此列出此插件.

运行`brew install webpquicklook`或 [download manually](https://github.com/dchest/webp-quicklook/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/WebP.png)](https://github.com/dchest/webp-quicklook)

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Sindre Sorhus](https://sindresorhus.com) 放弃了此作品的所有版权以及相关或邻近的权利.
