\# 系统架构文档



\## 模块划分

\- \*\*主控层\*\* (`main\_controller.py`): 系统调度核心，导师维护

\- \*\*硬件接口层\*\* (`hardware\_interface/`): 设备通信，学生A负责

\- \*\*算法层\*\* (`stim\_algorithm/`): 刺激波形计算，学生B负责



\## 开发流程

1\. Fork 主仓库到个人账号

2\. 功能开发在 feature/\* 分支进行

3\. 通过 Pull Request 提交到 main 分支

