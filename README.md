# XTVerCodeSingeA
一个可以验证码的输入框, 单个单个字符显示!

Usage
```objectivec
    XTVerCodeInput *verView = [[XTVerCodeInput alloc] initWithFrame:CGRectMake(0, 190, self.view.frame.size.width, 82)];
    /// 4 / 6
    verView.inputType = 4;
    [verView initSubviews];
    verView4.verCodeBlock = ^(NSString *text){
        NSLog(@"您输入的验证码是%@",text);
    };
    [self.view addSubview:verView];
```

Example

[](https://i.loli.net/2018/02/07/5a7aab4e188a6.gif)