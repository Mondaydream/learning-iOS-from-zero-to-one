# learning-iOS-from-zero-to-one
一直认为学习一门新的东西从动手开始，自行搜索解决问题应该是技术领域基本原则。这个项目是一个面对0基础的人的一个上手教程，从动手开始。整个教程力争能够达到基础的入门，深入则看自己所做的项目遇到的问题。时间周期：一个月。

## 1.Hello world

### 1.1在Xcode的控制台中打印Hello world
如图：![](https://raw.githubusercontent.com/Mondaydream/learning-iOS-from-zero-to-one/master/截图/Screen%20Shot%202018-01-08%20at%2011.44.59%20AM.png)

目的为了解：Xcode中控制台的作用及基本运行一个项目的基础操作，以及OC中 NSLog 打印函数的使用。

## 2.初步理解Objective-C这门语言
### 2.1理解OC中Class的概念
入门不需要先去理解一些元类或者类的底层概念，只需要知道类是这门面向对象编程语言的基础，一个类就类似大自然届中的一个物种的名字，比如鱼类，可以有很多种不同的鱼，而鱼类这个类代表的鱼的一些特征。
### 2.2在Xcode中建立起一个新的继承与NSObject的类名为Person的类
这一步只需明白OC中所有的类都继承于NSObject。

### 2.3理解Person类的.h与.m文件各自的作用与区别
interface是接口，implementation是实现。

### 2.4了解OC的基本语法

#### 2.4.1理解类的函数的概念
OC中类有两种函数，一种为类函数，即不用生成类的实例就可以调用的函数，另外一种函数为实例函数，实例函数只有类的实例可以调用，注意类的实例无法调用类函数。两者之间的区别为 类函数 以符号 + 开头，实例函数以符号 - 开头。函数是存在返回值的。

#### 2.4.2给Person类添加一个无返回值的 todo 类函数
函数的实现为打印一个字符串 ‘todo class method’
#### 2.4.3给Person类添加一个无返回值的 todo 实例函数
函数的实现为打印一个字符串 ‘todo instance method’
#### 2.4.4在Xcode的模版中引入Person类并在调用todo 类函数
理解#import概念
#### 2.4.5创建出Person的实例并调用 todo 实例函数。
建立起类生成实例的概念



