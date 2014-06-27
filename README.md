jQuery Mobile - Notice Plugin
==================

###demo
[See a demo](https://github.com/is8r/jquerymobile-notice)

![qrcode](https://cloud.githubusercontent.com/assets/822147/3407382/815568de-fda9-11e3-8230-7cf1bcd38dea.png)

## Installation

Include script after the jQuery Mobile library.

```
  <script src="common/plugin/notice/js/jquery.mobile.notice.js"></script>
  <link href="common/plugin/notice/css/jquery.mobile.notice.css" rel="stylesheet" />
```
	
## Usage

Sucsess Notification.

```
 $.mobile.notice({
   type: 'success',
   title: 'Success',
   content: 'Success content.'
 });
```

Error Notification.

```
 $.mobile.notice({
   type: 'error',
   title: 'Error',
   content: 'Error content.'
 });
```

