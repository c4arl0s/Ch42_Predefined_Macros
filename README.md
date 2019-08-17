# Ch42_Predefined_Macros
Ch42_Predefined_Macros

``` objective-c
//
//  ViewController.m
//  Predefined_Macros
//
//  Created by Carlos Santiago Cruz on 8/17/19.
//  Copyright © 2019 Carlos Santiago Cruz. All rights reserved.
//

#import "ViewController.h"

@interface ViewController ()

@end

@implementation ViewController

- (void)viewDidLoad {
    [super viewDidLoad];
    
    NSLog(@"File :%s\n", __FILE__ );
    NSLog(@"Date :%s\n", __DATE__ );
    NSLog(@"Time :%s\n", __TIME__ );
    NSLog(@"Line :%d\n", __LINE__ );
    NSLog(@"ANSI :%d\n", __STDC__ );

}

@end
```

``` console
2019-08-17 09:13:41.326254-0500 Predefined_Macros[16895:1750605] File :/Users/carlossantiagocruz/Documents/SWIFT-PROGRAMMING/Ch42_Predefined_Macros/Predefined_Macros/Predefined_Macros/ViewController.m
2019-08-17 09:13:41.326645-0500 Predefined_Macros[16895:1750605] Date :Aug 17 2019
2019-08-17 09:13:41.327450-0500 Predefined_Macros[16895:1750605] Time :09:13:35
2019-08-17 09:13:41.328301-0500 Predefined_Macros[16895:1750605] Line :23
2019-08-17 09:13:41.335200-0500 Predefined_Macros[16895:1750605] ANSI :1

```
