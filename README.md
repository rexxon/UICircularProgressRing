# UICircularProgressRing

This is simply clone from [https://github.com/luispadron/UICircularProgressRing](https://github.com/luispadron/UICircularProgressRing), just add 2 features

Added Fatures

* client can toggle is show custom label
* client can setup custom label font and color
* client can setup the background color in middle circle 

Result 

![image](https://github.com/rexxon/UICircularProgressRing/blob/master/%E6%88%AA%E5%9C%96%202020-02-03%20%E4%B8%8B%E5%8D%886.11.03.png)

Usage:

First , enable show custom label flag
```
progressRing.shouldShowCustomText = true
```
Setup custom label text
```
progressRing.customLabelString = "Score"
```

Setup custom label font
```
progressRing.customLabelfont = UIFont.systemFont(ofSize: 12.0)
```

Setup custom label color
```
progressRing.customLabelfontColor = UIColor.black
```

Setup middle circle background color
```
progressRing.circleBackgroundColor = UIColor.white
```