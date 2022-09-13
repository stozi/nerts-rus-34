# nerts-rus-34
a ZMK / Linux setup for a writing-focused 34-key nerts / Russian keyboard layout with mouse keys. Punctuation is heavily optimized for writing.

In Linux, set compose to pause, switch lang to rctrl.
Instructions on what to do with the 'custom' and 'evdev' files are in those files. Copy the contents of my ZMK keymap file, found here: https://github.com/stozi/zmk-config/blob/master/config/a_dux.keymap to yours in Github. ZMK mouse keys require additional setup. If ZMK mouse keys are still in beta and you haven't got it working yet, you can copy the contents of my west.yml file: https://github.com/stozi/zmk-config/blob/master/config/west.yml.


Prefix 'ct' or 'c' means ctrl+...

Illustration:

Base layer, mouse keys on the left.

```
8   9<  0>  1&  2     3   4   5   6   7!

ml  mu  md  mr  rmb   tab al  ad  au  ar

mmb v-  v+  lmb ,     .   hm  pd  pu  ed
                ctl

layer2 layer1/enter  shift/space alt/bkspc   
```               

Hybrid ctrl/fn layer for base layer

```
f8  f9  f0  f1  f2    f3  f4  f5  f6  f7

[{  whu whd ]}  f11   esc cal cad cau car

`~  ct- ct+ \|  f12   mut chm cpd cpu ced
                ctl

nul layer0/enter  shift/space alt/del   
```

```
p   l   d   g   v     z   k   o   u   -_

n   r   t   s   w     y   h   e   i   a

q   j   m   c   x     b   f   '"  ,?  ./

layer0 layer3/enter  shift/space alt/bkspc   
```

Hybrid ctrl/fn layer for alpha layer. Here, nerts chars are below Russian. ^ is compose, L switch lang. You probably don't need F9 and ctrl-enter here like I do.

```
ctp ctl ^   L   ctv   ctz Ъ   cto ctu -
                          =+

ctn ctr ctt cts ctw   cty X   Э   cti cta
                          ;:  ()

ctq F9  ctE ctc ctx   ctb ctf "   ?   Ё
                              @   !   –—

null layer3/enter  shift/space alt/del   
```
