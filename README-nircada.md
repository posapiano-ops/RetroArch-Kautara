# Build
```bash
./configure
make clean
make DEBUG=1 GL_DEBUG=1 HAVE_NIRCADA=1 HAVE_ZARCH=0 -j4

#tooronto - build (1.8.7)
#./configure --disable-discord
#make clean 
# make V=1 HAVE_NIRCADA=1 HAVE_ZARCH=0 DEBUG=1 GL_DEBUG=1
```
to run
```bash
./retroarch
```
config file in `${HOME}/.config/retroarch`

### Note
https://docs.libretro.com/development/retroarch/compilation/ubuntu/