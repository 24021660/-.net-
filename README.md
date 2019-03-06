# -.net-
公司网站出现问题，这两天进行修复：
首先，问题列表：
1. http://www.bjttsf.com/wap/xinw/xinwlb_693.html
翻页、头部、后台上传19年数据不生成静态页

2. http://www.bjttsf.com/wap/zaixianbx/zaixbx_679.html
http://www.bjttsf.com/wap/swx/ptty_792.html
提交表单有问题

3. http://www.bjttsf.com/wap/chanp/chanplb_622_2754.html  立即采购有问题
4. http://www.bjttsf.com/wap/chanp/chanplb3_643.html 图片加载很慢
5. http://www.bjttsf.com/wap/chanp/chanplb3.aspx?nodeid=644&pagesize=1&pagenum=12  头部问题
6. 后台显示，能按提交的时间排序吗？现在是乱的，总找不到新提交的信息
 
7. http://www.bjttsf.com/admin/login.aspx  总提示不安全，360和sougo浏览器提示不安全
 
8.服务器是否需在按装ftp？后期维护是安全还是不安全？要是安全是不是需配置下？
9.服务器提示有严重的安全问题，是否需要配置调整下？
 
 
10. http://www.bjttsf.com/wap/gyrj/gyrj_724.html
banner，后台显示3个，前台只显示两个

源码到手，vs进行运行报错：
	HTTP Error 500.22 - Internal Server Error
	检测到在集成的托管管道模式下不适用的 ASP.NET 设置。

各种百度进行修改，新错误出现：

未能加载类型“MyApp.MyModule”。 
	说明: 执行当前 Web 请求期间，出现未处理的异常。请检查堆栈跟踪信息，以了解有关该错误以及代码中导致错误的出处的详细信息。 
	异常详细信息: System.Web.HttpException: 未能加载类型“MyApp.MyModule”。


