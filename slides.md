title: 104 學年度資訊社迎新
author: 中興資訊社

%%%%%%%%%%%%%%%%%%%
% Use '%' to comment or directive (ex:css below)

%%%%%%%%%%%%%%%%%%%
%% You can add some custom style rules here...

%css



%end

%%%%%%%%%%%%%%%%%%%
%% occupation of scale=1:
%% x = 1200
%% y = 700
%% occupation of scale=2: [occupation of scale=1] * 2
%% x = 2400
%% y = 1400
%% occupation of scale=3: [occupation of scale=1] * 3
%% x = 3600
%% y = 2100
%% occupation of scale=4: [occupation of scale=1] * 4
%% ...
%% the location of one step (slide) is originated from the center!

%%%%%%%%%%%%%%%%%%%
%% Here we go...

%%%%%%%%%%%%%%% 開場白
!SLIDE slide x=-1000 y=-1600

### Aren't you just **bored** with all those slides-based presentations?

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  

> This is a sample of modified impress.js template  

> Go to the [last few slides](#/step-13) to see elements availible.

%%%%%%%%%%%%%%% socket聊天室
!SLIDE slide x=200 y=-1600

### Don't you think that presentations given **in modern browsers**

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  


#### shouldn't **copy the limits** of 'classic' slide decks?

%%%%%%%%%%%%%%% 歡迎廖主任
!SLIDE slide x=1400 y=-1600

## Would you like to **impress your audience** with **stunning visualization** of your talk?

%%%%%%%%%%%%%%% 社課
!SLIDE x=0 y=0 scale=4

## then you should try `impress.js` <sup>*</sup>  

#### <sup>*</sup>no rhyme intended

%%%%%%%%%%%%%%% ACM
!SLIDE x=0 y=2000 rotate=180 scale=4

## It's a **presentation tool**

#### Inspired by the idea behind [prezi.com](http://prezi.com)

#### Based on the `power of CSS3 transforms and transitions` in modern browsers.

%%%%%%%%%%%%%%% 開工計畫
!SLIDE x=8400 y=2000 rotate=270 scale=10

## visualize your **big** thoughts

%%%%%%%%%%%%%%% 樂富
!SLIDE x=3000 y=2000 z=-3000 rotate=300 scale=1

## and **tiny** ideas

%%%%%%%%%%%%%%% 🐱喵
!SLIDE x=14400 y=2000 rotate=270 scale=6

## by **positioning**, **rotating** and **scaling** them on an infinite canvas

%%%%%%%%%%%%%%% 平台介紹
!SLIDE x=6700 y=-2000 scale=6

## the only **limit** is your **imagination**

%%%%%%%%%%%%%%% Ｑ＆Ａ
!SLIDE x=6300 y=-4000 rotate=20 scale=4

## want to know more?

#### [use the source](http://github.com/bartaz/impress.js), Luke!

%%%%%%%%%%%%%%% 報名
!SLIDE x=7000 y=-5000 rotate=40 scale=2

## one more thing...

%%%%%%%%%%%%%%% 自由時間
!SLIDE x=7500 y=-6000 z=-100 rotate=60 rotate-x=90 rotate-y=90 rotate-z=90 scale=2

## have you noticed it's in 3D<sup>*</sup>?  

####<sup>*</sup>beat that, prezi ;)

%%%%%%%%%%%%%%% 以下的之後會刪掉
!SLIDE slide x=10000 y=10000 scale=1

## h2 for the big

#### h4 for sub text of the big

#### h4 for sub text of the big

%%%%%%%%%%%%%%%
!SLIDE slide x=11200 y=10000 scale=1

### h3 for the detailed

Don't use `h1` header  
Because it will become a new slide  
Use `!SLIDE` directive for this template  
More info? see [here](http://slideshow-s9.github.io/more.html)

%%%%%%%%%%%%%%%
!SLIDE slide x=12400 y=10000 scale=1

### Codes

```
var greeting = "Hello world";
console.log(greeting);
this_line_is_too_short_to_fit_in_one_line(the_first_real_long_arg,the_second_real_long_arg);
```

This is inline code: `"Hello world"`

%%%%%%%%%%%%%%%
!SLIDE slide x=12400 y=10700 scale=1

### Lists

 * item 1
 * item 2
    - sub item 1
    - sub item 2

%%%%%%%%%%%%%%%
!SLIDE slide x=12400 y=11400 scale=1

### Indented Text

> Here is some indented text

>> even more indented

>>> even more more indented

%%%%%%%%%%%%%%%
!SLIDE slide x=14200 y=10350 scale=2

### Overflowed picture

If you have `slide` class, the picture will be `max-width:100%` and the slide is scrollable

![Big picture](http://i.imgur.com/S2iMIh8.jpg)

%%%%%%%%%%%%%%% socket聊天室
!SLIDE picture x=14200 y=10350 z=10000 scale=2

### Or `picture` class to use one centered picture

![img in picture slide](http://i.imgur.com/S2iMIh8.jpg)

%%%%%%%%%%%%%%% 宜恩時間
!SLIDE center slide x=16600 y=10350 scale=2

### `center` class to center small picture

![Small picture](http://i.imgur.com/nP2GIt3.png)

Use `center` class to center a picture that is not big enough to fill the slide

%%%%%%%%%%%%%%% 社課
!SLIDE slide x=19000 y=10350 scale=2 rotate=180

### And Links of course

[My Github](https://github.com/chgu82837)  

[This repo](https://github.com/chgu82837/slideshow-impress.js)  

%%%%%%%%%%%%%%% ACM
!SLIDE unclickable showOnlyWhenPresent x=15000 y=12050 scale=5

## That's it!

#### Have fun!

#### this one is `unclickable` and `showOnlyWhenPresent`

#### Useful for overview

%% The End
%%%%%%%%%%%%%%%
