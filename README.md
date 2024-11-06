# 全目录

3000套系统，根据编号搜索演示视频，复制至流浪器：www.yuque.com/wisebit/blog


![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/11/06/qq_wechat.png)
# springboot692智慧养老平台
# 5系统详细设计
## 5.1系统功能模块
智慧养老平台，在系统首页可以查看首页、活动信息、便利店、劳工、服务项目、个人中心、后台管理等内容，并进行详细操作；如图5-1所示。

![](/md/blog.012.png)

图5-1系统首页界面图

活动信息，在活动信息页面中可以查看活动标题、活动分类、开始时间、结束时间、活动地点等内容进行收藏等操作，如图5-2所示。

![](/md/blog.013.png)

图5-2活动信息界面图

便利店，在便利店页面可以查看商品名称、生产地、数量、单价、商品分类等内容进行详情或收藏等操作，如图5-3所示。

![](/md/blog.014.png)

图5-3便利店界面图

服务项目，在服务项目页面可以查看项目名称、项目类型、项目价格、劳工姓名等内容进行详情或收藏等操作，如图5-4所示。

![](/md/blog.015.png)

图5-4服务项目界面图

`    `个人中心，在个人中心页面通过填写老人账号、密码、老人姓名、性别、年龄、图片、老人手机、积分、老人地址等内容进行更新信息等操作，并可以根据我的收藏进行相应的操作，如图5-5所示。

![](/md/blog.016.png)

图5-5个人中心界面图
## 5.2后台登录功能
管理员和老人进入系统前在登录页面根据要求填写用户名和密码，选择角色等信息，点击登录进行登录操作，如图5-6所示。

![](/md/blog.017.png)

图5-6登录界面图
### 5.2.1管理员功能
管理员登录系统后，可以对首页、个人中心、老人管理、亲属管理、每日健康管理、既往病史管理、活动分类管理、活动信息管理、商品类型管理、便利店管理、商品购买管理、劳工管理、服务类型管理、服务项目管理、服务购买管理、紧急求助管理、礼品发放管理、积分增加管理、系统管理等功能进行相应的操作管理，如图5-7所示。

![](/md/blog.018.png)

图5-7管理员功能界面图

老人管理，在老人管理页面可以对索引、老人账号、老人姓名、性别、年龄、照片、老人手机、积分、老人地址等内容进行详情、礼品发放、积分增加、修改或删除等操作，如图5-8所示。

![](/md/blog.019.png)

图5-8老人管理界面图

亲属管理，在亲属管理页面可以对索引、老人账号、亲属姓名、性别、联系方式、与老人关系等内容进行详情、修改或删除等操作，如图5-9所示。

![](/md/blog.020.png)

图5-9亲属管理界面图

每日健康管理，在每日健康管理页面可以对索引、老人账号、老人姓名、性别、年龄、体温、血压、心跳、健康报告、添加时间等内容进行详情、修改或删除等操作，如图5-10所示。

![](/md/blog.021.png)

图5-10每日健康管理界面图

既往病史管理，在既往病史管理页面可以对索引、老人账号、老人姓名、性别、年龄、登记时间等内容进行详情、修改或删除等操作，如图5-11所示。

![](/md/blog.022.png)

图5-11既往病史管理界面图

活动信息管理，在活动信息管理页面中可以对索引、活动标题、封面、活动分类、开始时间、结束时间、活动地点等内容进行详情、修改或删除等操作，如图5-12所示。

![](/md/blog.023.png)

图5-12活动信息管理界面图

便利店管理，在便利店管理页面中可以对索引、商品编号、商品名称、出生地、数量、单价、商品分类、商品图片等内容进行详情、进货、修改或删除等操作，如图5-13所示。

![](/md/blog.024.png)

图5-13便利店管理界面图

商品进货管理，在商品进货管理页面可以对索引、进货编号、商品名称、数量、进货单价、进货总价、进货时间、备注等内容进行详情、修改或删除等操作，如图5-14所示。

![](/md/blog.025.png)

图5-14商品进货管理界面图

劳工管理，在劳工管理页面中可以对索引、劳工姓名、性别、年龄、图片、工作年龄、专长等内容进行详情、修改、查看评论或删除等操作；如图5-15所示。

![](/md/blog.026.png)

图5-15劳工管理界面图

服务购买管理，在服务购买管理页面中可以对索引、下单编号、项目名称、服务类型、项目价格、劳工姓名、老人姓名、老人手机、老人地址、预约时间、下单时间、备注、是否支付、审核回复、审核状态、审核等内容进行详情、修改或删除等操作，如图5-16所示。

![](/md/blog.027.png)

图5-16服务购买管理界面图

礼品发放管理，在礼品发放管理页面中可以对索引、老人账号、老人姓名、老人手机、积分、礼品、礼品图片、发放时间、发放人等内容进行详情、修改或删除等操作，如图5-17所示。

![](/md/blog.028.png)

图5-17礼品发放管理界面图

积分增加管理，在积分增加管理页面中可以对索引、老人账号、老人姓名、积分、增加时间等内容进行详情、修改或删除等操作，如图5-18所示。

![](/md/blog.029.png)

图5-18积分增加管理界面图

### 5.2.2老人功能
老人注册，通过填写老人账号、密码、确认密码、老人姓名、年龄老人手机、老人地址等内容进行注册等操作，如图5-19所示。

![](/md/blog.030.png)

图5-19老人注册界面图

老人登录系统后，可以对首页、个人中心、亲属管理、每日健康管理、既往病史管理、商品购买管理、服务购买管理、紧急求助管理、礼品发放管理、积分增加管理等功能进行相应的操作管理，如图5-20所示。

![](/md/blog.031.png)

图5-20老人功能界面图

亲属管理，在亲属管理页面中可以对索引、老人账号、亲属姓名、性别、联系方式、与老人关系等内容进行详情、修改或删除等操作；如图5-21所示。

![](/md/blog.032.png)

图5-21亲属管理界面图

商品购买管理，在商品购买管理页面中可以对索引、订单编号、商品名称、商品分类、数量、单价、总价、老人账号、老人姓名、老人手机、下单时间、备注、是否支付、审核回复、审核状态等内容进行详情或删除等操作，如图5-22所示。

![](/md/blog.033.png)

图5-22商品购买管理界面图

服务购买管理，在服务购买管理页面中可以对索引、下单编号、项目名称、 服务类型、项目价格、劳工姓名、老人账号、老人手机、老人地址、预约时间、下单时间、备注、是否支付、审核回复、审核状态等内容进行详情或删除等操作，如图5-23所示。

![](/md/blog.034.png)

图5-23服务购买管理界面图

商品购买管理，在商品购买管理页面中可以对索引、订单编号、商品分类、数量、单价、总价、老人账号、老人姓名、老人手机、备注、是否支付、审核回复、审核状态等内容进行详情或删除等操作，如图5-24所示。

![](/md/blog.035.png)

图5-24商品购买管理界面图

