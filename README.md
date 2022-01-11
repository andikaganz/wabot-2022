andikaganz-Wabot-2022
Forks Watchers Stars Contributors Issues Issues Pull Request Pull Request

NOMOR BOT
https://wa.me/628978161093

Deploy to Heroku
Deploy

Heroku Buildpack
BuildPack	LINK
FFMPEG	here
IMAGEMAGICK	here
FOR TERMUX USER
pkg update && pkg upgrade
pkg install bash && pkg install wget
wget -O - https://raw.githubusercontent.com/BochilGaming/games-wabot/main/install2.sh | bash
INSTALL ON TERMUX WITH UBUNTU
[ INSTALLING UBUNTU ]

apt update && apt full-upgrade
apt install wget curl git proot-distro
proot-distro install ubuntu
echo "proot-distro login ubuntu" > $PREFIX/bin/ubuntu
ubuntu
[ INSTALLING REQUIRED PACKAGES ]

ubuntu
apt update && apt full-upgrade
apt install wget curl git ffmpeg imagemagick build-essential libcairo2-dev libpango1.0-dev libjpeg-dev libgif-dev librsvg2-dev dbus-x11 ffmpeg2theora ffmpegfs ffmpegthumbnailer ffmpegthumbnailer-dbg ffmpegthumbs libavcodec-dev libavcodec-extra libavcodec-extra58 libavdevice-dev libavdevice58 libavfilter-dev libavfilter-extra libavfilter-extra7 libavformat-dev libavformat58 libavifile-0.7-bin libavifile-0.7-common libavifile-0.7c2 libavresample-dev libavresample4 libavutil-dev libavutil56 libpostproc-dev libpostproc55 graphicsmagick graphicsmagick-dbg graphicsmagick-imagemagick-compat graphicsmagick-libmagick-dev-compat groff imagemagick-6.q16hdri imagemagick-common libchart-gnuplot-perl libgraphics-magick-perl libgraphicsmagick++-q16-12 libgraphicsmagick++1-dev
[ INSTALLING NODEJS & GAMES-WABOT ]

ubuntu
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash -
apt install -y nodejs gcc g++ make
git clone https://github.com/BochilGaming/games-wabot
cd games-wabot
npm install
npm update
FOR WINDOWS/VPS/RDP USER
Download And Install Git Click Here
Download And Install NodeJS Click Here
Download And Install FFmpeg Click Here (Don't Forget Add FFmpeg to PATH enviroment variables)
Download And Install ImageMagick Click Here
git clone https://github.com/BochilGaming/games-wabot
cd games-wabot
npm install
npm update
Run
node .
Arguments node . [--options] [<session name>]
--self
Activate self mode (Ignores other)

--pconly
If that chat not from private bot, bot will ignore

--gconly
If that chat not from group, bot will ignore

--swonly
If that chat not from status, bot will ignore

--prefix <prefixes>
prefixes are seperated by each character Set prefix
--server
Used for heroku or scan through website

--big-qr
If small qr unicode doesn't support

--restrict
Enables restricted plugins (which can lead your number to be banned if used too often)

Group Administration add, kick
--img
Enable image inspector through terminal

--autoread
If enabled, all incoming messages will be marked as read

--nyimak
No bot, just print received messages and add users to database

--test
Development Testing Mode

--trace
conn.logger.level = 'trace'
--debug
conn.logger.level = 'debug'
--presence <Presence>
when the bot executes the command, the bot will type, record, etc.

Presence avaible: available, composing, recording, paused

want to contribute?
fork this repository
Change/edit/create what you want. for example you can add features, fix bug, etc
test before making a pull req!!
make a pull req!
if your pull req is already in acc/merge, you can delete your branch or you can create pull req again :)
want to use multi-device (md)?
now games-wabot already support MD, but of course there are still many bugs and there are still many that have not been implemented,

use this branch if you want to use MD!

Thanks To
Allah SWT,

Orang Tua,

Semua yang selalu mendukung

Nurutomo BochilGaming andikaganz

Contributor
idhamthoriqbot Adiixyz zatu22 arisawali2014 Nobuyaki unx21 botstylee qisyana ryznxx @dependabot[bot] itsmeR1F4I ZeroChanBot andikaganz
