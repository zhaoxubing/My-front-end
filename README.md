目录结构

在这个目录结构中，client 目录包含客户端代码，server 目录包含服务器端代码。
客户端和服务器端的代码都有自己的 package.json 文件和 package-lock.json 文件，这些文件分别用于管理客户端和服务器端的依赖项。

在客户端代码中，通常将静态文件（如图片和样式表）存放在 public 目录下，而组件代码和业务逻辑代码则存放在 src 目录下。
在服务器端代码中，通常将路由代码存放在 routes 目录下，将控制器代码存放在 controllers 目录下，将模型代码存放在 models 目录下。
my-app/
  ├── client/
  │   ├── public/
  │   │   ├── index.html
  │   │   └── favicon.ico
  │   ├── src/
  │   │   ├── index.js
  │   │   └── App.js
  │   ├── package.json
  │   └── package-lock.json
  ├── server/
  │   ├── index.js
  │   ├── routes/
  │   │   └── api.js
  │   ├── controllers/
  │   │   └── apiController.js
  │   ├── models/
  │   │   └── apiModel.js
  │   ├── package.json
  │   └── package-lock.json
  ├── package.json
  └── package-lock.json
