# nerts-rus-34
a ZMK / Linux setup for a writing-focused 34-key nerts / Russian keyboard layout with mouse keys.

In Linux, set compose to pause, switch lang to rctrl.
Instructions on what to do with the 'custom' and 'evdev' files are in those files. Copy the contents of the ZMK keymap file to yours in Github. 

Open this readme raw to view layout illustration with correct spacing, some chars displayed wrong otherwise. If confused, refer to the ZMK codes in the keymap file.

Base layer, mouse keys on the left. ZMK mouse keys require additional setup. If necessary, you can copy the west.yml file from my zmk-config repo.

8   9<  0>  1&  2     3   4   5   6   7!

ml  mu  md  mr  rmb   tab al  ad  au  ar

mmb v-  v+  lmb ,     .   hm  pd  pu  ed
                ctl
                

Hybrid ctrl/fn layer for base layer

f8  f9  f0  f1  f2    f3  f4  f5  f6  f7

[{  wu  wd  ]}  f11   esc cal cad cau car

`~  ct- ct+ \|  f12   mut chm cpd cpu ced
                ctl

p   l   d   g   v     z   k   o   u   -_

n   r   t   s   w     y   h   e   i   a

q   j   m   c   x     b   f   '"  ,?  ./


Hybrid ctrl/fn layer for alpha layer. Here, nerts chars are below Russian. ^ is compose, L switch lang. You probably don't need F9 and ctrl-enter here like I do.

ctp ctl ^   L   ctv   ctz Ъ   cto ctu -
                          =+

ctn ctr ctt cts ctw   cty X   Э   cti cta
                          ;:  ()

ctq F9  ctE  ctc ctx   ctb ctf "   ?   Ё
                               @   !   –—