# botacode

<img title="Flamingo plushie in a relaxed pose" src="/My%20project.png" width="270" height="178">

>Life's hard enough, so use code to ease it.  [^"info"]

I try to make things easier for everyone, and I think using code is a **great and fun** way to do it.

## (Potential) Projects
Some might work out, others might not. None exist outside my head *yet*.
- **TurnItOver**: Record and calculate turnip commerce prices in *[Animal Crossing: New Horizons](https://en.wikipedia.org/wiki/Animal_Crossing:_New_Horizons)*.
- **Knifeblock**: All-encompassing tool for restaurant owners. Knifeblock helps you 
  - manage inventory,
  - track suppliers' prices,
  - create turnover reports,
  - record & evaluate statistical data,
  - schedule employee shifts,
  - plan & implement marketing strategies,
  - and way more!
- **LetsSee**: Keep track of shows and movies you've watched, are watching, and want to watch. Manage and share these lists. It'll even help you choose what to watch based on your previous choices!

## Stuff to learn!
Like this code from *[Quake III Arena](https://en.wikipedia.org/wiki/Fast_inverse_square_root#Overview_of_the_code)*, I don't know what it does, but I heard it's ingenious and I want to understand it!
```c
float Q_rsqrt( float number )
{
	long i;
	float x2, y;
	const float threehalfs = 1.5F;

	x2 = number * 0.5F;
	y  = number;
	i  = * ( long * ) &y;                       // evil floating point bit level hacking
	i  = 0x5f3759df - ( i >> 1 );               // what the flamingo? 
	y  = * ( float * ) &i;
	y  = y * ( threehalfs - ( x2 * y * y ) );   // 1st iteration
//	y  = y * ( threehalfs - ( x2 * y * y ) );   // 2nd iteration, this can be removed

	return y;
}
```

## Footnotes
[^"info"]: I'm sure someone said something like this before.
