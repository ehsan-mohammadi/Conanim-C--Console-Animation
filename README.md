# conanim - C++ console animation

> C++ Development in Microsoft® Visual Studio

با استفاده از این هدر فایل میتونید از تعدادی انیمیشن طراحی شده در محیط کنسول سی پلاس پلاس استفاده کنید

conanim is an animation header file for C++ console application.

With conanim, you can set animation and use it in your console application project. 

## How to Get Started

### Add header file

It's very simple. Add `conanim.h` and `conanim.cpp` to your Header Files folder. Then include header file by using #include"conanim.h" at the top of your C++ program.

### Set animation

Try your first animation:

```c++
// Create object of Animation class
Animation anim = Animation("(..)\n"
                           "<][>\n"
                           " /\\n");
                           
// Set translate animation to object
anim.translateX(2, 2, 30, 0.1);

```

See the Sample.cpp file for more ideas on how to use conanim in your own projects.

## List of animations

- Translate in X

- Translate in Y

- Wink

- Colorize

- Extend

- Extend To Down

- Appear

- Hide


## License

[MIT © Ehsan Mohammadi.](../master/LICENSE)
