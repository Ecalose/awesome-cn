<div class="github-widget" data-repo="marcobiedermann/search-engine-optimization"></div>

## Search Engine Optimization (SEO) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

搜索引擎优化（SEO）技巧和技术的有用清单/集合.



## URL

-描述性网址：使用描述性页面网址，该网址应反映您的目标关键字.
- [File extension](https://www.youtube.com/watch?v=dSG6C33GwsE) -不要去除网址上的文件扩展名.
- [HTTPS](https://webmasters.googleblog.com/2014/08/https-as-ranking-signal.html) -安全是Google的头等大事.
- [Hyphens](https://www.youtube.com/watch?v=AQcSFsQyct8) -使用连字符分割单词.
- [Localisation](https://support.google.com/webmasters/answer/62399) -选择特定国家/地区的域名，以获得更好的本地搜索结果.
- [Subdomain or subfolder](https://www.youtube.com/watch?v=_MswMYk05tk) -子域被视为单独的域.
- [URL builder](https://support.google.com/analytics/answer/1033867) - Use this tool to add custom campaign parameters to your URLs.

## Accessibility

-403：提供“ 403-访问被拒绝”页面.
-404：提供“ 404-未找到页面”页面.
- [Custom Search](https://developers.google.com/structured-data/slsb-overview) -使用Google附加链接搜索框，人们可以更快地访问您的内容.
-找不到文件：避免出现“ 404 FILE_NOT_FOUND”错误.
 -布局：使用`divs`代替`tables&#39;进行布局. 使用`tables&#39;在语义上是不正确的.
-移动网站：通过.htaccess将所有链接重定向到新位置.
- [Pagination](https://support.google.com/webmasters/answer/1663744) -实现链接的rel =“ next”`和`rel =“ prev”`属性.
- [Performance](https://developers.google.com/webmasters/mobile-sites/mobile-seo/common-mistakes/slow-mobile-pages) -性能和加载时间很重要.
 -重定向：尽可能避免重定向. 使用301重定向而不是302.
- [RichSnippets](https://schema.org/) -使用丰富的代码片段标记您的代码，它们会显示在搜索结果页面上.
- [Robots](https://en.wikipedia.org/wiki/Robots_exclusion_standard) -阻止不应通过“ robots.txt”文件或
  `<meta name="robots" content="">`.
-验证：写入有效代码（[HTML Validator](https://validator.w3.org/) [CSS Validator](https://jigsaw.w3.org/css-validator/)).
- [WAI-Aria](https://www.w3.org/TR/wai-aria/) -使用WAI-Aria标签来帮助机器理解您的代码.

## Meta Information

- [Description](https://www.youtube.com/watch?v=W4gr88oHb-k) -每页应有唯一的描述（最多160个字符）
  `<meta name="description" content="">`.
 -标题：每个页面应有一个唯一的演讲标题（60-100个字符）<title>网站标题</title> `.

## Keywords

-内容：关键字应以文章长度的〜3％出现.
-标题：关键字应出现在标题中.
- [Meta Tag](https://www.youtube.com/watch?v=jK7IPbnmvVU)  -您可以省略`<meta name="keywords" content="">  `，
  搜索引擎不使用此元标记.
-研究：高流量和较少竞争的关键字排名.
-单个：每个页面都应该有一个唯一的目标关键字.
-标题：关键字应出现在页面标题中.
- [URL](https://www.youtube.com/watch?v=rAWFv43qubI) -关键字应出现在URL名称中.


-内容：在SEO中，内容最重要.
 -Flash：避免使用Flash内容和Flash页面. 它们无法在手机上访问，并且排名较低.
 -新鲜度：新内容很重要. 建议更新页面或定期发布.
 -标题：最大结构为H1-H6的结构.  70个字符长.
-长度：文章至少应为300个字.
-强-使用“强”标签突出显示您的目标关键字.
- [Uniqueness](https://www.youtube.com/watch?v=mQZY7EmjbMA) -不要提供重复的内容，请使用唯一的内容类型.

## Images

- [Alt tag](https://support.google.com/webmasters/answer/114016) -添加一个alt标签，以描述图像（60-70个字符）.
-尺寸：在图片中添加`width =“”`和`height =“”`属性.
- [File name](https://www.youtube.com/watch?v=h2SWuUobbr0) -使用简短的描述性名称.
- [Optimization](https://imageoptim.com/) -通过删除一些元信息来优化图像.
- [Responsive Images](https://www.w3.org/TR/html-picture-element/) -提供与窗口大小相对应的最佳图像.
-大小：将文件大小保持尽可能低.

## Videos

-控件：添加控件以播放和控制视频.
-嵌入：允许其他人嵌入您的视频.
-转录：将转录用于索引，可用性和内容.
- [Unplayable content](https://developers.google.com/webmasters/mobile-sites/mobile-seo/common-mistakes/unplayable-content)  -避免播放无法播放的视频内容. 使用HTML5`<video> 标签而不是Flash.

## Links

-反向链接：仅当您获得指向站点的反向链接时，才添加外部链接.
-内部链接：在您的内容中添加〜3个内部链接.
- [Languages](https://moz.com/learn/seo/hreflang-tag) -hreflang标签告诉Google您在特定页面上使用的是哪种语言，因此搜索引擎可以将该结果提供给使用该语言进行搜索的用户
  `<link rel="alternate" href="example.com/fr/" hreflang="fr-fr" />`.
 -命名：使用描述性链接名称：“单击此处”或“阅读更多”是错误的链接文本. 更好的“阅读有关SEO和Web可访问性的更多信息”.
- [nofollow](https://support.google.com/webmasters/answer/96569) -仅向外部链接添加rel =“ nofollow”属性以防止垃圾邮件和错误链接.
-标题：将标题属性添加到链接.

## Mobile

- [AppLinks](http://applinks.org/documentation/) -链接到您内容的应用程序可以使用此元数据深层链接到您的应用程序.
- [mobile friendly](https://googlewebmastercentral.blogspot.be/2014/11/helping-users-find-mobile-friendly-pages.html)  -在搜索结果中标记了针对移动设备进行了优化的网站. 测试 [mobile friendly site](https://www.google.com/webmasters/tools/mobile-friendly/).
- [Smart App Banner](https://developer.apple.com/library/ios/documentation/AppleApplications/Reference/SafariWebContent/PromotingAppswithAppBanners/PromotingAppswithAppBanners.html) -Safari具有智能应用程序横幅功能，该功能提供了从网站在App Store上推广应用程序的标准化方法.
- [Tap targets](https://developers.google.com/speed/docs/insights/SizeTapTargetsAppropriately) -可点击的链接不应太小.
-视口：告诉浏览器如何调整页面尺寸和缩放比例以适合设备
  `<meta name="viewport" content="width=device-width, initial-scale=1">`

## Sitemap

- [HTML sitemap](https://www.youtube.com/watch?v=hi5DGOu1uA0) -HTML网站地图使网站访问者可以轻松浏览网站.
- [Image sitemap](https://support.google.com/webmasters/answer/178636) -增加您的图像可以在图像搜索结果中找到.
- [Mobile sitemap](https://support.google.com/webmasters/answer/6082207) -对于功能手机，您可以创建移动站点地图.
- [Video sitemap](https://support.google.com/webmasters/answer/80471) -确保搜索引擎了解您网站上的所有视频内容.
- [XML sitemap](https://support.google.com/webmasters/answer/183668) -帮助搜索引擎索引您的页面.

## Social Media

-作者信息.
- [Facebook](https://developers.facebook.com/docs/sharing/best-practices) -分享网站和移动应用的最佳做法.
- [OpenGraph](http://ogp.me/) -开放图谱协议可使任何网页成为社交图谱中的丰富对象.
- [Social Profiles](https://developers.google.com/webmasters/structured-data/customize/social-profiles) -将社交资料添加到您的Google搜索结果中.
-社交共享：为您的网站提供共享选项.
- [Twitter](https://dev.twitter.com/cards/getting-started) -使用Twitter卡，您可以将照片，视频和媒体体验附加到推文上.

## Tools & Services

### Webmasters

- [Bing Webmasters](http://www.bing.com/toolbox/webmaster) -允许网站管理员将其网站添加到Bing索引搜寻器.
- [Google Search Console (GWT)](https://www.google.com/webmasters/) -允许网站管理员检查索引编制状态并优化其网站的可见性.
- [Google Tag Manager](https://www.google.com/analytics/tag-manager/)  -了解有关Google Analytics（分析）跟踪代码管理器以及它如何帮助您简化生活和满足IT需求的信息. 几次点击即可启动新标签.

### Analytics

- [Ahrefs](https://ahrefs.com/)  -分析网站，跟踪社交媒体，建立反向链接-Ahrefs涵盖了您. 立即尝试我们的营销和SEO工具站点浏览器和内容浏览器！
- [BuzzSumo](https://app.buzzsumo.com/research/most-shared) -查找任何主题或域中共享最多的内容.
- [Followerwonk](https://moz.com/followerwonk) -Twitter分析，生物搜索等工具.
- [Google Analytics](https://www.google.com/analytics/) -生成有关网站流量的详细统计信息.
- [Open Site Explorer](https://moz.com/researchtools/ose/)  -使用“开放式站点资源管理器”来确定链接建立机会. 研究反向链接，识别首页，查看社交活动并分析锚文本.
- [Matomo](https://matomo.org/) -一个开放的分析平台.
- [SEMrush](https://www.semrush.com/) -SEMrush是一款功能强大且用途广泛的竞争情报套件，用于从SEO和PPC到社交媒体和视频广告研究的在线营销.
- [Seomator](https://seomator.com/) -SEO审核工具和网站搜寻器，通过“如何修复”提示提高SEO性能.
- [SEOstats](https://github.com/eyecatchup/SEOstats) -SEOstats是一个功能强大的开源PHP库，用于请求一堆与SEO相关的指标.
- [SimilarWeb](https://www.similarweb.com/)  -使用SameWeb.com的高级访问量估算器工具比较网站访问量. 查看任何网站的流量来源并了解其在线营销策略.
- [SpyFu](https://www.spyfu.com/)  -无限搜索任何竞争对手的SEO或Google Ads关键字. 研究关键字，找到任何域中最强的内容及其最主要的广告文案.
- [Twitter Analytics](https://analytics.twitter.com/) -衡量并增强您对Twitter的影响.
- [Plausible](https://plausible.io/) -Google Analytics（分析）的一种简单且对隐私友好的选择.

### Optimization

- [Web.dev](https://web.dev/)  -在Web.dev的有用指导和分析下，在您自己的站点和应用程序上获得Web的现代化功能. 无论您已经有一个网站还是刚刚起步，都可以在Web.dev上学习为现代Web进行构建.
- [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) -Page Speed Insights可衡量移动设备和台式机设备页面的性能.
- [Varvy Seo tool](https://varvy.com/) -显示：域强度，链接，图像seo，社交计数和提及，页面/技术seo，pagespeed等.
- [Webpagetest.org](https://www.webpagetest.org/)  -网页测试为您提供整体性能瀑布以及网站渲染时间表. 它还提供了关键的洞察力，可以深入了解到第一个字节的时间以及可能导致网页性能下降的原因.
- [WooRank](https://www.woorank.com/) -WooRank将帮助您解决网站上的问题并确定机会，使您在竞争中领先.
- [Awesometechstack.com](https://awesometechstack.com/) -AwesomeTechStack提供了有关任何网站技术堆栈的安全性，现代化性和性能的见解，并提供了有关改进网站生命周期和技术堆栈的指南.

### Keywords

- [Google Trends](https://www.google.com/trends/) -使用Google趋势探索Google趋势搜索主题.
- [Keyword Planner](https://adwords.google.com/KeywordPlanner) -计划您的搜索网络广告系列并了解客户的需求.
- [Keyword Tool](http://keywordtool.io/)  -Google关键字工具的最佳免费替代软件，可用于SEO和PPC关键字研究！ 只需几秒钟即可从Google建议中获取750多个相关的长尾关键字！
- [Moz Keyword Explorer](https://moz.com/explorer) -付费关键字工具，可提供精确的搜索量，关键字难度，SERP功能和自然的点击率数据.
- [Keyword Clarity](https://keywordclarity.io)  -免费的关键字分析工具，可让您使用树形图可视化和分组关键字指标. 该工具可用于Google Search Console API和CSV中的数据.
- [SEOwl](https://www.seowl.co) -跟踪您的关键字排名超时情况并监控反向链接 

### Links

- [OpenLinkProfiler](http://www.openlinkprofiler.org/) -对最新的实时反向链接进行深入分析.
- [Search Engine Spider Simulator](http://tools.seochat.com/tools/search-spider-simulator) -该工具通过完全按照搜索引擎机器人抓取页面时看到的网页内容的方式显示网页内容来模拟搜索引擎：查看最突出或无法访问的页面元素.
- [Screaming Frog SEO Spider Tool & Crawler Software](https://www.screamingfrog.co.uk/seo-spider/) -Screaming Frog SEO Spider是一个小型桌面程序（PC或Mac），可从SEO角度抓取网站链接，图像，CSS，脚本和应用程序.
- [Linkbuilding Spider](https://github.com/fulldecent/linkbuilding-spider) -一个PHP项目，用于检查网站是否链接到您的网站.

### Structured Data

- [Facebook Debugger](https://developers.facebook.com/tools/debug) -输入您要抓取的网址，以查看页面标记在Facebook上的显示方式.
- [Pinterest](https://developers.pinterest.com/rich_pins/validator/) -验证您的Rich Pins并申请将其添加到Pinterest上.
- [Structured Data Testing Tool](https://developers.google.com/structured-data/testing-tool/) -粘贴您的丰富网页摘要或网址进行测试.
- [Twitter card validator](https://cards-dev.twitter.com/validator) -输入带有meta标签的页面网址以进行验证.

### Bookmarklets

- [OuiSEO](https://github.com/carlsednaoui/seo-bookmarklet) -开源书签，可向您显示页面SEO和社交元数据信息.
- [SEO Bookmarklet](https://twkm.ca/projects/seo-bookmarklet) -一站式SEO书签，可快速查看现场SEO.

### Browser Extensions

- [MozBar](https://moz.com/tools/seo-toolbar)  -Moz的SEO工具栏可让您快速访问许多页面SEO要素，域和页面权限以及快速的nofollow切换. 立即下载免费工具栏！

### Jekyll Plugins

- [Jekyll SEO Tag](https://github.com/jekyll/jekyll-seo-tag) -Jekyll插件，可为搜索引擎和社交网络添加元数据标签，以更好地索引和显示您网站的内容.

### TYPO3 Extensions

- [Basic SEO Features](https://typo3.org/extensions/repository/view/seo_basics) -在新模块以及灵活的Google Sitemap中为每页的标题标签，简单易用的SEO友好关键字和说明编辑添加了单独的字段.
- [Google sitemap](https://typo3.org/extensions/repository/view/dd_googlesitemap) -高性能的Google网站地图实现，可避免其他类似扩展程序产生的典型错误.

### WordPress Plugins

- [All in One SEO Pack](https://wordpress.org/plugins/all-in-one-seo-pack/)  -WordPress下载次数最多的插件（近3000万次下载）. 使用“多于一个SEO包”可自动为搜索引擎优化您的网站.
- [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/) -改善您的WordPress SEO：使用Yoast SEO插件编写更好的内容，并拥有一个完全优化的WordPress网站.
- [Slim SEO](https://wordpress.org/plugins/slim-seo/) -使用轻量级WordPress SEO插件为您自动执行SEO任务.

## Books

- [Search engine optimization 2016: Learn SEO with smart internet marketing strategies](https://www.amazon.com/Search-Optimization-Internet-Marketing-Strategies/dp/151534567X) -通过SEO 2016了解SEO策略，使其在Google中名列前茅.
- [Search Engine Optimization All-in-One For Dummies](https://www.amazon.com/Search-Engine-Optimization-All-Dummies/dp/1118921755)  -布鲁斯·克莱（Bruce Clay）是SEO社区中最受尊敬的人物之一，在所有主要会议上讲课和讲习班. 像“ SEO的艺术”一样，尽管它是“傻瓜”系列的一部分，但实际上它是一门技术性很强的书，可能不是您最容易的第一本指南.
- [SEO 2016: Learn Search Engine Optimization](https://www.amazon.com/SEO-2016-Search-Engine-Optimization/dp/1512275069) -当今竞争性搜索环境中关于SEO的全面必备指南.
- [SEO Fitness Workbook](https://www.amazon.com/SEO-Fitness-Workbook-2016-Optimization/dp/1518748880) -关于SEO的循序渐进的书，从目标开始，遍历页面SEO（例如页面标签），最后到达页面SEO（例如链接建立和社交提及）.
- [SEO For Dummies, 6th Edition](http://shop.oreilly.com/product/9781119129554.do) -您完整更新的搜索引擎优化指南.
- [SEO Step-by-Step - The Complete Beginner's Guide to Getting Traffic from Google](https://www.amazon.com/SEO-Step-Step-Complete-Beginners/dp/1497415020)  -还以关键字开头，并涵盖“页面上”和“页面外SEO”. 强调速度的重要性，并且有一个不错的附录，其中包含SEO资源，词汇表和链接.
- [SEO Warrior](http://shop.oreilly.com/product/9780596157081.do) -增加Web可见性的基本技术.
- [SEO: Marketing Strategies to Dominate the First Page](https://www.amazon.com/SEO-Marketing-Strategies-analytics-optimization-ebook/dp/B01ACB7LQM) -介绍Google Analytics（分析），网站管理员，网站流量，Adwords，每次点击付费，网站推广和搜索引擎优化.
- [The Art of SEO, 3rd Edition](http://shop.oreilly.com/product/0636920032908.do) -掌握搜索引擎优化.
- [The Beginner's Guide to SEO](https://moz.com/beginners-guide-to-seo)  -SEO的新手？ 需要完善您的知识吗？  SEO初学者指南已阅读了300万次以上，并提供了在迈向专业质量SEO道路上所需的信息.
- [The SEO Battlefield](http://shop.oreilly.com/product/0636920050964.do) -如果您想建立一个持续进行的SEO计划，以增加流量和提高搜索知名度为目标，此实用的分步指南将帮助您了解SEO方法论，然后向您展示如何将这些理论付诸实践.

## Courses

- [Analyzing Your Website to Improve SEO](https://www.lynda.com/Marketing-Small-Business-Marketing-tutorials/Analyzing-Your-Website-Improve-SEO/82409-2.html)  -逐步浏览网站的内容和标记，以提高其在搜索引擎结果中的排名. 与Lynda.com的彼得·肯特（Peter Kent）合作.
- [ClickMinded](https://www.clickminded.com/) -ClickMinded是面向希望尽快增加其自然流量和销售量的初创公司的SEO培训课程.
- [Ecommerce SEO 101 Video Series](https://www.shopify.com/videos/ecommerce-seo-101) -shopify与Helen Overland的电子商务SEO 101视频系列.
- [Improving SEO Using Accessibility Techniques](https://www.lynda.com/HTML-5-tutorials/Improving-SEO-Using-Accessibility-Techniques/89051-6.html)  -通过适当的标记和Web标准合规性，使网站更易于访问并且对搜索引擎友好. 与Lynda.com的Morten Rand-Hendriksen合作.
- [International SEO Fundamentals](https://www.lynda.com/Analytics-tutorials/International-SEO-Fundamentals/377449-6.html)  -通过这些SEO技巧吸引国际访客到您的网站. 了解如何确定目标市场并针对全球国家和语言优化网站的技术方面和内容. 与Lynda.com的David Booth合作.
- [Learning Search Engine Optimization (SEO) - A Video Introduction](https://www.video2brain.com/en/courses/learning-search-engine-optimization-seo-a-video-introduction) -学习搜索引擎优化（SEO）-video2brain的Matt Bailey的视频介绍.
- [Learning Web Analytics](https://www.video2brain.com/en/courses/learning-web-analytics) -通过video2brain与Matt Bailey学习Web分析.
- [SEO for Beginners](http://seoforbeginners.com/) -面向初学者的SEO：视频指南简介.
- [SEO for Ecommerce](https://www.lynda.com/Google-Analytics-tutorials/SEO-Ecommerce/386884-2.html) - SEO for ecommerce is different. Get strategies tailored for optimizing an online store to improve page rankings and build traffic. With Steven Harris by Lynda.com.
- [SEO for Local Visibility](https://www.lynda.com/Google-Maps-tutorials/SEO-Local-Visibility/178132-2.html)  -使用这些本地SEO策略在搜索排名中获得最大的知名度. 与Lynda.com的Brad Batesole合作.
- [SEO for Web Designers](https://webdesign.tutsplus.com/courses/seo-for-web-designers) -TutsPlus的Craig Campbell为网页设计师提供的SEO.
- [SEO Fundamentals](https://www.lynda.com/Analytics-tutorials/SEO-Fundamentals/187858-2.html) -Lynda.com的David Booth提供的SEO基础知识.
- [SEO Fundamentals](https://www.pluralsight.com/courses/seo-fundamentals) -Pluralsight的Paul Wilson撰写的SEO基础知识.
- [SEO Tools Fundamentals](https://www.lynda.com/Buzzstream-tutorials/SEO-Tools-Fundamentals/368917-2.html)  -了解有关技术优化，内容优化，异地优化和竞争性研究的当今顶级SEO工具. 与Lynda.com的Brad Batesole合作.
- [SEO Training Course by Moz](https://www.udemy.com/whiteboard-seo/) -udemy与Moz进行的SEO培训课程.
- [SEO: Keyword Strategy in Depth](https://www.lynda.com/Business-Online-Marketing-tutorials/SEO-Keyword-Strategy-Depth/147030-6.html)  -了解如何研究关键字，将其应用到您的网站以及围绕关键字创建广告系列. 增加您的网站访问量，并通过关键字更好地了解用户的意图. 与Lynda.com的Matt Bailey合作.
- [SEO: Link Building in Depth](https://www.lynda.com/Business-Online-Marketing-tutorials/SEO-Link-Building-Depth/95253-6.html)  -研究链接的结构，链接如何影响页面排名以及构成出色的入站链接的属性. 与Lynda.com的彼得·肯特（Peter Kent）合作.
- [Spying with SEO Tools](https://www.lynda.com/Marketing-PPC-tutorials/Spying-SEO-Tools/371730-6.html)  -了解如何使用SEO工具和技术在线研究比赛. 找出竞争对手正在优化的关键字，然后在搜索引擎结果页上将其排名居后. 与Lynda.com的Anson Alexander合作.
- [WordPress Plugins: SEO](https://www.lynda.com/WordPress-tutorials/WordPress-Plugins-SEO/140779-2.html)  -在两个强大的插件的帮助下，通过执行搜索引擎优化或SEO，将更多访问者吸引到您的WordPress网站. 与Lynda.com的Morten Rand-Hendriksen合作.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
