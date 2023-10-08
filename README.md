# nerts-rus-34
a ZMK / Linux setup for a writing-focused 34-key nerts / Russian keyboard layout with mouse keys. Punctuation is heavily optimized for writing.

In Linux, set compose to pause, switch lang to rctrl.
Instructions on what to do with the 'custom' and 'evdev' files are in those files. Copy the contents of my ZMK keymap file to yours in Github, that's a key step. ZMK mouse keys require additional setup. If ZMK mouse keys are still in beta and you haven't got it working yet, you can copy the contents of my west.yml file: https://github.com/stozi/zmk-config/blob/master/config/west.yml.


Prefixes 'ct' or 'c' mean ctrl+ below.

Illustration:

Base layer, mouse keys on the left. Switching bang and ampersand makes the former more accessible on the last layer. 

```
9<  0>  1&  2   3     4   5   6   7!  8

ml  mu  md  mr  v+    tab al  ad  au  ar

v-  rmb mmb lmb .     ,   hm  pd  pu  ed

layer2 layer1/enter  shift/space alt/bkspc   
```               

Hybrid ctrl/fn layer for base layer (skC is sticky ctrl, which is only there for very rare ocassions, ctE is ctrl-enter)

```
f9  f10 f1  f2  f3    f4  f5  f6  f7  f8

skC whu whd ctE mut   esc cal cad cau car

[{  ]}  `~  \|  f11   f12 chm cpd cpu ced

null layer0/enter  shift/space alt/del   
```

```
p   l   d   g   v     z   k   o   u   -_

n   r   t   s   w     y   h   e   i   a

q   j   m   c   x     b   f   '"  ,/  .?

layer0 layer3/enter  shift/space alt/bkspc   
```

Hybrid ctrl/fn layer for alpha layer. The positions of puncts/Ru alphas (and some handy puncts for Ru) are influenced by comfort and which letters are seldom used with ctrl. ^ is compose, L switch lang.

```
ctp ctl ^   L   ctv   ctz =+  cto ctu –—
                          Ъ           -_

ctn ctr ctt cts ctw   cty ;:  ()  cti cta
                          X   Э

ctq ct- ct+ ctc ctx   ctb ctf the @   !
                                  Ё   ?

null layer2/enter  shift/space alt/del   
```
