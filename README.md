# D5
An alternate keyboard layout originally by StrawberryTurtle: https://codeberg.org/StrawberryTurtle/, found from the [AKL Discord](https://discord.com/invite/sxTV2G5Acg).

Intended for column-staggered keyboards with two thumb keys per side. \
Light switches are recommended. I use [Ambient Nocturnals](https://lowprokb.ca/collections/switches/products/ambients-silent-choc-switches?variant=44873446391972) and the original creator uses the same ones with [even lighter 12g springs.](https://nolltronics.com/product/sprit-kailh-choc-12g-springs/)

D5 makes use of doubled/mirrored letters, thumb vowels, pinky spaces, skipmagic keys, and combos to reduce redirects, same finger bigrams and pinky movement while increasing rolls and alts.

## My implementation

I adapted mine for a 34-key board instead of the original 28 keys, which also allowed me to add Ä and Ö for Finnish typing.
My version is done with Kanata and has slight adjustments from the original.

The homerow mods were carefully adjusted for no misfires while typing, and it's been working well so far. They're partially based on [Argenkiwi's homerow setup](https://github.com/argenkiwi/kenkyo/discussions/27).

Note that the Kanata config file expects the input layout to be configured as so, with the thumb keys being `1 2` on the left half and `3 4` on the right half:

	q	w	e	r	t				y	u	i	o	p	
	a	s	d	f	g				h	j	k	l	;	 		
	z	x	c	v	b				n	m	,	.	/
					1	2		3	4		

## Layout

![alt text][layoutd5] 

[layoutd5]: https://github.com/samuelborrasca/D5akl/blob/main/D5samuel.png "layoutd5"
