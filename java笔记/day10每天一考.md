1.构造器的作用是什么？使用中有哪些注意点（>=3条）

​	①创建对象②初始化对象结构

2.关于类的属性的赋值，有几种赋值的方法。谈谈赋值的先后顺序

默认初始化-显式初始化-构造器中初始化-对象。方法或结构。属性给属性赋值

3。this关键字可以用哪些结构，简单说明一下其使用

this：属性、方法、构造器

this：理解为当前对象，当前正在创建的对象

4。java中目前学习涉及到的四种权限修饰符都有什么？并说明各自的权限范围

private int age；

private void eat（）{}

5。创建Circle类，提供私有的radius属性，提供相应的get和set方法，提供求圆面积的方法。

private double radius；

public void 	steRadius(double radius){

​	this.radius = radius;

}

public double getRadius (){

return radius;

}

public 	doule findArea(){

​	retuan 3.14 *  redius * redius;

}