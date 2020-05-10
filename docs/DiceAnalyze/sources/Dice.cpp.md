## Dice.cpp功能解析日志

### 引用的标准库

> windows.h  
> string  
> iostream  
> map  
> set  
> fstream  
> algorithm  
> ctime  
> mutex  

### 引用的第三方库

> APPINFO.h  
> DiceFile.hpp  
> Jsonio.h  
> RandomGenerator.h  
> RD.h
> ManagerSystem.h  
> DiceMod.h  
> DiceMsgSend.h  
> MsgFormat.h  
> DiceCloud.h  
> CardDesk.h  
> DiceConsole.h
> EncodingConvert.h
> CharacterCard.h  
> DiceEvent.h  
> DiceSession.h  

> CQEVE_ALL.h  

### 命名空间
~~~CPP
using namespace std;
using namespace CQ;
~~~

### 代码功能分析
#### 流程结构

---
* 加载数据  
1. 如果找不到DiceData，就在酷Q根目录创建DiceData文件夹。（调用DiceFile.hpp）
2. 
3.

---

