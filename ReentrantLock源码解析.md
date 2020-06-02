### ReentrantLock类文件结构

ReentrantLock实现了Lock接口，并且聚合Sync抽象类的对像作为属性

`Sync`类继承了`AbstractQueuedSynchronizer`类，而如果是非公平锁的话由`NonfairSync`集成Sync类，并重写

