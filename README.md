This script can fully parse all M2s and modify any chunk/track. It can resize, rescale, rotate, retexture, modify opacity, particles, ribbons, cameras - everything that can be reasonably touched by a script.

This script should help replace a lot of time spent performing basic operations like rescaling a model in blender. It has a unified mode (known as basicScaling) which will automatically rescale a model, including all the necessary components such as animations.

This script also features .anim file autoloading. It will parse the related .anim files and open/read/modify/write/save/close them.

To use the script, simply load it into 010 Editor and run it on the m2 file. Currently, only vanilla/tbc/wotlk are supported. I didn't have any cata+ clients while writing it, but added the offset tables for future m2s. If you want to fill them in, or send me a pack of m2s from a specific expansion, I'll add support for them.

It is still in development. It handles everything correctly from my testing, but there's still a few features that I'll be adding in the future. Currently, color can only be downshifted as I haven't written RGB shifting functions yet. As well, I plan on inlining all functions in the future to make the code much cleaner; for now, it's just fully outlined according to m2 structures.

This script took well over 200+ hours to write, and I believe it will come in very handy for anyone interested in editing m2 files in 010. If you enjoy the work and wish to help support my efforts in creating useful tools, then please consider supporting me through patreon or paypal.

https://www.patreon.com/wallcraft

https://www.paypal.com/biz/fund?id=3LY74ZUQHWCG6

With that said, enjoy.
