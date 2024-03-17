# pocket-gameboy-library-images

This was a small project that got a bit out of hand.

Originally this was just an attempt to fix a few things that annoyed me with the [libretro-thumbnails' Game Boy image set](https://github.com/libretro-thumbnails/Nintendo_-_Game_Boy): Japan- & Europe-specific releases in that 
set often make use of the American art, even when the title is different or it's using a completely different licensed property.

What I quickly discovered while doing that is that a lot of the images in that set are at best composites — it's box art, but the Nintendo Seal of Quality or the Game Boy logo has been replaced with one from another source — and at worst they're straight up photoshop jobs. Sometimes decently done photoshop jobs, and sometimes
[insultingly](https://github.com/libretro-thumbnails/Nintendo_-_Game_Boy/blob/b1e90a4/Named_Boxarts/World%20Beach%20Volley%20-%201992%20GB%20Cup%20(Europe).png),
[laughably](https://github.com/libretro-thumbnails/Nintendo_-_Game_Boy/blob/b1e90a47ad525df6bd4deb7fedefc81edfa80400/Named_Boxarts/Ring%20Rage%20(USA).png) [bad](https://github.com/libretro-thumbnails/Nintendo_-_Game_Boy/blob/b1e90a4/Named_Boxarts/Super%20James%20Pond%20(Europe).png) ones.

At which point I started building my own library set. And then I decided "Why not separate regional sets with the box art for games that had the same ROM released in multiple regions?"

And well, that's how we got here.

Still to do:
* Only the most obvious photoshop jobs were fixed and the composites were largely left alone. A second pass needs to be done to find less obvious fakes.
* Some percentage of the Japanese box art that was technically correct is also oddly resized into the incorrect aspect ratio. Need to double check these to see which need fixing.
* Game Boy Color.
