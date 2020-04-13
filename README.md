# LJScrollText
LJScrollText滚动文字,支持属性有：

- 滚动速度
- 文字相关属性

使用方法：

pod 'LJScrollText';



`#import "ScrollTextView.h"`

 `ScrollTextView *textView = [[ScrollTextView alloc]initWithFrame:CGRectMake(30, 100, 200, 60)];`

  `textView.font = [UIFont systemFontOfSize:20];`

  `textView.textColor = [UIColor blackColor];`

  `textView.text = @"这是抖音滚动字符串wqdqwd大青蛙多群无多群无多群无多群无多群无多群无多群无多群无";`

  `textView.fade = 0.5;`
  
  `textView.speed = 0.32;`

  `[**self**.view addSubview:textView];`
