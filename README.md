# CTTextDisplayView

************* 更新 2016/04/05 处理邮箱、电话号码、颜色、下划线等 **************

************* 上传 2016/04/02 Start **************

************* 主要处理系统自带emoji表情、中英文导致的行距不一致的问题 

网上找到了几个比较好的图文混排库，但是都达不到自己想要的简单粗暴的效果，于是借鉴TQRichTextView的思想写了CTTextDisplayView，解决了文本中系统英文/自带emoji表情行距不一样、表情大小定制、字距等一些问题，并没有处理号码、邮箱及更多定制功能，代码简单易修改，所以需要的可以自己修改定制。

************* 上传 2016/04/02 End ****************

示例:

  效果:xxx@张三xxx

  代码:xxx@{张三}xxx 或 xxx@{张三:id}xxx
	


  效果:xxx#过年了#xxx

  代码:xxx#{过年了}xxx  或  xxx#{过年了:id}xxx



  效果:张三 回复 李四

  代码:${张三} 回复 ${李四:id}

*********************  email:347991555@q.com   *************************

![CTTextDisplayView](https://github.com/BrownCN023/CTTextDisplayView/blob/master/ScreenShot.png)