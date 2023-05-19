### 语法

#### 基础语法

整体语法类似c语言

基础类型：int ,long long,float,double,

复合类型：message；主要需要提供[]访问赋值支撑

任意类型:   object

~~~go
message m1;
m1["key1"]["key2"][1]=1;
~~~

#### 包语法

xml/json/array/hashmap/string/byte/pair java库以包形式提供

访问方式使用面向对象的方式

#### 函数语法

除了基础类型，全为引用类型，需要显式clone进行深拷贝，多返回值使用 `ArrayList<Object>`