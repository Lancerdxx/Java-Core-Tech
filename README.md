# Java-Core-Tech
Java Core Tech

2.2.3. 本地方法区(线程私有)
本地方法区和Java Stack作用类似, 区别是虚拟机栈为执行Java方法服务, 而本地方法栈则为Native方法服务, 如果一个VM实现使用C-linkage模型来支持Native调用, 那么该栈将会是一个C栈，但HotSpot VM直接就把本地方法栈和虚拟机栈合二为一。
