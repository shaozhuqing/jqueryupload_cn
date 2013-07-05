# jQuery文件上传插件
# 演示
[演示文件上传](http://blueimp.github.io/jQuery-File-Upload/)

## 说明
文件上传多个文件选择，拖放支持，进度条，验证和预览图像，音频和视频的jQuery部件。

支持跨域，分块和可恢复的文件上传和客户端图像缩放。

工程与任何服务器端平台（PHP，Python和Ruby on Rails的，java，Node.js，Go等），支持标准的HTML表单文件上传。


# 特点
* **多文件上传：**
  允许选择多个文件同时上传。
* **拖放支持：**
  允许上传文件将它们从你的桌面或文件管理器拖放您的浏览器窗口。
* **上传进度条：**
  显示一个进度条，显示单个文件的上传进度，并为所有上传图片结合。
* **可取消上传：**
  可以取消单个文件上传，，停止上传进度。
* **可恢复上传：**
  中止上传可以恢复，支持BLOB API的浏览器。
* **分块上传：**
  较小的块，可以上传大文件支持BLOB API的浏览器。
* **客户端的图片大小：**
  图像可以自动调整客户端的浏览器支持所需的JS API。
* **预览图像，音频和视频：**
  上传前的预览图像，音频和视频文件，可以显示浏览器支持所需的API。
* **没有浏览器插件（例如Adobe的Flash）：**
  的实现是基于HTML5和JavaScript等开放标准和要求没有额外的浏览器插件。
* **优美的后备旧版浏览器：**
  如果上传文件，通过XMLHttpRequest的支持和传统的浏览器作为后备使用内置页框。
* **HTML文件上传表单回退：**
  允许逐步增强，通过使用一个标准的HTML文件上传表单部件元素。
* **跨站点的文件上传：**
  支持文件上传，跨站点的XMLHttpRequest或iframe重定向到不同的域。
* **多个插件实例：**
  允许使用多个插件实例，在同一网页。
* **可定制和可扩展性：**
  提供一个API来设置单独的选项，并为各种上传事件定义回调方法。
* **多重和文件的内容流上传：**
  可以上传文件，标准的“多重/表单数据”或文件的内容流（HTTP PUT文件上传）。
* **兼容任何服务器端应用平台：**
  工程与任何服务器端平台（PHP，Python和Ruby on Rails，java，Node.js的，Go等），支持标准的HTML表单文件上传。

## 要求
* [jQuery的]（http://jquery.com/） 1.6+
* [jQuery UI的小部件厂]（http://api.jqueryui.com/jQuery.widget/） 1.9+（包含）
* [jQuery的IFRAME交通插件]（https://github.com/blueimp/jQuery-File-Upload/blob/master/js/jquery.iframe-transport.js） （含）
* [JavaScript的模板引擎]（https://github.com/blueimp/JavaScript-Templates） 2.2.1+（选配）
* [JavaScript的加载图像功能]（https://github.com/blueimp/JavaScript-Load-Image） 1.7.3+（选配）
* [JavaScript的帆布斑点功能]（https://github.com/blueimp/JavaScript-Canvas-to-Blob） 2.0.6+（选配）
* [引导CSS工具包]（https://github.com/twitter/bootstrap/） 2.3+（选配）

jQuery UI的小部件是文件上传插件的基本要求，但没有任何其他的依赖非常轻巧。

jQuery的Iframe运输是必需的[浏览器没有XHR支持文件上传](https://github.com/blueimp/jQuery-File-Upload/wiki/Browser-support)。

在UI版本的文件上传插件也需要JavaScript的模板引擎以及JavaScript的加载图片和JavaScript帆布斑点的功能（图像预览和调整功能）。

在这些依赖被标记为可选的，没有他们作为基本的文件上传插件可用于UI版本的插件可以扩展到覆盖这些依赖关系替代方案。

在Twitter的[引导](https://github.com/twitter/bootstrap/)工具包是建立与用户界面。

这使得基于CSS的，反应灵敏的现代浏览器的布局和花哨的过渡效果。

该演示还包括[blueimp画廊](https://github.com/blueimp/Gallery)。

这两个组件是可选的，不是必需的。

该库还包括jQuery的[XDomainRequest运输插件](https://github.com/blueimp/jQuery-File-Upload/blob/master/js/cors/jquery.xdr-transport.js)，这使得跨域AJAX请求（GET和POST）Microsoft Internet Explorer> = 8。

然而，XDomainRequest对象不支持文件上传和插件只为跨域请求所使用的[演示](http://blueimp.github.io/jQuery-File-Upload/)，删除上传的文件演示文件上传服务。

[跨域文件上传](https://github.com/blueimp/jQuery-File-Upload/wiki/Cross-domain-uploads)使用[IFRAME运输插件](https://github.com/blueimp/jQuery-File-Upload/blob/master/js/jquery.iframe-transport.js)需要重新回到原始服务器检索上传结果。 

[例如执行](https://github.com/blueimp/jQuery-File-Upload/blob/master/js/main.js) 使得使用[result.html](https://github.com/blueimp/jQuery-File-Upload/blob/master/cors/result.html)起源服务器作为静态重定向页面。

## 浏览器

### 桌面浏览器
文件上传插件定期测试最新的浏览器版本，并支持以下的最低版本：

* Google Chrome
* Apple Safari 4.0+
* Mozilla Firefox 3.0+
* Opera 11.0+
* Microsoft Internet Explorer 6.0+

### 移动浏览器
文件上传插件已经过测试，与支持以下移动浏览器：

* Apple Safari on iOS 6.0+
* Google Chrome on iOS 6.0+
* Google Chrome on Android 4.0+
* Default Browser on Android 2.3+
* Opera Mobile 12.0+

### 支持的功能
每个浏览器版本支持的功能的详细介绍，
请看[扩展浏览器的支持信息]（https://github.com/blueimp/jQuery-File-Upload/wiki/Browser-support）。

## 许可证
[MIT许可]（http://www.opensource.org/licenses/MIT）下发布。

## 捐款
jQuery的文件上传是免费软件，但你可以捐款支持插件翻译者：

Alipay: [![Alipay](https://www.paypalobjects.com/WEBSCR-640-20110429-1/en_US/i/btn/btn_donateCC_LG.gif)](https://me.alipay.com/shaozhuqing)

=============================================================================================



# jQuery File Upload Plugin

## Demo
[Demo File Upload](http://blueimp.github.io/jQuery-File-Upload/)

## Description
File Upload widget with multiple file selection, drag&amp;drop support, progress bars, validation and preview images, audio and video for jQuery.  
Supports cross-domain, chunked and resumable file uploads and client-side image resizing. Works with any server-side platform (PHP, Python, Ruby on Rails, Java, Node.js, Go etc.) that supports standard HTML form file uploads.

## Setup
* [How to setup the plugin on your website](https://github.com/blueimp/jQuery-File-Upload/wiki/Setup)
* [How to use only the basic plugin (minimal setup guide).](https://github.com/blueimp/jQuery-File-Upload/wiki/Basic-plugin)

## Support

* **[Support Forum](https://groups.google.com/d/forum/jquery-fileupload)**  
**Support requests** and **general discussions** about the File Upload plugin can be posted to the official
[Support Forum](https://groups.google.com/d/forum/jquery-fileupload).  
If your question is not directly related to the File Upload plugin, you might have a better chance to get a reply by posting to [Stack Overflow](http://stackoverflow.com/questions/tagged/blueimp+jquery+file-upload).

* Bugs and Feature requests  
**Bugs** and **Feature requests** can be reported using the [issues tracker](https://github.com/blueimp/jQuery-File-Upload/issues).  
Please read the [issue guidelines](https://github.com/blueimp/jQuery-File-Upload/blob/master/CONTRIBUTING.md) before posting.

## Features
* **Multiple file upload:**  
  Allows to select multiple files at once and upload them simultaneously.
* **Drag & Drop support:**  
  Allows to upload files by dragging them from your desktop or filemanager and dropping them on your browser window.
* **Upload progress bar:**  
  Shows a progress bar indicating the upload progress for individual files and for all uploads combined.
* **Cancelable uploads:**  
  Individual file uploads can be canceled to stop the upload progress.
* **Resumable uploads:**  
  Aborted uploads can be resumed with browsers supporting the Blob API.
* **Chunked uploads:**  
  Large files can be uploaded in smaller chunks with browsers supporting the Blob API.
* **Client-side image resizing:**  
  Images can be automatically resized on client-side with browsers supporting the required JS APIs.
* **Preview images, audio and video:**  
  A preview of image, audio and video files can be displayed before uploading with browsers supporting the required APIs.
* **No browser plugins (e.g. Adobe Flash) required:**  
  The implementation is based on open standards like HTML5 and JavaScript and requires no additional browser plugins.
* **Graceful fallback for legacy browsers:**  
  Uploads files via XMLHttpRequests if supported and uses iframes as fallback for legacy browsers.
* **HTML file upload form fallback:**  
  Allows progressive enhancement by using a standard HTML file upload form as widget element.
* **Cross-site file uploads:**  
  Supports uploading files to a different domain with cross-site XMLHttpRequests or iframe redirects.
* **Multiple plugin instances:**  
  Allows to use multiple plugin instances on the same webpage.
* **Customizable and extensible:**  
  Provides an API to set individual options and define callBack methods for various upload events.
* **Multipart and file contents stream uploads:**  
  Files can be uploaded as standard "multipart/form-data" or file contents stream (HTTP PUT file upload).
* **Compatible with any server-side application platform:**  
  Works with any server-side platform (PHP, Python, Ruby on Rails, Java, Node.js, Go etc.) that supports standard HTML form file uploads.

## Requirements
* [jQuery](http://jquery.com/) v. 1.6+
* [jQuery UI widget factory](http://api.jqueryui.com/jQuery.widget/) v. 1.9+ (included)
* [jQuery Iframe Transport plugin](https://github.com/blueimp/jQuery-File-Upload/blob/master/js/jquery.iframe-transport.js) (included)
* [JavaScript Templates engine](https://github.com/blueimp/JavaScript-Templates) v. 2.2.1+ (optional)
* [JavaScript Load Image function](https://github.com/blueimp/JavaScript-Load-Image) v. 1.7.3+ (optional)
* [JavaScript Canvas to Blob function](https://github.com/blueimp/JavaScript-Canvas-to-Blob) v. 2.0.6+ (optional)
* [Bootstrap CSS Toolkit](https://github.com/twitter/bootstrap/) v. 2.3+ (optional)

The jQuery UI widget factory is a requirement for the basic File Upload plugin, but very lightweight without any other dependencies.  
The jQuery Iframe Transport is required for [browsers without XHR file upload support](https://github.com/blueimp/jQuery-File-Upload/wiki/Browser-support).  
The UI version of the File Upload plugin also requires the JavaScript Templates engine as well as the JavaScript Load Image and JavaScript Canvas to Blob functions (for the image previews and resizing functionality). These dependencies are marked as optional, as the basic File Upload plugin can be used without them and the UI version of the plugin can be extended to override these dependencies with alternative solutions.

The User Interface is built with Twitter's [Bootstrap](https://github.com/twitter/bootstrap/) Toolkit. This enables a CSS based, responsive layout and fancy transition effects on modern browsers. The demo also includes the [blueimp Gallery](https://github.com/blueimp/Gallery). Both of these components are optional and not required.

The repository also includes the [jQuery XDomainRequest Transport plugin](https://github.com/blueimp/jQuery-File-Upload/blob/master/js/cors/jquery.xdr-transport.js), which enables Cross-domain AJAX requests (GET and POST only) in Microsoft Internet Explorer >= 8. However, the XDomainRequest object doesn't support file uploads and the plugin is only used by the [Demo](http://blueimp.github.io/jQuery-File-Upload/) for Cross-domain requests to delete uploaded files from the demo file upload service.

[Cross-domain File Uploads](https://github.com/blueimp/jQuery-File-Upload/wiki/Cross-domain-uploads) using the [Iframe Transport plugin](https://github.com/blueimp/jQuery-File-Upload/blob/master/js/jquery.iframe-transport.js) require a redirect back to the origin server to retrieve the upload results. The [example implementation](https://github.com/blueimp/jQuery-File-Upload/blob/master/js/main.js) makes use of [result.html](https://github.com/blueimp/jQuery-File-Upload/blob/master/cors/result.html) as a static redirect page for the origin server.

## Browsers

### Desktop browsers
The File Upload plugin is regularly tested with the latest browser versions and supports the following minimal versions:

* Google Chrome
* Apple Safari 4.0+
* Mozilla Firefox 3.0+
* Opera 11.0+
* Microsoft Internet Explorer 6.0+

### Mobile browsers
The File Upload plugin has been tested with and supports the following mobile browsers:

* Apple Safari on iOS 6.0+
* Google Chrome on iOS 6.0+
* Google Chrome on Android 4.0+
* Default Browser on Android 2.3+
* Opera Mobile 12.0+

### Supported features
For a detailed overview of the features supported by each browser version please have a look at the [Extended browser support information](https://github.com/blueimp/jQuery-File-Upload/wiki/Browser-support).

## License
Released under the [MIT license](http://www.opensource.org/licenses/MIT).

## Donations
jQuery File Upload is free software, but you can donate to support the developer, Sebastian Tschan:

Flattr: [![Flattr](https://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/thing/286433/jQuery-File-Upload-Plugin)

PayPal: [![PayPal](https://www.paypalobjects.com/WEBSCR-640-20110429-1/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=PYWYSYP77KL54)
