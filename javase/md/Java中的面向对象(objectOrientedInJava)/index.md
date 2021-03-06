## **面向对象**

### 	一、三大特征

#### 		1.封装

​		封装就是隐藏对象的属性和实现细节，仅对外公开接口，控制在程序中属性的读和修改的访问级别，将抽象得到的数据和行为（或功能）相结合，形成一个有机的整体，也就是将数据与操作数据的源代码进行有机的结合，形成“类”，其中数据和函数都是类的成员。

​		封装的目标是增强安全性和简化编程，使用者不必了解具体的实现细节，而只是要通过外部接口，以特定的访问权限来使用类的成员。

​		与面向过程不同，面向过程关心处理的逻辑、流程等问题，而不关心事件主体，而面向对象在处理工作时，是围绕对象来进行的。

#### 		2.继承

​		继承是面向对象的基本特征之一，继承机制允许创建分等级层次的类。继承就是子类继承父类的特征和行为，使得子类对象（实例）具有父类的实例域和方法，或子类从父类继承方法，使得子类具有父类相同的行为。

​		在Java中的Object类是所有类的超类，常称作上帝类。

#### 		3.多态

​		多态同一个行为具有多个不同表现形式或形态的能力。是指一个类实例（对象）的相同方法在不同情形有不同表现形式。多态机制使具有不同内部结构的对象可以共享相同的外部接口。这意味着，虽然针对不同对象的具体操作不同，但通过一个公共的类，它们（那些操作）可以通过相同的方式予以调用。多态的直观体现是方法的重写和重载。

​		

### 	二、五大原则

#### 		1.单一职责原则

​		一个类型的职责范围应该尽可能的清晰，其所涵盖的工作范围或者说职责范围应该精确且单一。每一个类应该专注于做一件事。如果一个类有多个职责，这些职责就耦合在一起了。当一个职责发生变化，可能会影响其他职责。多职责耦合在一起，会影响复用性。

#### 		2.开放封闭原则

​		面向对象的设计应该更多地去考虑后期扩展，尽量避免对原始设计的修改。

#### 		3.里氏替换原则

​		父类中可行的调用，在子类中也应当可行。

#### 		4.依赖倒置原则

​		类的实现应当依赖于具体地抽象规则，而不是让抽象规则围绕类的实现来变更。

#### 		5.接口隔离原则

​		接口在设计上应当尽可能功能独立，即同层级之间不应该存在依赖关系。

