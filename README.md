We	want	to	apply	some	function	to	all	elements	in	an	array thr Solution for thiis prob is Use	NumPy’s	vectorize	method, NumPy’s	vectorize	class	converts	a	function	into	a	function	that	can	apply	to	all	elements	in	an	array
or	slice	of	an	array.	It’s	worth	noting	that	vectorize	is	essentially	a	for	loop	over	the	elements	and does	not	increase	performance.	Furthermore,	NumPy	arrays	allow	us	to	perform	operations	between
 arrays	even	if	their	dimensions	are	not	the	same	(a	process	called	broadcasting).	For	example,	we	can create	a	much	simpler	version	of	our	solution	using	broadcasting.
