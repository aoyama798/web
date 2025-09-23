# 创二病人管理

步骤 1：
创建 Firebase 项目
进入 Firebase 控制台
创建一个新项目（比如叫 “hospital-patient”）。
在左侧菜单选择 构建 → Firestore Database，创建数据库（选择“测试模式”即可，后面再加权限）。
在 项目设置 → 常规 → 我的应用 中，点击 Web 应用，注册应用，会得到一段 firebaseConfig 配置。

步骤 2：构建GitHub Pages静态网站 
教程：https://blog.csdn.net/qq_20042935/article/details/133920722
（需翻墙）

步骤 3：复制我的源码index.html

步骤 4：从第216行开始换为自己的数据库：

    const firebaseConfig = {
      apiKey: "AIzaSyDAXDiMOzZhYJw60HsO47iFt_OuTGHY8-Y",
      authDomain: "patient-ed38f.firebaseapp.com",
      databaseURL: "https://patient-ed38f-default-rtdb.firebaseio.com",
      projectId: "patient-ed38f",
      storageBucket: "patient-ed38f.firebasestorage.app",
      messagingSenderId: "871945702518",
      appId: "1:871945702518:web:5b93500a0a0941a20c2357",
      measurementId: "G-0BFKEDCZ2B"
    };

    
