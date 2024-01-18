<!--
 * @Description: 
 * @Author: Rabbiter
 * @Date: 2023-03-05 20:17:11
-->
### 启动项目
``` bash
# 切换镜像
npm config set registry https://registry.npm.taobao.org

# 安装依赖，对应node -v 16.13.2
npm install node-sass@6.0.1 --save-dev
npm install sass-loader@10.2.0 --save-dev
npm install

# 启动项目
npm run dev
