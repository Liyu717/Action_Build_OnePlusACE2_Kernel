### 使用GitHub Action 构建一加ACE2内核（KernelSU,SukiSU,KernelSU NEXT）
注意：
- 只用于OKI5.10的构建，请不要问除（一加ACE2）以外其他机型的问题
- 可选原版KernelSU,，MKSU，SukiSU,Kernelsu NEXT(同样支持Wild Ksu)
- SukiSU不接受关于KPM的反馈，因为本身就有BUG
- 除了SukiSU外，勾选SUSFS都需要安装模块，否则无法调整设置
- action思路以及部分代码 来自[https://github.com/Numbersf] (其实大部分都是从人家那里偷来的还没求授权)
## 注意：当上游更新仓库时，SUSFS可能没有同步上游，所以有时候会导致SUSFS不可用，请等待上游仓库更新，或者使用旧版
~~为什么没有原版KSU和MKSU的SUSFS~~
~~因为主播不会打补丁，打上去在模块也不显示，破防了~~
## 请注意主页的更新日志！
试着添加了SUSFS V1.5.12 KSU V1.0.5 ,理论可用
