# 0，oop-python面向对象
- python的面向对象
- 面向对象变成
    - 基础
    - 共有私有
    - 继承
    - 组合，Minxi
- 魔法函数
    - 魔法函数概述
    - 构造类魔法函数
    - 运算类魔法函数
    
# 1 面向对象概述（object0riented，00）
- oop思想
    - 接触到任意一个任务，首先想到的是任务是这个世界构成，是由模型构成的
- 几个名词
    - 00：面向对象
    - 00A：面向对象的分析
    - 00D：面向对象的设计
    - 00I：xxx的实现
    - 00P：xxx的编程
    - 00A：->00D->00I:面向对象的实现过程
- 类和对象的概念
    - 类：抽象名词，代表一个集合，共性的事务
    - 对象：具象的事务，单个个体
    - 类跟对象的关系
        - 一个具象，代表一类事务的某一个个体
        - 一个抽象，代表的是一大类事物
- 类中的内容，应该具有2个内容
    - 表明事物的特征，叫做属性（变量）
    - 表明事物功能或动作，称为成员方法（函数）
    
# 2，类的基本实现
- 类的命名
    - 遵守变量命名规范
    - 大驼峰
    - 尽量避开跟系统命名相同的命名
- 如何声明一个类
    - 必须用class关键字
    - 类由属性和方法构成，其他不允许出现
    - 成员属性定义可以直接使用变量赋值，如果没有值，使用None
    - 案例 01.py
- 实例化类
        变量 = 类名（） #实例化了一个对象
- 访问对象成员
    - 使用点操作符
                obj.成员属性
                obj.成员方法 
- 可以通过默认内置变量检查类和对象的所有成员
    - 对象所有成员检查
            # dict前后各有2个下划线
            obj.__dict__
    - 类所有的成员
            # dict前后各有2个下划线
            class_name.__dict__
            

# 3,anaconda基本使用
- anaconda主要是一个虚拟环境管理器
- 还是一个安装包管理器
- conda list：显示anaconda安装的包
- conda create -n xxx python=3.6:创建版本为3.6的虚拟环境，名称xxx
- win
    1，打开Anaconda Prompt输入
    conda create -n xxx python=3.7
    2，激活虚拟环境
    activate tensorflow
    3，安装名为tensorflow的软件
    pip install tensorflow 或者 pip install –ignore-installed –upgrade tensorflow
