## 1、C++中的拷贝构造函数与赋值运算符的区别

**区别在于：**</br>
        1）、拷贝构造函数使用传入对象的值生成一个新的对象的实例，而赋值运算符是将对象的值复制给一个已经存在的实例。</br>
        2）、这种区别从两者的名字也可以很轻易的分辨出来，拷贝构造函数也是一种构造函数，那么它的功能就是创建一个新的对象实例；赋值运算符是执行某种运算，将一个对象的值复制给另一个对象（已经存在的）。</br>
       所以，调用的是拷贝构造函数还是赋值运算符，**主要是看是否有新的对象实例产生**。如果产生了新的对象实例，那调用的就是拷贝构造函数；如果没有，那就是对已有的对象赋值，调用的是赋值运算符。
