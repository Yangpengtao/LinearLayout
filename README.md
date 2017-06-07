# LinearLayout
LinearLayout简单的源码解析，欢迎纠错。<br/>

 
view的绘制过程无非是onmeasure(),onLayout(),onDraw()。三个过程。<br/>
1，通过weight， gravity，测量模式 测量view和子view的大小。 <br/>
2，通过 gravity确定子view的位置 <br/>
3，通过 在onDraw绘制divider<br/>
