# react-native-city-pick
#### 1、里面有两种城市的选择模式，一个是picker模式，一个是列表模式；
#### 2、其中picker模式采用的是react-native-picker，里面只有两层的目录结构，如果需要三层的用作者的那个就可以了
#### 3、列表模式是我们最常用的，再次采用的方法是计算出城市列表的高度，点击右侧的index字母索引就可以对应到相应的字母对应的城市列表，各位请看下图
#### 4、如果要运行我的代码，需要先下载下来 git clone https://github.com/LiuC520/react-native-city-pick/
#### 5、然后 npm i
#### 6、然后react-native run-android 或者 react-native run-ios
![](https://github.com/LiuC520/react-native-city-pick/blob/master/src/screenshorts/%E6%9C%AA%E6%A0%87%E9%A2%98-2.png)
#### 如果iOS运行出错，libRCTBEEPickerManager.a找不到,可以移除以后，在BuildPhases中重新引入libRCTBEEPickerManager.a
#### 如果报错#import <React/RCTEventDispatcher.h>找不到，可以替换引入方法#import "RCTEventDispatcher.h"
