# 学 iOS 开发写的笔记和代码
#### 环境 
硬件:  Mac mini  
系统:  OS X EI Caption (10.11)  
Xcode 版本:  7.0.1  


### 学习来源

https://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/   
http://blog.csdn.net/hherima/article/details/8620941    
http://ios-blog.co.uk/tutorials/beginners-ios-development-objective-c/   


__Learn Objective-C__  
http://cocoadevcentral.com/d/learn_objectivec/    


__About Objective-C__  
https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html  

__马上着手开发 iOS 应用程序 (Start Developing iOS Apps Today)__  
https://developer.apple.com/library/ios/referencelibrary/GettingStarted/RoadMapiOSCh/DesigningaUserInterface.html#//apple_ref/doc/uid/TP40012668-CH6-SW1  


__Google Objective-C Style Guide 中文版__  
http://zh-google-styleguide.readthedocs.org/en/latest/google-objc-styleguide/   

__[ISUX转译]iOS7人机界面指南__  
http://isux.tencent.com/ios-human-interface-guidelines-ui-design-basics-ios7.html  


__iOS开发60分钟入门__  
https://github.com/qinjx/30min_guides/blob/master/ios.md  




<br/>
### 要学的东西
1. APP ICON + 名字
2. 发请求
3. 复杂的视觉效果
2. 打包上传Apple Store
5. 怎么适配不同版本？ iPhone 5, 5s



<br/>
<br/>
### 小备注
UIKit 是 iOS 开发的核心框架  必学  


<br/>
<br/>
## 学习资料
1. (OC) 传智播客的 iOS 视频
2. (Swift) Youtube -  channel: thenewboston - __iOS Development with Swift__



---



<br/>
<br/>
## 第 1 个 OC 程序

#### 1. 新建一个 1.m 文件

内容如下
```Objective-C

#import <Foundation/NSObjCRuntime.h>
// NSObjCRuntime have the NSLog..

int main()
{

    NSLog(@"hello");
    return 0;


}
```

#### 2. 运行

```Objective-C
cc -c 1.m
// 编译出 o

cc 1.o -framwork Foundation
// 编译出 out 文件

./a.out
// 运行
```





<br/>
<br/>
## 第 2 个 OC 程序
```Objective-C
#import <Foundation.h>

int main()
{

NSLog(@"hello");
return 0;

}
```














