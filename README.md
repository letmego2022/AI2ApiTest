# AI2ApiTest

## AI 驱动的接口自动测试平台

AI 驱动的接口自动测试平台利用人工智能技术自动化测试用例生成、执行、断言和报告，提高测试效率和覆盖率，同时与 CI/CD 流程集成，实现持续测试和质量保证。

### 演示地址
- [在线演示](http://134.175.222.87:5006)      不定期

### 功能演示
- **登录界面**：
  ![image](https://github.com/user-attachments/assets/8d3c4a2d-25aa-48e0-9630-9b4ebf37c0cd)
- **生成接口测试用例**：
  ![image](https://github.com/user-attachments/assets/ffa84a8b-bdcd-497e-9dd9-29dd1c4ed564)
- **查看测试用例**：
  ![image](https://github.com/user-attachments/assets/3a7aaabe-9f87-47fb-8921-3460bb3733e3)
- **生成pytest脚本**：
  ![image](https://github.com/user-attachments/assets/cfd22216-3b77-4bda-bb26-14f3c9aaed09)
- **脚本调整**：
  ![image](https://github.com/user-attachments/assets/8682ec26-a73c-4e80-bd48-5ba80330f6e1)
- **流程节点prompt修改**：
  ![image](https://github.com/user-attachments/assets/28865536-610f-4344-b91e-b2b4e201f4ef)
- **all in one**:
  ![image](https://github.com/user-attachments/assets/766c84a0-adb4-47da-9347-38f64d2be42e)

### 代码设计
/my_flask_app
- /app
  - /blueprints
    - __init__.py
    - auth.py        # 登录相关模块
    - xxxx.py        # 其他相关模块
  - /static            # 静态文件
  - /templates         # HTML 模板
    - login.html     # 登录页面模板
    - xxxxx.html     # 其他页面模板
  - /utils             # 工具函数
  - /models            # 数据库模型
  - __init__.py        # 应用初始化
- config.py              # 配置文件
- requirements.txt       # 项目依赖
- run.py                 # 应用入口
### 贡献指南
~~我们欢迎任何形式的贡献，请在提交前阅读我们的[贡献指南](CONTRIBUTING.md)。~~

### 许可证
~~本项目采用[MIT许可证](LICENSE)。~~
