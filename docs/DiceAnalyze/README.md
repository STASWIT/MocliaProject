## Dice!源码文件内容
> 已完成解析的文件会在复选框前打勾。  
### 外部引用

+ [CQCPPSDK](https://github.com/cqmoe/cqcppsdk) —— 对接酷Q使用的SDK  
+ [Nlohmann/Json.h Json for modern C++](https://github.com/nlohmann/json) —— Json解析相关库  

### 头文件目录及可能作用

+ [ ] [APPINFO.h](DiceAnalyze/head/APPINFO.h.md) —— 酷q相关，应用id和应用介绍，无对应CPP
+ [ ] [DiceXMLTree.h](DiceAnalyze/head/DiceXMLTree.h.md) —— XML树状结构，用途未知  
+ [ ] [Jsonio.h](DiceAnalyze/head/Jsonio.h.md) —— Json处理相关  
+ [ ] [RDConstant.h](DiceAnalyze/head/RDConstant.h.md) —— 常量调用相关
+ [ ] [STLExtern.hpp](DiceAnalyze/head/STLExtern.hpp.md) —— 自定义容器，功能暂时未知
+ [ ] [StrExtern.hpp](DiceAnalyze/head/StrExtern.hpp.md) —— 字符串辅助函数  
---
+ [ ] [BlackListManager.h]() —— 黑名单相关  
+ [ ] [CardDeck.h]() —— 牌堆抽卡相关  
+ [ ] [CharacterCard.h]() —— 人物卡相关   
+ [ ] [DiceCloud.h]() —— 骰娘网络相关  
+ [ ] [DiceConsole.h]() —— 骰娘控制台相关  
+ [ ] [DiceEvent.h]() —— 消息事件相关  
+ [ ] [DiceFile.hpp]() —— 文件读写相关  
+ [ ] [DiceMod.h]() —— 资源相关  
+ [ ] [DiceMsgSend.h]() —— 多线程消息发送相关  
+ [ ] [DiceNetwork.h]() —— 网络访问命名空间相关  
+ [ ] [DiceSession.h]() —— 会话控制相关，可能和.OB旁观指令相关。  
+ [ ] [EncodingConvert.h]() —— 编码转换相关  
+ [ ] [GetRule.h]() —— 规则获取相关  
+ [ ] [GlobalVar.h]() —— **可能** 为全局变量相关  
+ [ ] [ManagerSystem.h]() —— 后台管理系统相关  
+ [ ] [MsgFormat.h]() —— **猜测** 为消息格式相关  
+ [ ] [MsgMonitor.h]() —— 消息检测相关  
+ [ ] [RandomGenerator.h](DiceAnalyze/head/RandomGenerator.h.md) —— 随机生成器相关  
+ [ ] [RD.h]() —— 掷骰相关  
+ [ ] [StorageBase.h]() —— 存取相关  

### 源文件目录及可能作用

+ [ ] [Dice.cpp](DiceAnalyze/sources/Dice.cpp.md) —— 主实现
+ [ ] [DiceUpdate.cpp]() —— 骰娘插件更新
+ [ ] [dllmain.cpp]() —— 动态链接库主实现
---
+ [ ] [BlackListManager.cpp]() —— 黑名单相关  
+ [ ] [CardDesk.cpp]() —— 牌堆抽卡相关  
+ [ ] [CharacterCard.cpp]() —— 人物卡相关  
+ [ ] [DiceCloud.cpp]() —— 骰娘网络相关  
+ [ ] [DiceConsole.cpp]() —— 骰娘控制台相关  
+ [ ] [DiceEvent.cpp]() —— 消息事件相关  
+ [ ] [DiceFile.cpp]() —— 文件读写相关  
+ [ ] [DiceMod.cpp]() —— 资源相关  
+ [ ] [DiceMsgSend.cpp]() —— 多线程消息发送相关  
+ [ ] [DiceNetwork.cpp]() —— 网络访问命名空间相关  
+ [ ] [DiceSession.cpp]() —— 会话控制相关，可能和 **.OB** 旁观指令相关。  
+ [ ] [EncodingConvert.cpp]() —— 编码转换相关  
+ [ ] [GetRule.cpp]() —— 规则获取相关  
+ [ ] [GlobalVar.cpp]() —— **可能** 为全局变量相关  
+ [ ] [ManagerSystem.cpp]() —— 后台管理系统相关  
+ [ ] [MsgFormat.cpp]() —— **猜测** 为消息格式相关  
+ [ ] [MsgMonitor.cpp]() —— 消息检测相关  
+ [x] [RandomGenerator.cpp](DiceAnalyze/sources/RandomGenerator.cpp.md) —— 随机生成器相关  
+ [ ] [RD.cpp]() —— 掷骰相关  
+ [ ] [StorageBase.cpp]() —— 存取相关  