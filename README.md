### 技术栈

```
编程语言：TypeScript 4.x + JavaScript
构建工具：Vite 2.x
前端框架：Vue 3.x
路由工具：Vue Router 4.x
状态管理：Vuex 4.x
UI 框架：Element Plus
CSS 预编译：Stylus / Sass / Less
HTTP 工具：Axios
Git Hook 工具：husky + lint-staged
代码规范：EditorConfig + Prettier + ESLint + Airbnb JavaScript Style Guide
提交规范：Commitizen + Commitlint
单元测试：vue-test-utils + jest + vue-jest + ts-jest
自动部署：GitHub Actions
```


###
   -- yarn create @vitjs/app  /   npm init @vitejs/app
      输入项目名称（demo）-->>选择模板 （vue-ts）-->>进入项目目录(cd ..)-->> 安装依赖（yarn install） -->> 启动项目（npm run dev）

   -- 项目配置
      vite-config-ts  vite 配置   // 详细配置文档：https://vitejs.dev/config/
      npm i vue-router@4  路由配置
      npm i vuex@next  vuex配置
      npm i element-plus  UI框架
      npm i axios  HTTP 工具（配置：请求拦截，响应拦截....)
      npm i stylus -D   /  npm i sass -D   /   npm i less -D   css预编译 sass/less/stylus

   -- 代码规范
      EditorConfig  配置（根目录下新建文件 .editorConfig ） // 详细配置见：editorconfig.org

   -- 提交规范

   -- 单元测试 jest vue-test-utils vue-jest ts-jest
      安装依赖：npm i @vue/test-utils@next jest vue-jest@next ts-jest -D


   -- 自动部署  gitHub Action

       