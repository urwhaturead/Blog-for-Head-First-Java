Tuesday, December 7, 2021
12:47 AM

p29
面向对象让他最喜欢的其中一点就是  
有时不需动到已经测试好的程序就可以达到新目标。  
面向对象的适应性与可扩展性让他面对修改时不会觉得太过于痛苦  
  
    
    
P31
用方法代替过程 用类代替物体  
  
    
    

什么叫面向对象的继承 inheritance:  
1. 找出4个类中共同的部分  
2. 他们都是shape，而且都有rotate和playSound，因此可以提取出新的类  
3. 将4个形状体以继承的关系连接到shape这个类  
次级类会继承上级类的方法。也就是说，子类会自动获得父类的功能。  
4. 子类的方法会覆盖上级类的方法  
	覆盖的意思是 由子类重新定义继承下来的方法，以改变或延伸此方法的行为。  
  
    
    
P33  
• 他帮助我用更自然的方法设计  
• 加入新功能时不会搞乱已经写好的程序代码  
• 将数据与操作数据的方法摆在同一个类内  
• 写一个类的时候，可以使该类有足够的扩展性，以便以后用到  
   
     
P34  
对象已知的事物  
	实例变量 instance variable （状态）  
对象会执行的动作  
	方法 methods （行为）  
  
    
该类型的每一个对象都会独立的拥有一份该类型的值  
所以你也可以把对象当作为实例。  
对象可以执行的动作称为方法。  
在设计类时，你也会设计出操作对象数据的方法。  
对象带有读取或操作实例变量的方法是很常见的情形。  
举例来说，闹钟对象会有个变量来保存响铃时间，  
且会有getTime()和setTime()这两个方法来存取该时间。  
因此说对象带有实例变量和方法  
但它们都是类设计中的一部分。  
  
    
P35  
类和对象有什么不同  
	类不是对象，却是用来创建他们的模型  
	
	  
	    
P36  
创建你的第一个对象 object  
你需要两个类。  
一个是要被操作于对象的类，  
另一个是用来测试该类的类。  
测试用的类 带有main（）  
你会在其中建立与存取被测的对象  
后续章节会有许多双类的范例  
测试用的类 会被命名为“受测类名称”+testDrive  
  
    
      
圆点运算符(.)  
这个运算符能让你存取对象的状态与行为。  
  
    
      
步骤：  
1.编写类  
2.编写测试用的类  
3.在测试用的类中：建立对象，并存取对象的变量和方法  

第四章会讨论封装的问题。  

P38  
Main()的两种用途  
	• 测试真正的类  
	• 启动你的Java应用程序  

P38-39  
产生随机数  
3个player猜测该数字  

用三个实例变量分别表示三个玩家对象  
创建出player对象  
声明三个变量来保存猜测的数字  
声明三个变量来保存是否猜中  
产生谜底数字  
调用player的guess方法  
取得每个player所猜测的数字并将他列出  
检查是否猜中，若是猜中则去设定是否猜中的变量  
如果有一或多个猜中 游戏结束  
不然的话就重复循环继续猜下去  
  
用vs studio试一下 太麻烦了 先不要动好了 先看书  
  
    
      
P41  
java程序是由一组类所组成    
其中有一个类会带有启动用的main()方法  
因此程序员必须要编写一或多个类并以此提交  
  
  
任何Java中的事物都必须待在类中。  
因此，random()方法也必须定义在math这个类中。  
而且你必须记住这种近似全局的事物在Java中算是例外。他们是非常特殊的情况，不会有多个实例或对象。  

  
    
要点：  
面向对象设计扩展功能不需改动之前已经测试好的程序代码。  
所有的java程序都定义在类中  
类 如同蓝图 描述该类型的对象 要如何创建。  
  
    
对象自治：你无需在意他如何完成任务。   
对象有已知的事物，并能执行工作。  
对象本身已经知道的事物称为实例变量，  
他代表对象的状态。  
对象可执行的动作称为方法，  
他代表对象的行为。  
创建类时，可能同时会需要创建独立、测试用的类。  
类可以继承自 较为抽象的父类。  
java的程序 在执行期 是一组会互相交谈的对象。  



