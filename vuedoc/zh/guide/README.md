# 介绍

可视化编辑器可以编辑通用组件的属性值,通用组件是指开发者编写的自定义组件.

编辑器界面可以对组件的数据做动态的绑定(或者是STATIC的).
原理是通过编辑一段SQL语句,保存到数据库后,在页面渲染时候请求后端服务器,
服务器执行连接数据库,并通过数据库查询到SQL并执行返回结果,前端绑定数据的过程.