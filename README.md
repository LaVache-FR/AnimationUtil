# AnimationUtil
Simple AnimationUtil using Easing functions. Can be used anywhere, Hacked-Client, Mods, etc..


Render example >
https://gyazo.com/780b5d84f7bc69f863acdcc7022591fe


Exemple of how to use it.

```java

//Variable Initialization
Animate anim = new Animate();

//Set Easing Method
anim.setEase(Easing.CUBIC_OUT);

//Set min Value
anim.setMin(20);

//Set max Value
anim.setMax(440);

//Set Animation Duration
anim.setSpeed(200);

//Set Reversed Animation
anim.setReversed(false);

//Update Animation
anim.update();

//Draw Rectangle, X, Y, WIDTH, HEIGHT, COLOR.
drawRect(anim.getValue(), 10, 20, 20, 0xFFFFFFFF);
```
