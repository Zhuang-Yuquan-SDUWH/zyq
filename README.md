# zyq
zyq
<pre>
元件：
    元件采用STC89C52单片机，DS18B20，温度传感器，数码管等元件
功能：
   该产品用于测量实时的水温，通过DS18B20实时测量温度，并将温度的数值在数码管上显示，测温的范围在-55度到125度。
   可通过按键来设置上限温度和下限温度：通过当前所显示的温度，选择合适的温度范围，通过key1来设置上下限的增加，H代表着上限，L代表着下限；key2来设置上下限的减小，HL同样代表；key3用来切换正常温度，上限与下限的显示，分别用flag0,flag1,flag2 来表示。
   设置好后，一旦温度高于上限或低于下限就会蜂鸣器响起，小灯led1与led2会分别闪烁。再次调整上下限就会停止。
</pre>

