## Roadmap
**********
### fixes:  <br />
- fix that no longer .xsession file says what to autostart, use /home/pi/.config/lxsession/LXDE/autostart instead.
this might fix the problem when making apt upgrade and all the x functions do not work anymore.<br />
- remove videomapper remote app button in CP and add magmapper button.<br />

### Video: <br />
- test if gstreamer gst-omx is loading videos faster for GPIO implementations (compile: https://gist.github.com/Swap-File/ea4b7a4739ca8c859bd7c3c3d8b087e6) <br />
- play movies and images after each other <br />
- sync with USB alsa audio does not work, fix it! (is this needed in any way?)<br />
- jump to next file button <br />
- Slow motion function (1 Increase Speed 2 Decrease Speed) (dbus control no ready yet, waiting for new omxplayer version https://github.com/popcornmix/omxplayer)<br />
- Master Slave auto-detection<br />
- Audio reactive effects, like RGB change to beat, pulsating brightness, some efx similar to camera effects<br />

### Streaming: <br />
- Support NDI (this might require an x86 platform since its not possible anymore to compile on ARM)<br />
- Add knob to show NDI version <br />
- Update Tcpsyphon (https://github.com/z37soft/INetSyphon_RaspberryPi_SDK)
- uv4l (https://www.linux-projects.org/uv4l/tutorials/desktop-streaming/)

### Image: <br />
- Gif player, gif for cli https://github.com/google/gif-for-cli <br />
- slideshow with ken burns effect (maybe with QT: https://gist.github.com/nbergont/8963892, or openFramworks ofImage)<br />

### Mapper: <br />
- Build a completely new version of Mapper with more performance, remote controllable, (syncable?) and full code based on java. Prototype availabe on my github. <br />

<br />

- Add pause button<br />

- Bezier Warp, as seen here: https://github.com/TsubokuLab/ofxBezierWarpManager https://github.com/sticknor/ofxBezierWarpManager, both examples are openGL, but i hope there is a way without it<br />
- Grid mesh <br />
- Website or screengrabber as source for mapper  <br />
- Add playlist version of mapper (plays every video in /media/internal/video) <br />
- audio usb alsa support<br />
- compile shortcut for bigmove, make moves even bigger, also small moves(not importand if remote server works <br />
- Make sync script compatible with video mapper, need new ofxomxplayer, find a coder who can do this, payable! <br />

### Autostart
- Autostart to Processing in fullscreen (still not sure how to execute command) <br />

### Others:<br />
 
- Add osc support to control everything with osc, installed node for use, use osc from npm.<br />

- check if changes in htaccess file can help resolving functions e.g. 2.0.0.100/update <br />
- move softedge file location to another place<br />
- Add OLA DMX trigger scripts to control PVJ with DMX commands<br />
- Add OLA DMX recorder script and DMX playback script to record and playback DMX commands <br />
- Search for an DMX player, https://github.com/peterdikant/SimpleDmxEngine which could be synced to omxplayer <br />
<br />
- Check if processing is still working <br />
- Add some processing demos in fullscreen <br />
- integrate sound analyzer for use with mic or soundfile: https://github.com/karlstav/cava<br />
- sound reactive video effects https://github.com/karlstav/cava https://github.com/xdaimon/music_visualizer<br />
- integrate UV4L Streaming Server (http://www.linux-projects.org/uv4l/) (tested: works 640x480, waiting for HD)<br />
- screen controls for color, brightness, contrast (openframeworks solution?) <br />
- function to show CPU usage (top)<br />
- function to display version of omxplayer, feh, tcpsyphon<br />
- make an artnet/dmx script to control omxplayer: http://doityourselfchristmas.com/forums/archive/index.php/t-22092.html <br />
- Integrate artnet player from aeby: https://github.com/atizo/epicwall/tree/master/standalone<br />
- Integrate PiTunnel for remote management <br />
- Hub75 library to be compatible with led panels and adafruit board <br />
- Integrate RaspiVJ function for videomixing (http://w.xuv.be/projects/raspivj#raspivj) <br />
- get into pi3d: http://pi3d.github.io/html/ReadMe.html#setup-on-the-raspberry-pi maybe do a mapper + slidshow with this<br />
- get into shaders: http://journeytounknownsoundscapes.blogspot.ch/2013/02/raspi-as-poor-mans-video-jockey.html?m=1<br />
- more shader stuff: https://github.com/dff180/pishadertoy<br />
- https://github.com/scottlawsonbc/audio-reactive-led-strip<br />
...

### OS for PVJ 3.7: <br />
- add Fugio (https://www.bigfug.com) Update: not installable nor compilable on raspian jessie :( <br />
- update qlcplus for headless without hdmi (run with -n or --nogui), need to compile newest version <br />

### OS for PVJ 3.8: <br />
- switch to alpinelinux: https://wiki.alpinelinux.org/wiki/Raspberry_Pi<br />

### PVJ 4k: <br />
- PocketVJ 4k will have a resolution of 4k and fully syncable and remote controllable mapper. Release date around March 2019. 

### Manual .pdf: <br />

- update manual for CP2.0.x release, new screenshots, half way done...I hate office programs <br />
- shortcuts for mapping mode with keyboard <br />
- more description for tcpsclient, with example using syphoner to capture software <br />
- correct errors concerning timer.txt (possible to seperate with commas? ) <br />
- Add scheduler commands <br />
- Something about GPIO, where is the script and how to connect buttons <br />
- how to use OSC <br />

### Tutorials (Pocketvj.com/Vimeo): <br />

- Uplaod with Filezilla<br />
- All autostart functions <br />
- Filename-Fixer<br />

=======================<br />
Opensource rocks, closedsource sucks<br />
©2018 marc-andré gasser

