# -Unity-IL2Cpp_AOT_Interpreter


[![](https://img.shields.io/badge/made%20by-HuaTuo-blue.svg?style=flat-square)](https://protocol.ai)
[![](https://img.shields.io/badge/Unity%20Ver-2020.3.33f1-blue.svg?style=flat-square)](https://protocol.ai)
[![](https://img.shields.io/badge/project-Unity_IL2CPP_HotFIx-yellow.svg?style=flat-square)](https://libp2p.io/)
[![](https://img.shields.io/badge/freenode-%23libp2p-yellow.svg?style=flat-square)](https://webchat.freenode.net/?channels=%23libp2p)
[![codecov](https://codecov.io/gh/libp2p/go-reuseport/branch/master/graph/badge.svg)](https://codecov.io/gh/libp2p/go-reuseport)
[![Travis CI](https://travis-ci.org/libp2p/go-reuseport.svg?branch=master)](https://travis-ci.org/libp2p/go-reuseport)
[![Discourse posts](https://img.shields.io/discourse/https/discuss.libp2p.io/posts.svg)](https://discuss.libp2p.io)

---
## 【HuaTuo热更框架】

### HuaTuo热更框架使用Cpp开发，原理(Unity)IL2Cpp_AOT_Interpreter，在原生层面支持C#的dll热更新。

### huatuo自身并没有一个完整的虚拟机系统而是借由Unity Native和IL2CPP本身驱动执行自己的一套简单的解释执行栈帧，并且由于其自身就是IL2CPP的拓展，所以跨域调用性能也很强劲（毕竟只是几次指针跳转和函数调用），借助于C++的指针偏移和函数调用能获得相当强力的性能
---

<!--```Json-->
<!--项目结构-->

<!--Assets-->
<!--├── Resources    // Resources目录-->
<!--├── Scenes       // 场景-->
<!--└── Scripts      // 脚本资源-->

<!--Scripts-->
<!--├── Core                // 基础框架-->
<!--|   ├── 3rd             // 三方插件-->
<!--|   ├── Common          // Common-->
<!--|   ├── Editor          // Editor-->
<!--|   ├── Event           // Event-->
<!--|   ├── ECS             // ECS架构-->
<!--├── Game                // 核心逻辑-->
<!--|   ├── Actor           // 角色系统-->
<!--|   ├── ActorName       // ActorName-->
<!--|   ├── Bubble          // Bubble-->
<!--|   ├── Camera          // Camera-->
<!--|   ├── DataCenter      // 数据中心-->
<!--|   ├── Proto           // 协议相关-->
<!--|   └── UI              // UI-->
<!--├── GameApp.cs          // 主入口-->
<!--└── GameApp_RegisterSystem.cs      // 主入口注册系统-->
<!--```-->