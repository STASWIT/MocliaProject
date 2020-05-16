## RandomGenerator.cpp功能解析日志

### 引用的标准库

> random  
> chrono  
> intrin.h  
> (else)x86intrin.h  

### 引用的第三方库

> RandomGenerator.h   
> 重要：本cpp必须和同名.h文件一同使用，否则会报错LNK2019。 

### 命名空间
~~~CPP
using namespace std;
~~~

### 代码功能分析
#### 流程结构

---
+ 定义命名空间——RandomGenerator
+ 定义一个无符号类型的长整型变量GetCycleCount()
+ + 该变量使用__rdtsc()函数返回CPU指令周期数，用以作为随机数种子。
+ 定义一个整型函数Randint，同时定义两个整型参数lowest（最小值），highest（最大值）。
+ + 该函数利用mt19937随机数函数生成随机数。

---
