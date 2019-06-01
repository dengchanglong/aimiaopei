# aimiaopei
one project for test
配置中心有哪些功能呢？

1.将配置统进行集中管理，提供一配置服务，开发、测试、生产环境均可直接从配置服务器中读取配置信息。大致就是，应用在启动后从配置服务器中获取配置信息，加入到环境中。这样所有的配置服务都可以进行集中管理。

2.追溯到配置变更的历史，诸如是谁在什么时候修改了哪些内容，根据这些信息进行配置回滚操作。

3.配置中心还能够增加权限管理，保证不同角色不同权限的人只能访问到可看的配置，防止重要线上配置信息的泄露。

ModelAndView包含两部分：一个View和一个Model
View由setViewName()方法来决定，决定让ViewResolver去哪里找View文件，并找到是哪个jsp文件；
Model由addObject()方法来决定，它的本质是java的HashMap，键值对；
用人话来解释ModelAndView的功能就是，View负责渲染Model，让你找到代表View的jsp，用这个jsp去渲染Model中的数据。
