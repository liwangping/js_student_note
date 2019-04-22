## js有哪些假值？为什么？
七个假值，
undefined, null, NAN, -0, +0, "", false.
这个是属于记忆的东西。
之所以这样可以实验这样子。
Number(true)  //1
Number(false)   //0
[] === false    //因为[]转换后为"",""为内置的假值。