# BookTradeDemo
![icon](/screenshots/ic_launcher.png) 

### 代码块
``` python
@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print 'Greater'
    return (param2 - param1 + 1) or None
class SomeClass:
    pass
>>> message = '''interpreter
... prompt'''
```
$$	x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

### 流程图
```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```

以及时序图:

```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```
> NOTE: This project is deprecated.The brand-new version is still in
> development mode.

- An Android app for BUPT students to post information of their used books.

- It's still a demo now.



## Screenshots ##
![icon](/screenshots/1.png) ![icon](/screenshots/2.png) 

![icon](/screenshots/3.png) ![icon](/screenshots/4.png)
![icon](/screenshots/5.png) ![icon](/screenshots/6.png)  




## Demo ##
[Download apk](/release/app-debug.apk)



## Use ##



1. Apply for an `Application ID` in [Bmob](http://www.bmob.cn/)
2. In `com.bupt.booktrade.utils.Constant`, replace the field `BMOB_APP_ID` with your `Application ID`



## Thanks ##



- [Glide](https://github.com/bumptech/glide)
- [SmoothProgressBar](https://github.com/castorflex/SmoothProgressBar)
- [Float Labeled EditText](https://github.com/wrapp/floatlabelededittext)
- [ZrcListView](https://github.com/zarics/ZrcListView)
- [Wonderful2](https://github.com/bmob/Wonderful2)



## License ##
> Copyright (C) 2015 Liu Yan



> This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.



> This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details


> You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.