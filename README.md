# AgentObjSize
## *说明*    
这是一个 可以查看java对象大小的Agent 
## *使用方法* 
 - 1 打成jar包
 - 2 导入jar包
 - 3 idea 在运行参数加入 Eg.( `-javaagent:F:\AgentObjSize.jar`)
 - 4 运行程序（结果是bit）   
## 使用例子
        System.out.println(ObjectSizeof.sizeOf(new Integer(1)));  
        System.out.println(ObjectSizeof.sizeOf(new String("a")));  
        System.out.println(ObjectSizeof.sizeOf(new char[1]));  
        System.out.println(ObjectSizeof.fullSizeOf(list));   
## 结果 
        16  
        24   
        24   
        164862008   
