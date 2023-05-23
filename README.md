# wxHexEditor
wxHexEditor official GIT repo
For info : http://www.wxhexeditor.org

# Compilation instructions
$ git clone https://github.com/void-linux/void-packages.git

$ cd void-packages

$ ./xbps-src binary-bootstrap

$ mkdir -p srcpkg/wxhexditor

$ wget https://raw.githubusercontent.com/johna23-lab/wxHexEditor-for-void-linux/main/template -O srcpkg/wxhexditor/

$ mkdir -p srcpkg/wxhexditor/patches

$ wget https://raw.githubusercontent.com/johna23-lab/wxHexEditor-for-void-linux/main/Makefile.patch -O srcpkg/wxhexditor/patches/

$ ./xbps-src pkg wxhexditor



# How to install the already compiled version

$ wget https://github.com/johna23-lab/wxHexEditor-for-void-linux/releases/download/0.25/wxhexditor-0.25_1.x86_64.xbps

$ xbps-rindex -a *.xbps

$ sudo xpbs-install -R $PWD wxhexditor-0.25_1

