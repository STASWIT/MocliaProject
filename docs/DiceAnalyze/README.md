## Dice!源码文件内容
### 外部引用

+ [CQCPPSDK](https://github.com/cqmoe/cqcppsdk) —— 对接酷Q使用的SDK  
+ [Nlohmann/Json.h Json for modern C++](https://github.com/nlohmann/json) —— Json解析相关库  

### 头文件目录及可能作用

+ [APPINFO.h]() —— 酷q相关，应用id和应用介绍  
+ [BlackListManager.h]() —— 黑名单相关  
+ [CardDeck.h]() —— 牌堆抽卡相关  
+ [CharacterCard.h]() —— 人物卡相关   
+ [DiceCloud.h]() —— 骰娘网络相关  
+ [DiceConsole.h]() —— 骰娘控制台相关  
+ [DiceEvent.h]() —— 消息事件相关  
+ [DiceFile.hpp]() —— 文件读写相关  
+ [DiceMod.h]() —— 资源相关  
+ [DiceMsgSend.h]() —— 多线程消息发送相关  
+ [DiceNetwork.h]() —— 网络访问命名空间相关  
+ [DiceSession.h]() —— 会话控制相关，可能和.OB旁观指令相关。  
+ [DiceXMLTree.h]() —— XML树状结构，用途未知  
+ [EncodingConvert.h]() —— 编码转换相关  
+ [GetRule.h]() —— 规则获取相关  
+ [GlobalVar.h]() —— **可能**为全局变量相关  
+ [Jsonio.h]() —— Json处理相关  
+ [ManagerSystem.h]() —— 后台管理系统相关  
+ [MsgFormat.h]() —— **猜测**为消息格式相关  
+ [MsgMonitor.h]() —— 消息检测相关  
+ [RandomGenerator.h]() —— 随机生成器命名空间相关  
+ [RD.h]() —— 掷骰相关  
+ [RDConstant.h]() —— 常量调用相关
+ [STLExtern.hpp]() —— 自定义容器，功能暂时未知
+ [StorageBase.h]() —— 存取相关
+ [StrExtern.hpp]() —— 字符串辅助函数

### 源文件目录及可能作用

+ [BlackListManager.cpp]()
+ [CardDesk.cpp]()
+ CharacterCard.cpp
+ Dice.cpp
+ DiceCloud.cpp
+ DiceConsole.cpp
+ DiceEvent.cpp
+ DiceFile.cpp
+ DiceMod.cpp
+ DiceMsgSend.cpp
+ DiceNetwork.cpp
+ DiceSession.cpp
+ DiceUpdate.cpp
+ dllmain.cpp
+ EncodingConvert.cpp
+ GetRule.cpp
+ GlobalVar.cpp
+ ManagerSystem.cpp
+ MsgFormat.cpp
+ MsgMonitor.cpp
+ RandomGenerator.cpp
+ RD.cpp
+ StorageBase.cpp