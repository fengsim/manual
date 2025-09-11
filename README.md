# WEB端使用说明

点击[链接](https://run-web-app.pre-env.cae001.com/projects)进入WEB端。

## 模态分析

在通用模块中点击结构模态分析软件。

### 导入网格文件

目前可以导入.inp格式的网格文件。点击工具栏中添加网格模型，弹出对话框，点击浏览文件，选择.inp文件，如下图。可以选择FENGSim/starter/ccx/oiltank路径中的modal.inp文件。

![项目截图](./fig/1.png)

导入网格文件后可以看到下图。

![项目截图](./fig/2.png)

### 设置材料和边界条件

对于模态分析来说，可以不设置边界条件，或者设置homogeneous Dirichlet边界条件。

#### 设置材料

如上图，在左侧工具栏中有网格文件的树形结构。modal.inp是根节点，子节点包括单元组和节点组，support、pipe、sphere\_tank为单元组，pip\_fixed\_nodes、fixed\_nodes、inner\_surface\_nodes、outer\_surface\_nodes为节点组。点击support，再点击工具栏中的选择材料，再点击材料模型（**这个材料模型是否去掉，或者增加另外一个选项**），弹出对话框，如下图，可以选择Aluminum alloys，点击右下角应用按钮确认。

![项目截图](./fig/3.png)

#### 设置边界条件

