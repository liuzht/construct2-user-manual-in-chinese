# 2.6 平台支持

Construct 2基于跨平台的HTML5技术，使你可以将你的项目发布到各个平台。下面列出了支持的平台以及每个平台的特性。

记住一条最好在最开始就在你预期的平台进行规律测试————尤其是手机平台，因为手机设备通常被认为比用来开发的桌面设备更脆弱。尽管使用HTML5在各处表现相同，但是事实上常有不同，尤其在表现、可用内存、文字表现、特性支持（例如WebGL或者高级视频特效）、平台特殊特性（例如Construct 2平台插件）、输入法、屏幕大小以及相似性很小的浏览器特性方面。

###桌面浏览器平台（HTML5）###

最新的手机浏览器对Construct 2游戏有很好的支持，但是有时在性能和桌面特性方面有点不足。Construct 2游戏在IOS6以上版Safari，Android Google Chrome，Firefox，Windows Phone 8设备，黑莓10以上以及Firefox OS上运行良好。

注意Android上面的默认浏览器（没有被Chrome替换之前的Android版本）在性能及特性方面表现较差，不适合运行Construct 2游戏。对于Android设备，强烈建议使用Chrome或者Firefox安卓版。最新的Android设备默认浏览器是Chrome，随着时间过去，安卓的旧版默认浏览器使用量会趋于微弱。

###本地桌面应用###

Construct 2支持使用node-webkit的技术来导出项目。这事实上是把Chrome桌面浏览器打包使其独立于你的项目。因此因此它的性能和特性都和成熟的高质量浏览器Chrome想匹配。COnstruct 2使用node-webkit导出到Windows，Mac OS X，32位或者64位的Linux等平台。

使用node-webkit进行预览或导出时，你还可以利用桌面应用的特性，例如读写磁盘文件。可用的[Node-Webkit插件](file:///G:/interesting/manual/manual.html#anchor-162)。

###其他桌面应用###

Construct 2游戏可以发布到[Chrome网上商店](https://www.scirra.com/tutorials/68/publishing-to-the-chrome-web-store)，在那里它们也可以从本地运行。

[Firefox 商店](https://www.scirra.com/tutorials/430/how-to-export-an-open-web-app-for-firefox-marketplace)提供了与Chrome网上商店相同的设施，只是使用Firefox。它也包括了Firefox OS手机平台。

Construct 2可以直接导出为Windows 8应用，从磁贴式的开始菜单里运行。Windows RT设备以及触屏平板电脑也支持。Windows 8的特性例如快照和应用内购买可以通过Construct 2的[Windows 8插件](file:///G:/interesting/manual/manual.html#anchor-145)获得。

###本地手机应用###

Construct 2可以通过PhoneGap Build来方便的把你的HTML5游戏包装到其他手机平台。然而由于它的独特工作方式，iOS以及Android应用做得还不够好。

想要使导出的iOS或Android应用有不错的表现，Construct 2还支持通过CocoonJS等服务包装你的应用。这些服务使用不同于PhoneGap的技术，被认为更快。PhoneGap Build，CocoonJS可以发布不同的版本。Construct 2有一个自带的CocoonJS插件可以用来实现广告、应用内购买等功能。CocoonJS属于Ludei公司，而Ludei是Scirra的分公司。查看[如何导出到CocoonJS](http://www.scirra.com/tutorials/303/how-to-export-to-cocoonjs)获取更多信息。

Construct 2也可以直接导出到许多其他手机应用商店，这些手机都有高质量的浏览器，游戏可以运行良好。这些包括黑莓10，Windows Phone 8，Firefox OS和Tizen。

###其他###

Construct 2也可以发布Facebook游戏，通过Construct 2的[Facebook插件](file:///G:/interesting/manual/manual.html#anchor-112)获得Facebook特性。

也可以发布到Scirra的游乐场，通过Construct 2的Scirra游乐场插件获得hi-scores等特性。


