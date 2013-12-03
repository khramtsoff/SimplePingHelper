Simple Ping Helper
==================

（Fork自：[SimplePingHelper](https://github.com/chrishulbert/SimplePingHelper)）

###更新了SimplePing 的源码：[SimplePing](https://developer.apple.com/library/mac/samplecode/SimplePing/Listings/SimplePing_m.html#//apple_ref/doc/uid/DTS10000716-SimplePing_m-DontLinkElementID_5)

###增加了ARC

###增加了通过回调来处理事件：
      [SimplePingHelper ping:@"www.baidu.com"
                    callback:^(NSNumber *b){
                  if(b.boolValue)
                  {
                    NSLog(@"%@", @"success");
                    [self log:@"success"];
                  
                  }
                  else
                  {
                    NSLog(@"%@", @"failure");
                    [self log:@"failure"];
                  }
      }];