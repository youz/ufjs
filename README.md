# UserFilter for canvas
A clone of ["UserFilter Plug-in for The Gimp"](http://gimpuserfilter.sourceforge.net/) for canvas

## DEMO
<http://youz.github.com/ufjs/ufdemo.html>


## samples
### filter
- [greyscale](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:put%280.299*r+0.587*src%28x%2Cy%2C1%29+0.114*src%28x%2Cy%2C2%29%2C0%29:get%280%29:get%280%29:255:3)
- [colorize](http://youz.github.com/ufjs/ufdemo.html?#118:0:0:0:0:0:0:0:put%280.299*r+0.587*src%28x%2Cy%2C1%29+0.114*src%28x%2Cy%2C2%29%2C0%29*sin%28ctl%280%29*2%29/800:get%280%29*abs%28sin%28ctl%280%29*2+512/3%29%29/800:get%280%29*abs%28sin%28ctl%280%29*2+1024/3%29%29/800:255:3)

### pattern
- [x ^ y](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:x%5Ey:x%5Ey:x%5Ey:255:5)
- [delicious?](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:x%5Ey:x%5Ey:x%7Cy:255:5)
- [fractal](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:put%28%28x%26y%29%3FC-%28x+y%29/8%3A0%2C0%29:get%280%29:get%280%29:255:5)
- [polar coordinates](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:m%5Ed%2F4:m%5Ed%2F4:m%5Ed%2F4:255:5)

### animation
- [scrolling gradation](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:%28f*5+x*2%29%26255:%28f*8+y*2%29%26255:%28f*3+x+y%29%26255:A:4:1)
- [scrolling checker pattern](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:%28%28x+f*2%3E%3E4%29%5E%28y+f*2%3E%3E4%29%29%261%3F192%3A0:%28%28x+f*3%3E%3E4%29%5E%28y+f*2%3E%3E4%29%29%261%3F255%3A192:255:255:4:1)
- [rotation](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:abs%28sin%28d+f*6%29%29/4:abs%28sin%28d+f*12%29%29/4:abs%28sin%28d+f*18%29%29/4:255:4:1)
- [mosaic?](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:put%28x%5Ey%7C%7Ef%26255%2C0%29:get%280%29:x%7Cy%7C%7Ef%26255:A:4:1)
- [y*y/x](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:%28y*y/x%29+f*9%26127:0:%28y*y/x%29+f*15%26255:255:4:1)

### transition
- [white out](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:c*1.1%2B8:c*1.1%2B8:c*1.1%2B8:255:3:1)
- [horror](http://youz.github.com/ufjs/ufdemo.html?#0:0:0:0:0:0:0:0:r*1.1:g*0.9:b*0.9:255:1:1)

