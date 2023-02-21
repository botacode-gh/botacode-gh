# botacode

<img title="Flamingo plushie in a relaxed pose" src="/My%20project.png" align="right" width="270" height="178">

>Life's hard enough, so use code to ease it.  [^1]

I try to make things easier for everyone, and I think using code is a **great and fun** way to do it.

Check out some stuff on my mind:

[Stuff to attempt](#projects)<br/>
[Stuff to learn](#learnlist)<br/>
[Other stuff](#miscellaneous)<br/>

<h2 id="projects">Stuff to attempt</h2>

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
- **LetsSee**: Keep track of shows and movies you've watched, are watching, and want to watch. Manage and share these lists. It'll even help you choose what to watch based on your previous choices! No, I don't really care that something like this already exists.

<h2 id="learnlist">Stuff to learn</h2>

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

<h2 id="miscellaneous">Other stuff</h2>

Sure, embedding videos in websites is probably considered ancient technology now, but that doesn't mean it's still not cool!
Just look at this recipe video for what looks to be really yummy pasta:
</br>
</br>
<a href="https://www.youtube.com/watch?v=GRteIZM05Sg" target="_blank">
	<img src="https://i3.ytimg.com/vi/GRteIZM05Sg/maxresdefault.jpg" alt="YouTube recipe video for Spaghetti all'Assassina (Assassin’s Spaghetti)" width="50%" height="50%" border="10"/>
</a>

## Footnotes
[^1]: I'm sure someone said something like this before.
