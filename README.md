# AnimationUtil
Simple AnimationUtil using Easing functions. Can be used anywhere, Hacked-Client, Mods, etc..


Render example >
[https://gyazo.com/780b5d84f7bc69f863acdcc7022591fe](https://i.gyazo.com/780b5d84f7bc69f863acdcc7022591fe.mp4)


Exemple of how to use it.

```java

//Variable Initialization
Animate anim = new Animate();

//Set Easing Method
anim.setEase(Easing.CUBIC_OUT);

//Set min Value
anim.setMin(10);

//Set max Value
anim.setMax(500);

//Set Animation Duration
anim.setSpeed(200);

//Set Reversed Animation
anim.setReversed(false);

//Update Animation
anim.update();

//Draw Rectangle, X, Y, WIDTH, HEIGHT, COLOR.
drawRect(anim.getValue(), 10, 20, 20, 0xFFFFFFFF);

//Reset Animation
if(Mouse.isButtonDown(0))
   anim.reset();
```

OR

```java
//Variable Initialization
Animate anim = new Animate();

//Set Easing Method
anim.setEase(Easing.CUBIC_OUT).setMin(10).setMax(500).setSpeed(200).setReversed(false).update();

//Draw Rectangle, X, Y, WIDTH, HEIGHT, COLOR.
drawRect(anim.getValue(), 10, 20, 20, 0xFFFFFFFF);

//Reset Animation
if(Mouse.isButtonDown(0))
   anim.reset();
```
