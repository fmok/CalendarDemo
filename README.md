# CalendarDemo
包含两部分: 1.轮播图形式的日历界面 2.计算万年历数据的工具类 

 主要优势:
 
 1.接口简单, 参数只有一个, 返回值利用也特别简单, 直接拆除对象使用即可 < 详细的对象拆解下方注释 >
 
 2.因为是工具类, 所以只涉及数据层面, 可以单独使用, 与界面无耦合度
 
 3.采用缓存机制, 在计算日历数据时可以避免多次运算, 提高运算效率
 
 4.采用自定义对象 < CalenderObject > 作为数据存储器, 可以对内容进行自定义扩展, 以满足业务需求
 
 5.对时间计算方式做了优化, 可以左右无限滑动, 且计算效率高
 
 6.Demo 中的日历界面为轮播图形式, 不会占用大量内存
 
 7.如果不需要显示本月日历中上月的数据, 根据对应的标识符进行处理即可
 
 8.后续会根据 EventKit 框架, 进行日历工具与提醒事件的联结开发 
