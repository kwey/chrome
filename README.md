

一些例子

## 点击改变Browser Action的图标。
```
使用 background_page, browser_action and tabs

调用:
chrome.browserAction.onClicked
chrome.browserAction.setIcon
源文件:
background.html
manifest.json

```
## 改变弹出式Browser Action的页面颜色.
```
使用 browser_action, popup and tabs

调用:
chrome.tabs.executeScript
源文件:
manifest.json
popup.html

```
## 将一个没有图标的Browser Action页面变成红色
```
使用 background_page, browser_action and tabs

调用:
chrome.browserAction.onClicked
chrome.browserAction.setBadgeBackgroundColor
chrome.browserAction.setBadgeText
chrome.tabs.executeScript
源文件:
background.html
manifest.json

```
## AcceptLanguage
```
使用 browser_action and popup

返回可用的语言。

调用:
chrome.i18n.getAcceptLanguages
chrome.i18n.getMessage
源文件:
_locales/en_US/messages.json
_locales/es/messages.json
_locales/sr/messages.json
manifest.json
popup.html

```
## 动画页面Action
```
使用 background_page, page_action and tabs

这个扩展在工具栏上添加一个动画Browser Action

调用:
chrome.pageAction.hide
chrome.pageAction.onClicked
chrome.pageAction.setIcon
chrome.pageAction.setTitle
chrome.pageAction.show
chrome.tabs.get
chrome.tabs.getSelected
chrome.tabs.onSelectionChanged
源文件:
background.html
manifest.json

```
## App Launcher
```
使用 browser_action and management

调用:
chrome.extension.getURL
chrome.management.get
chrome.management.getAll
chrome.management.launchApp
chrome.tabs.create
源文件:
manifest.json
popup.css
popup.html
popup.js

```
## 空白的新标签页
```
使用 chrome_url_overrides

源文件:
blank.html
manifest.json

```
## Chrome 声音
```
使用 background_page, bookmarks, options_page and tabs

浏览网页时使用声音会让您享受更神奇逼真的体验。

调用:
chrome.bookmarks.onCreated
chrome.bookmarks.onMoved
chrome.bookmarks.onRemoved
chrome.extension.getBackgroundPage
chrome.extension.onRequest
chrome.extension.sendRequest
chrome.tabs.get
chrome.tabs.onAttached
chrome.tabs.onCreated
chrome.tabs.onDetached
chrome.tabs.onMoved
chrome.tabs.onRemoved
chrome.tabs.onSelectionChanged
chrome.tabs.onUpdated
chrome.windows.onCreated
chrome.windows.onFocusChanged
chrome.windows.onRemoved
源文件:
bg.html
bg.js
content.js
manifest.json
options.html

```
## Chromium Buildbot Monitor
```
使用 background_page, browser_action, notifications, options_page and popup

在工具栏上显示Chromeium编译机器人的状态，在状态气泡上点击了解更多信息。

调用:
chrome.browserAction.setBadgeBackgroundColor
chrome.browserAction.setBadgeText
chrome.browserAction.setTitle
chrome.extension.getURL
源文件:
bg.html
manifest.json
options.html
popup.html

```
## Chromium 搜索
```
使用background_page and tabs

添加搜索Chromium源代码功能到地址栏。

调用:
chrome.omnibox.onInputCancelled
chrome.omnibox.onInputChanged
chrome.omnibox.onInputEntered
chrome.omnibox.onInputStarted
chrome.omnibox.setDefaultSuggestion
chrome.tabs.get
chrome.tabs.getSelected
chrome.tabs.update
源文件:
background.html
manifest.json

```
## CLD
```
使用background_page, browser_action and tabs

显示一个Tab页的语言

调用:
chrome.browserAction.setBadgeText
chrome.tabs.detectLanguage
chrome.tabs.get
chrome.tabs.getSelected
chrome.tabs.onSelectionChanged
chrome.tabs.onUpdated
源文件:
background.html
manifest.json

```
## 上下文菜单示例
```
使用background_page and contextMenus

显示一些上下文菜单API的例子

调用:
chrome.contextMenus.create
源文件:
background.html
manifest.json
sample.js

```
## Cookie API 测试扩展
```
使用 background_page, browser_action, cookies and tabs

测试 Cookie API

调用:
chrome.browserAction.onClicked
chrome.cookies.get
chrome.cookies.getAll
chrome.cookies.onChanged
chrome.cookies.remove
chrome.extension.getURL
chrome.tabs.create
chrome.tabs.update
chrome.windows.get
chrome.windows.getAll
源文件:
background.html
manager.html
manifest.json

```
## 在脚本文件中怎么实现跨域XMLHttpRequest
```
使用background_page

演示了怎么从脚本中提取跨域XMLHttpRequest . 这种扩展可以提取Twitter中最热的话题，并覆盖到Google News服务的最新内容中访问 http://news.google.com 以测试此扩展。

调用:
chrome.extension.onRequest
chrome.extension.sendRequest
源文件:
background.html
contentscript.js
manifest.json

```
## Email 此页面 (by Google)
```
使用 background_page, browser_action, options_page and tabs

这个扩展会在工具栏上添加一个邮件按钮，它可以调用您的默认邮件或Gmaile来发送此页。

调用:
chrome.browserAction.onClicked
chrome.extension.connect
chrome.extension.onConnect
chrome.tabs.create
chrome.tabs.executeScript
chrome.tabs.update
源文件:
background.html
content_script.js
manifest.json
options.html

```
## 用Google Analytics进行事件跟踪
```
使用background_page, browser_action and popup

示例扩展， Google Analytics 的用法

源文件:
analytics.js
background.html
manifest.json
popup.html

```
## Extension Docs Search
```
使用background_page and tabs

搜索Chrome扩展文档。在地址栏输入 'crdoc' 加一个搜索项以使用。

调用:
chrome.omnibox.onInputChanged
chrome.omnibox.onInputEntered
chrome.tabs.create
chrome.tabs.get
chrome.tabs.onRemoved
chrome.tabs.update
源文件:
background.html
manifest.json

```
## Google Calendar 检查 (by Google)
```
使用 background_page, browser_action, options_page and tabs

Quickly see the time until your next meeting from any of your calendars. 按一下按钮，设置您的日期。

调用:
chrome.browserAction.onClicked
chrome.browserAction.setBadgeBackgroundColor
chrome.browserAction.setBadgeText
chrome.browserAction.setIcon
chrome.browserAction.setTitle
chrome.extension.getBackgroundPage
chrome.extension.onRequest
chrome.extension.sendRequest
chrome.i18n.getMessage
chrome.tabs.create
chrome.tabs.get
chrome.tabs.getAllInWindow
chrome.tabs.onUpdated
chrome.tabs.update
源文件:
_locales/en/messages.json
javascript/background.js
javascript/options.js
javascript/util.js
manifest.json
views/background.html
views/options.html

```
## Google Document List Viewer
```
使用 background_page, browser_action, options_page, popup and  tabs

演示怎么使用 OAuth 连接 Google Documents 列表数据 API.

调用:
chrome.browserAction.setBadgeText
chrome.extension.getBackgroundPage
chrome.extension.getURL
chrome.tabs.create
chrome.tabs.get
chrome.tabs.getSelected
chrome.tabs.onUpdated
chrome.tabs.remove
源文件:
background.html
chrome_ex_oauth.html
chrome_ex_oauth.js
chrome_ex_oauthsimple.js
js/jquery-1.4.1.min.js
manifest.json
options.html
popup.html

```
## Google Mail Checker
```
使用 background_page, browser_action, options_page and tabs

显示Gmaile中未读邮件的数据.，也可以点击按钮打开Gmail。

调用:
chrome.browserAction.onClicked
chrome.browserAction.setBadgeBackgroundColor
chrome.browserAction.setBadgeText
chrome.browserAction.setIcon
chrome.extension.getBackgroundPage
chrome.i18n.getMessage
chrome.tabs.create
chrome.tabs.get
chrome.tabs.getAllInWindow
chrome.tabs.onUpdated
chrome.tabs.update
源文件:
_locales/ar/messages.json
_locales/bg/messages.json
_locales/ca/messages.json
_locales/cs/messages.json
_locales/da/messages.json
_locales/de/messages.json
_locales/el/messages.json
_locales/en/messages.json
_locales/en_GB/messages.json
_locales/es/messages.json
_locales/es_419/messages.json
_locales/et/messages.json
_locales/fi/messages.json
_locales/fil/messages.json
_locales/fr/messages.json
_locales/he/messages.json
_locales/hi/messages.json
_locales/hr/messages.json
_locales/hu/messages.json
_locales/id/messages.json
_locales/it/messages.json
_locales/ja/messages.json
_locales/ko/messages.json
_locales/lt/messages.json
_locales/lv/messages.json
_locales/nb/messages.json
_locales/nl/messages.json
_locales/pl/messages.json
_locales/pt_BR/messages.json
_locales/pt_PT/messages.json
_locales/ro/messages.json
_locales/ru/messages.json
_locales/sk/messages.json
_locales/sl/messages.json
_locales/sr/messages.json
_locales/sv/messages.json
_locales/th/messages.json
_locales/tr/messages.json
_locales/uk/messages.json
_locales/vi/messages.json
_locales/zh_CN/messages.json
_locales/zh_TW/messages.json
background.html
manifest.json
options.html

```
## Google Wave 通知器
```
使用 background_page, browser_action, options_page, popup and  tabs

当有新的waves消息时通知，并且能快速预览

调用:
chrome.extension.getBackgroundPage
chrome.extension.getURL
chrome.tabs.create
chrome.tabs.get
chrome.tabs.getSelected
chrome.tabs.onUpdated
chrome.tabs.remove
源文件:
background.html
chrome_ex_oauth.html
chrome_ex_oauth.js
chrome_ex_oauthsimple.js
manifest.json
options.html
popup.html
prettyload.js

```
## Hello World
```
使用browser_action and popup

您可以偿试编写的第一个扩展。.

源文件:
manifest.json
popup.html

```
## Idle - Simple Example
```
使用background_page, browser_action and idle

演示 Idle API

调用:
chrome.browserAction.onClicked
chrome.extension.getBackgroundPage
chrome.idle.onStateChanged
chrome.idle.queryState
源文件:
background.html
history.html
manifest.json

```
## iGoogle 新标签页
```
使用chrome_url_overrides

源文件:
manifest.json
redirect.html

```
## Imageinfo
```
使用background_page, contextMenus and tabs

从Images中获取图片信息,包含 EXIF 数据

调用:
chrome.contextMenus.create
chrome.tabs.get
chrome.tabs.getCurrent
chrome.windows.create
chrome.windows.update
源文件:
background.html
imageinfo/binaryajax.js
imageinfo/exif.js
imageinfo/imageinfo.js
info.html
manifest.json

```
## Mappy
```
使用 background_page, page_action, popup and tabs

Finds addresses in the web page you're on and pops up a map window.

调用:
chrome.extension.getBackgroundPage
chrome.extension.onRequest
chrome.pageAction.hide
chrome.pageAction.setTitle
chrome.pageAction.show
chrome.tabs.get
chrome.tabs.getSelected
chrome.tabs.onSelectionChanged
chrome.tabs.onUpdated
chrome.tabs.sendRequest
源文件:
background.html
manifest.json
mappy_content_script.js
popup.html

```
## 合并窗口
```
使用background_page, browser_action and tabs

合并所有的浏览窗口到当前窗口

调用:
chrome.browserAction.onClicked
chrome.tabs.get
chrome.tabs.getAllInWindow
chrome.tabs.move
chrome.windows.get
chrome.windows.getAll
chrome.windows.getCurrent
源文件:
background.html
manifest.json

```
## Message Timer
```
使用browser_action, popup and tabs

记录发送一个消息到脚步并且返回所用的时间。

调用:
chrome.extension.onConnect
chrome.extension.onRequest
chrome.tabs.connect
chrome.tabs.get
chrome.tabs.getSelected
chrome.tabs.sendRequest
源文件:
manifest.json
page.js
popup.html

```
## 我的收藏夹
```
使用 bookmarks, browser_action, popup and tabs

一个用于搜索，添加，编辑和删所有搜索的broswer action。

调用:
chrome.bookmarks.create
chrome.bookmarks.get
chrome.bookmarks.getTree
chrome.bookmarks.remove
chrome.bookmarks.update
chrome.tabs.create
源文件:
manifest.json
popup.html

```
## 新闻阅读
```
使用browser_action, popup and tabs

在一个弹出窗口中显示最新的5条Google News RSS咨询。

调用:
chrome.tabs.create
源文件:
feed.html
manifest.json

```
## 新闻阅读
```
使用browser_action, popup and tabs

在一个弹出窗口中显示最新的5条Google News RSS咨询。

调用:
chrome.i18n.getMessage
chrome.tabs.create
源文件:
_locales/en/messages.json
_locales/es/messages.json
_locales/sr/messages.json
feed.html
manifest.json

```
## 新闻阅读 (by Google)
```
使用 background_page, browser_action, options_page, popup and  tabs

显示Google新闻中最新的Story。

调用:
chrome.extension.getURL
chrome.i18n.getMessage
chrome.tabs.create
源文件:
_locales/en/messages.json
css/feed.css
css/options.css
javascript/feed.js
javascript/options.js
javascript/util.js
manifest.json
views/background.html
views/feed.html
views/options.html

```
## Notification Demo
```
使用 background_page, notifications, options_page and tabs

显示桌面通知, 从桌面上弹出一个类似"toast"的窗口。

调用:
chrome.tabs.create
源文件:
background.html
error.html
manifest.json
options.html

```
## 地址栏示例
```
使用background_page

使用时在地址栏输入"omnix"加一个搜索项。

调用:
chrome.omnibox.onInputChanged
chrome.omnibox.onInputEntered
源文件:
background.html
manifest.json

```
## Page action by content
```
使用background_page and page_action

Shows a page action for HTML pages containing the word 'sandwich'

调用:
chrome.extension.onRequest
chrome.extension.sendRequest
chrome.pageAction.show
源文件:
background.html
contentscript.js
manifest.json

```
## Page action by URL
```
使用background_page, page_action and tabs

Shows a page action for urls which have the letter 'g' in them.

调用:
chrome.pageAction.show
chrome.tabs.onUpdated
源文件:
background.html
manifest.json

```
## 页面测试
```
使用 background_page, browser_action, options_page and tabs

Chromium 页面测试。

调用:
chrome.browserAction.onClicked
chrome.browserAction.setBadgeBackgroundColor
chrome.browserAction.setBadgeText
chrome.browserAction.setTitle
chrome.extension.connect
chrome.extension.getBackgroundPage
chrome.extension.getExtensionTabs
chrome.extension.getURL
chrome.extension.onConnect
chrome.tabs.create
chrome.tabs.executeScript
chrome.tabs.get
chrome.tabs.getAllInWindow
chrome.tabs.getSelected
chrome.tabs.remove
chrome.tabs.update
chrome.windows.get
chrome.windows.getCurrent
源文件:
background.html
jquery/jquery-1.4.2.min.js
jquery/jquery-ui-1.8.4.custom.min.js
jquery/jquery.client.js
jquery/jquery.flot.dashes.js
jquery/jquery.flot.js
jquery/jquery.flot.min.js
jquery/jquery.flot.navigate.js
jquery/jquery.flot.valuelabels.js
jst/jsevalcontext.js
jst/jstemplate.js
jst/jstemplate_test.js
jst/util.js
manifest.json
options.html
script.js
util/sorttable.js
util/table2CSV.js

```
## 打印此页
```
使用background_page, browser_action and tabs

在浏览器上添加一个打印按钮。

调用:
chrome.browserAction.onClicked
chrome.tabs.update
源文件:
background.html
manifest.json

```
## 进程监视器
```
使用 browser_action, experimental, popup and tabs

添加一个Browser Action用于监视所有浏览器进程的资源使用情况。

调用:
chrome.experimental.processes.onUpdated
源文件:
manifest.json
popup.html

```
## 示例 - OAuth 联系人
```
使用background_page, browser_action and tabs

使用 OAuth 连接 Google's 联系人服务，并且以列表显示联系人。

调用:
chrome.browserAction.onClicked
chrome.browserAction.setIcon
chrome.extension.getBackgroundPage
chrome.extension.getURL
chrome.tabs.create
chrome.tabs.get
chrome.tabs.getSelected
chrome.tabs.onUpdated
chrome.tabs.remove
源文件:
background.html
chrome_ex_oauth.html
chrome_ex_oauth.js
chrome_ex_oauthsimple.js
contacts.html
manifest.json

```
## SandwichBar
```
使用 background_page and experimental

在页面上显示信息条，并且显示文字： 'sandwich'

调用:
chrome.experimental.infobars.show
chrome.extension.onRequest
chrome.extension.sendRequest
源文件:
background.html
contentscript.js
infobar.html
manifest.json

```
## Show Tabs in Process
```
使用 browser_action, experimental, popup and tabs

添加一个browser action 显示当前进程共享的Tabs。

调用:
chrome.experimental.processes.getProcessIdForTab
chrome.tabs.get
chrome.tabs.getSelected
chrome.tabs.update
chrome.windows.get
chrome.windows.getAll
chrome.windows.getCurrent
chrome.windows.update
源文件:
manifest.json
popup.html

```
## Tab Inspector
```
使用 background_page, browser_action and tabs

一些实用的，Extension Tabs API。

调用:
chrome.browserAction.onClicked
chrome.extension.getURL
chrome.tabs.create
chrome.tabs.get
chrome.tabs.getAllInWindow
chrome.tabs.getSelected
chrome.tabs.move
chrome.tabs.onAttached
chrome.tabs.onCreated
chrome.tabs.onDetached
chrome.tabs.onMoved
chrome.tabs.onRemoved
chrome.tabs.onSelectionChanged
chrome.tabs.onUpdated
chrome.tabs.remove
chrome.tabs.update
chrome.windows.create
chrome.windows.get
chrome.windows.getAll
chrome.windows.getCurrent
chrome.windows.getLastFocused
chrome.windows.onCreated
chrome.windows.onFocusChanged
chrome.windows.onRemoved
chrome.windows.remove
chrome.windows.update
源文件:
background.html
jstemplate_compiled.js
manifest.json
tabs_api.html

```
## 测试截图扩展
```
使用 background_page, browser_action and tabs

演示chrome.tabs api的截图功能。

调用:
chrome.browserAction.onClicked
chrome.extension.getURL
chrome.extension.getViews
chrome.tabs.captureVisibleTab
chrome.tabs.create
chrome.tabs.onUpdated
源文件:
background.html
manifest.json
screenshot.html
screenshot.js

```
## Typed URL History
```
使用 browser_action, history and tabs

读取历史，并且显示你输入URL访问历史的最多前10项。

调用:
chrome.history.getVisits
chrome.history.search
chrome.tabs.create
源文件:
manifest.json
typedUrls.html
typedUrls.js
```