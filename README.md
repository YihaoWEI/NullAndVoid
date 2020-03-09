# NullAndVoid
Log the bugs, thoughts and techniques.
针对大部分功能都是C++11及以上的，多数都是工程实践中发现的问题

##### 模板类也可以用模板函数  
使用目标类的函数，本身内部同样可以对某一函数使用不同的模板，但主要要在实例化的时候指明这些类型。  
