# Learn-iOS
学 iOS 开发写的笔记



UIKit 是 iOS 开发的核心框架  必学


## 第一个 OC 程序

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