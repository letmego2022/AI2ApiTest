## 平台1：用例生成**AI2ApiTest**

### **AI 驱动的用例生成平台**

一个基于人工智能的自动化测试用例生成平台，帮助开发者更高效地创建、优化和管理测试用例。
### **第二阶段：Maker-Checker 架构升级**

在第二阶段中，引入 **Maker-Checker** 概念，以提升测试用例生成的覆盖度与可靠性。

- **Maker 组（并联式设计）**  
  由多个专业化 Agent 组成，分别负责生成不同类型的测试用例：  
  - **Positive Case Agent** —— 生成正向用例  
  - **边界值分析师 (Boundary Value Analyst)** —— 生成边界值测试用例  
  - **错误场景推演师 (Error Guessing Specialist)** —— 生成异常/错误输入用例  
  - **状态机攻击手 (State Machine Attacker)** —— 生成状态机攻击与越权场景用例  

- **Checker 组**  
  负责对 Maker 组生成的测试用例进行验证与优化：  
  - 检查用例的 **完整性**（是否覆盖关键场景）  
  - 检查用例的 **有效性**（是否符合需求逻辑）  
  - 检查用例的 **去重性**（避免冗余与冲突）  

> 通过 **Maker 并联生成 + Checker 严格把关**，系统能够产出更高质量、更全面的测试用例集。
<img width="410" height="250" alt="image" src="https://github.com/user-attachments/assets/fad9752c-b00c-4c6e-83b6-33fb151a9d40" />

### **演示地址**
- [AI2ApiTest 演示地址](http://134.175.222.87:5016/)
- 新地址：[AI2ApiTest 新地址](http://134.175.222.87:5006/)

### **Todo List**
- [ ] **安全设计**
  - [x] 针对脚本编辑，避免执行命令
  - [x] 增加图形验证码

### **Doing List**
- [x] 针对历史聊天中的继续会话进行优化，以便生成更高质量的测试用例


### **功能更新（2024/12/16）**
#### **用户故事扩展**
用户可以输入一个用户故事（User Story），然后 AI 会自动扩展为详细的功能设计文档。

1. **用户输入用户故事**
   用户输入故事并停留 1 秒后，出现“AI 扩充”按钮。
   ![image](https://github.com/user-attachments/assets/b2f8acbf-685c-48b4-ae6a-7dab6b860d0a)

2. **AI 扩充**
   点击 AI 扩充按钮后，返回详细的功能设计内容，便于拓展用户输入内容的维度。
   ![image](https://github.com/user-attachments/assets/986e230c-df94-4f99-ac69-1934823e202d)

3. **生成测试用例**
   点击“生成测试用例”按钮，基于功能设计生成测试用例。
   ![image](https://github.com/user-attachments/assets/7535bfab-ac43-48d3-83ea-4a0e1f37b1de)

### **Test Case 生成优化过程**
1. **新建会话**
   ![image](https://github.com/user-attachments/assets/72bd9f56-d79d-4458-9cac-2efc95866ac3)

2. **选择历史会话并进入对话模式**
   ![image](https://github.com/user-attachments/assets/51c64af1-3192-43f6-8820-ea6a3a8dc3f9)

3. **根据需求优化生成测试用例**
   ![image](https://github.com/user-attachments/assets/3fc876da-177b-4a7e-9361-2bd66980fb0d)

4. **测试用例展示为列表**
   ![image](https://github.com/user-attachments/assets/bf289ca3-a5fe-458c-add0-48bfce1c85e4)
   
### **新功能：驱动器**
![驱动器功能截图](https://github.com/user-attachments/assets/4604eac9-442b-4f3d-84da-69d6284052c4)


### **演示视频**
观看此视频以了解如何使用本项目，并探索其功能和性能：
[![演示视频](https://img.youtube.com/vi/eSo_Ur-X9KE/0.jpg)](https://youtu.be/eSo_Ur-X9KE)


### **贡献指南**
我们欢迎任何形式的贡献！请在提交 PR 前阅读我们的 [贡献指南](CONTRIBUTING.md)。

### **许可证**
本项目采用 [MIT 许可证](LICENSE.TXT)，详细内容请查看 `LICENSE.TXT` 文件。

 -----------------------------------------------------------------------
 

