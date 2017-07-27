---
layout: post
title: Arcade Table
description: Arcade Table built from Ikea table and Raspberry Pi 3
image: dk-table.png
---

I want to share some of the **Tips and Mistakes** I ran into while building this arcade table.

## Parts ##
So here are the main parts, the rest can be found on the post I refererenced in building this

- **[PIK3A Gaming Table][element-14]:** original post describing how to build the arcade table
- **Table:** IKEA Lack coffee table
- **Computer:** Raspberry PI 3
- **Keyboard** Controller:* Arduino Leonardo
- **Joystick:** four-way ball-top joystick bought off of ebay
- **Buttons:** arcade style buttons bought off of ebay
- **Display:** 17 inch widescreen monitor

## TIP #1 - Cutting out the space for the monitor ##
All the measuring and marking in the world doesn't make up for not being able to cut a straight line with you dremel tool.  I should've used a straight edge and just cut along the lines I had marked

## TIP #2 - Make detailed notes when disassembling the monitor ##
I went throught two monitors on this project.  After stripping the case off the first monitor, I had to "unwire" several components to take it apart.  When re-assembling, I wired them up incorrectly and shorted out the entire monitor.  Needless to say, I was more careful with the second monitor.

## TIP #3 - Q: Where am I gonna put these wires? ##
_A: In a box zip tied underneath the table._  When wiring up the joystick and buttons, i used way too much wiring and ended up with a spaghetti mess of wires that just wouldn't fit back up in the base of the table.


## Final Product ##

Not too bad for my first try.

<div class="container">
	<div class="row">
		<div class="col m3 s12">
			<img class="responsive-img" src="/images/posts/arcade_top.png">
		</div>
		<div class="col m3 offset-m1 s12">
			<img class="responsive-img" src="/images/posts/arcade_front.png">
		</div>
		<div class="col m3 offset-m1 s12">
			<img class="responsive-img" src="/images/posts/arcade_bottom.png">
		</div>
	</div>
</div>


[element-14]: https://www.element14.com/community/docs/DOC-80946/l/pik3a-the-raspberry-pi-3-ikea-retro-gaming-table
[arcade_top]: /images/posts/arcade_top.png
[arcade_front]: /images/posts/arcade_front.png
[arcade_bottom]: /images/posts/arcade_bottom.png