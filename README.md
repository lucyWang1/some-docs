### 从零创建VUE项目

1.安装NodeJS

> 从NodeJS 官网（ http://nodejs.cn/ ）下载需要的安装包。
> 安装后，输入以下命令，查看版本号检查是否安装成功。
> NodeJS 安装后， 就可以使用包管理器npm

> ```
> node -v
> npm -v
> ```

2.使用 npm 国内镜像

> `npm install -g cnpm --registry=https://registry.npm.taobao.org`

> 现在可以使用cnpm install 代替npm install 安装包

3.借助vue-cli初始化vue项目
> 全局安装vue-cli工具包 <br><br>
> `cnpm install -g @vue/cli`


> 创建项目<br>

> `vue create my-project` <br><br>
> 根据命令行交互提示， 安装需要的包


>或者可视化创建项目<br>

> `vue ui` <br><br>
> 切换目录

> `cd my-project `<br>

> 安装依赖

> `cnpm install`<br>

>  本地运行项目

> `npm run serve`<br>

> 项目打包

> `npm run build`


> 网站链接

> vue-cli （https://cli.vuejs.org/zh/）

> vue (https://cn.vuejs.org/)
