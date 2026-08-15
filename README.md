<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/README/vapelogo-white.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/README/vapelogo-dark.png">
    <img alt="vape logo" src="https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/README/vapelogo.png">
  </picture>
</p>
<h2 align="center">
  一个完全从零构建的 Roblox 脚本，精准满足您的需求！
  <br/>
  在保持绝对不可追上的同时，直冲巅峰。
</h2>

> **📌 中文版说明**  
> 本 README 为原项目 [VapeV4ForRoblox](https://github.com/7GrandDadPGN/VapeV4ForRoblox) VapeV4脚本的完整中文翻译版本，内容严格遵循原文，仅作语言转换  
> **原作者**：[7GrandDad](https://github.com/7GrandDadPGN)（项目主要作者）  
> **中文版翻译+二改**：
[wc5789](https://github.com/wc5789)（翻译者）

---

## 联系方式 原作者
[Discord](https://discord.gg/5gJqhQmrdS)  
[YouTube](https://youtube.com/c/7GrandDadVape)

## 使用方法
1.下载Roblox脚本执行器。  
2.执行下方的 loadstring 代码。

```luau
loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()  
```
---


可能遇到的问题

一半的情况下，问题通常出在脚本执行器本身，请确保执行器满足以下质量标准：

1. 支持文件函数（file functions）和调试库（debug library）。
2. 不使用自己生成或半成品版本的此类函数，以免产生意外行为。
3. 在所有使用场景下保持相同的行为。

用户自身问题

如果问题并非执行器引起，请尝试以下排查步骤：

1. 删除 newvape 文件夹（务必在游戏关闭时操作）。
2. 确认您能正常访问 主 loadstring 地址。
3. 确保没有外部脚本与 Vape 发生冲突。

开发者与致谢

· 7GrandDad —— 项目主要维护者（Discord：vaperoblox）
· rce-incorporated —— 提供修改版 Luau 字节码反汇编
· Egor Skriptunoff, boatbomber, and howmanysmall —— 提供 Luau 的 HashLibrary
· Vernumerator —— 提供 Roblox 抛射物弹道预测方案
· wc5789 —— 进行了中文翻译和二改（只修改了语言）