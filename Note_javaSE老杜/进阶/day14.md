数组是引用数据类型，数组是在堆内存中； 数组一旦定义，长度不可变。数组分一维，二维等等； 数组只能装同一类型的数据；数组的引用（类比对象的引用）是数组第一个元素的地址；

数据优点： 内存是确定的，连续的，每个元素占的空间大小是确定的；通过下标可以立刻定位到所查询的数据，因此检索效率最高

缺点：1.增添或者删减元素的时候 效率低， 因为删掉一歌中间的数据，后面的数据就都要往前移
2. 数组无法存储大数据量，因为很难找连续的大内存空间。 

语法： int[] array = {100,200,300};(静态)   int[] array = new int[5]; 默认值为0

printArray(new int[] {1,2,3}) 只能这样传递

JVM调用main方法的时候会传一个string 给这个方法，但jvm传递的这个string是空的，没有数据；这个jvm的数据来自用户在控制台输入的内容/。

当数组里面放object的时候，虽然类型要一样，但可以放子类

数组扩容：重新建立一个大数组，把小数组里面的数据copy到大数组，效率很低，建议建立数组之前考虑清楚 System.arraycopy(src, srcpos, dest, dest0, src.length);

二维数组： int【】【】array 















