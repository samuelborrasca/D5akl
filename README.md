# D5
An alternate keyboard layout originally by StrawberryTurtle: [https://codeberg.org/StrawberryTurtle/zilpzalp-D5.git](https://codeberg.org/StrawberryTurtle/zilpzalp-D5.git), found from the [AKL Discord](https://discord.com/invite/sxTV2G5Acg).

Intended for column-staggered keyboards with two thumb keys per side. \
Light switches are recommended. I use [Ambient Nocturnals](https://lowprokb.ca/collections/switches/products/ambients-silent-choc-switches?variant=44873446391972) and the original creator uses the same ones, with [lighter 12g springs on the pinky and thumb keys.](https://nolltronics.com/product/sprit-kailh-choc-12g-springs/)

D5 makes use of doubled/mirrored letters, thumb vowels, chiral space/skipmagic pinkies, and horizontal & vertical ombos to reduce redirects, same finger bigrams and pinky movement while increasing rolls and alts.

## My implementation

The original is specifically meant for the 28-key [Zilpzalp](https://keeb.supply/products/zilpzalp). My version is for 34-key boards like [Re-gret](https://github.com/rschenk/re-gret), and is made with Kanata instead of QMK or ZmK.
34 keys also allowed me to add Ä and Ö for Finnish typing.


The homerow mods were carefully adjusted for no misfires while typing, and have been working well so far. They're based on [Argenkiwi's homerow setup](https://github.com/argenkiwi/kenkyo/discussions/27).

Note that the Kanata config file expects the input layout to be configured as so, with the thumb keys being `1 2` on the left half and `3 4` on the right half:

	q	w	e	r	t				y	u	i	o	p	
	a	s	d	f	g				h	j	k	l	;	 		
	z	x	c	v	b				n	m	,	.	/
					1	2		3	4		

## Layout

![alt text][layoutd5] 

[layoutd5]: https://github.com/samuelborrasca/D5akl/blob/main/D5samuel.png "layoutd5"
