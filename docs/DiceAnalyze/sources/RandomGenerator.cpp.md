## RandomGenerator.cpp功能解析日志

### 引用的标准库

> random  
> chrono —— 与时间有关的头文件  
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
+ + 该函数利用mt19937随机数函数生成随机数。同时传入最大最小值的参数以限定范围。最后返回在最大值和最小值范围内的均匀分布的随机数。
> uniform_int_distribution
  (C++11)&#8195;
 产生在一个范围上均匀分布的整数值(类模板)

---

### 参考资料

[伪随机数生成](https://zh.cppreference.com/w/cpp/numeric/random)  
[C++ STL mt19937 使用说明](https://www.jianshu.com/p/6d9a7de995bb)  