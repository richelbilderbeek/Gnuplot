Gnuplot
=======

My gnuplot notes


Fill everything above y = 0:

```
plot -cos(x)/(1+0.1*x**2) w filledc above y1=0
```

Color the line:

```
set palette defined ( 0 0 1 1 , 1 1 1 1 ) color model HSV gamma 1.5
set xrange[0:10]
f(x) = x**2
plot '+' using 1:(f($1)):(f($1)) with lines linecolor palette lw 3 notitle
```
