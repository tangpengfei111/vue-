业余时间写的关于vue两个框架的训练，以及一些小工具

* [vue.js + node.js  后台管理平台(vue_system)](#vue_system)<br/>


>技术：Vue, Vue-Router, Vuex, Node.js, Express, Jwt, WebPack

　　项目模仿的是中国电信一款管理手机的MDM管理平台，包括设备管理、用户管理、推送管理等模块,实现根据设备、用户信息的增删改查，用户的登录验证，路由拦截等功能；后台为Node.js，配合前端的vue技术栈实现前后端联调。重点练习vue的运用，数据的增删改查、手机与用户之间的关联、递归生成树状导航、Echarts插件运用、前后端数据交互等，对后端数据处理有了更深的理解。实际项目中部分涉及手机终端定位、策略调控，推送信息等，无法实现。

[项目代码](https://github.com/tangpengfei111/private-project/tree/sss/vue_system)

功能：

* 用户注册登录、退出登录
* 添加手机信息，实现用户、部门关联
* 用户分组、部门之间进行关联
* 用户操作查询

注册登录
![image](https://github.com/tangpengfei111/private-project/blob/master/vue_system/load.gif)

添加部门
![image](https://github.com/tangpengfei111/private-project/blob/master/vue_system/associated.gif)

关联部门
![image](https://github.com/tangpengfei111/private-project/blob/master/vue_system/addDepartment.gif)


