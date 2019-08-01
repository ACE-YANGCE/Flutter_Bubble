# flutter_bubble_example

Demonstrates how to use the flutter_bubble plugin.

## Getting Started

```
import 'package:flutter_bubble/flutter_bubble.dart';
import 'package:flutter_bubble/bubble_widget.dart';

@override
Widget build(BuildContext context) {
  return MaterialApp(
      home: Scaffold(
          appBar: AppBar(
            title: const Text('Plugin example app'),
          ),
          body: ListView(children: <Widget>[
            Padding(
                padding: EdgeInsets.all(4.0),
                child: Container(
                    alignment: Alignment.centerRight,
                    child: BubbleWidget(
                        255.0,
                        60.0,
                        Colors.green.withOpacity(0.7),
                        BubbleArrowDirection.right,
                        child: Text('你好，我是萌新 BubbleWidget！',
                            style: TextStyle(
                                color: Colors.white, fontSize: 16.0))))),
            Padding(
                padding: EdgeInsets.all(4.0),
                child: Container(
                    alignment: Alignment.centerLeft,
                    child: BubbleWidget(
                        205.0,
                        60.0,
                        Colors.deepOrange.withOpacity(0.7),
                        BubbleArrowDirection.left,
                        child: Text('你好，你有什么特性化？',
                            style: TextStyle(
                                color: Colors.white, fontSize: 16.0))))),
            Padding(
                padding: EdgeInsets.all(4.0),
                child: Container(
                    alignment: Alignment.centerRight,
                    child: BubbleWidget(
                        300.0,
                        90.0,
                        Colors.green.withOpacity(0.7),
                        BubbleArrowDirection.right,
                        child: Text(
                            '我可以自定义：\n尖角方向，尖角高度，尖角角度，\n距圆角位置，圆角大小，边框样式等！',
                            style: TextStyle(
                                color: Colors.white, fontSize: 16.0))))),
            Padding(
                padding: EdgeInsets.all(4.0),
                child: Container(
                    alignment: Alignment.centerLeft,
                    child: BubbleWidget(
                        140.0,
                        60.0,
                        Colors.deepOrange.withOpacity(0.7),
                        BubbleArrowDirection.left,
                        child: Text('你有什么不足？',
                            style: TextStyle(
                                color: Colors.white, fontSize: 16.0))))),
            Padding(
                padding: EdgeInsets.all(4.0),
                child: Container(
                    alignment: Alignment.centerRight,
                    child: BubbleWidget(
                        350.0,
                        60.0,
                        Colors.green.withOpacity(0.7),
                        BubbleArrowDirection.right,
                        child: Text('我现在还不会动态计算高度，只可用作背景！',
                            style: TextStyle(
                                color: Colors.white, fontSize: 16.0))))),
            Padding(
                padding: EdgeInsets.all(4.0),
                child: Container(
                    alignment: Alignment.centerLeft,
                    child: BubbleWidget(
                        105.0,
                        60.0,
                        Colors.deepOrange.withOpacity(0.7),
                        BubbleArrowDirection.left,
                        child: Text('继续加油！',
                            style: TextStyle(
                                color: Colors.white, fontSize: 16.0))))),
            Padding(
                padding: EdgeInsets.all(4.0),
                child: Container(
                    alignment: Alignment.centerRight,
                    child: BubbleWidget(
                        150.0,
                        140.0,
                        Colors.green.withOpacity(0.7),
                        BubbleArrowDirection.right,
                        child: Image.asset('images/icon_hzw.jpg'))))
          ])));
}
```
This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.io/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.io/docs/cookbook)

For help getting started with Flutter, view our 
[online documentation](https://flutter.io/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.
