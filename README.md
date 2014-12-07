Gnuplot
=======

My gnuplot notes


```
set palette defined ( 0 0 1 1 , 1 1 1 1 ) color model HSV gamma 1.5
set xrange[0:10]
f(x) = x**2
plot '+' using 1:(f($1)):(f($1)) with lines linecolor palette lw 3 notitle
```
