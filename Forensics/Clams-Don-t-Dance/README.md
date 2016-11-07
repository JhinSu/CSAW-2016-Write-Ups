# Hack the Vote 2016: Warp Speed

**Category:** Forensics
**Points:** 100
**Solves:** 325
**Description:**

Our Trump advertising campaign is incredible, it's skyrocketing! It's astronomical! Wait stop!! SLOW DOWN!!!

author's irc nick: krx

## Write-up

So we are given an image...
image [warp_speed.jpg]

xxd warp_speed.jpg
I. .a. m. .a. . s.q.u.a. r.e... . A.n.y.o. n.e. .w. h.o. .t. e.l.l.s. .y.o.u. .o.t.h. e.r.w.i. s.e. .i. s. .a. . L.I.A.R. !...

So I resized the image 
image [square_warp_speed.jpg]

It looks like the flag is just cut up and scrambled. A bit of paint and voila we have the flag. 
image [flag.jpg]

### Flag

`flag{1337_ph0t0_5k1ll5}`
