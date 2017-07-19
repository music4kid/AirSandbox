### What is it?
A simple class, enable you to view sandbox file system on iOS device, share files via airdrop, super convenient when you want to send log files from iOS device to Mac.

### How to use?
After your key window is created, add below code:
```
#ifdef DEBUG
    [[PAirSandbox sharedInstance] enableSwipe];
#endif
```
now swipe from the right edge of the screen, a simple file browser shall pop up.

<img src="http://mrpeak.cn/images/airsandbox.jpg" width="375">

no more instructions needed.

### Licence
MIT


