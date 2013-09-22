#http://www.medooze.com/products/media-mixer-server/installation.aspx

# mp4v2-1.9.1+svn479~dfsg0 
build: mcu /usr/local/src/ffmpeg /usr/local/src/x264 /usr/local/src/speex-1.2rc1 /usr/local/src/opus-1.0.2 /usr/local/src/libvpx /usr/local/src/xmlrpc-c-1.16.35 /usr/local/src/webrtc /usr/local/src/mp4v2
	make -C mcu/mcu \
		CC="ccache gcc" \
		CXX="ccache g++" \
		STATIC=yes \
		LOG=yes \
		DEBUG=yes \
		FLASHSTREAMER=no \
		VADWEBRTC=no \
		SRCDIR=$(shell pwd)/mcu/mcu \
		TARGET=/usr/local \
		WEBRTCINCLUDE=/usr/local/src/webrtc/trunk/webrtc/ \
		WEBRTDIROBJ=/usr/local/src/webrtc/trunk/out/Debug/obj/webrtc \
		INCLUDE="-I$(shell pwd)/mcu/mcu/include -I/usr/local/src/ffmpeg/ -I/usr/local/src/x264 -I/usr/local/src/speex-1.2rc1/include -I/usr/local/src/opus-1.0.2/include -I/usr/local/src/libvpx -I/usr/local/src/webrtc/trunk/webrtc -I/usr/local/src/webrtc/trunk -I/usr/local/src/xmlrpc-c-1.16.35" \
		LDFLAGS="-pthread /usr/lib/x86_64-linux-gnu/libbz2.a /usr/local/src/ffmpeg/libavcodec/libavcodec.a /usr/local/src/ffmpeg/libavdevice/libavdevice.a /usr/local/src/ffmpeg/libavfilter/libavfilter.a /usr/local/src/ffmpeg/libavformat/libavformat.a /usr/local/src/ffmpeg/libavresample/libavresample.a /usr/local/src/ffmpeg/libavutil/libavutil.a /usr/local/src/ffmpeg/libpostproc/libpostproc.a /usr/local/src/ffmpeg/libswresample/libswresample.a /usr/local/src/ffmpeg/libswscale/libswscale.a /usr/local/src/x264/libx264.a /usr/local/src/speex-1.2rc1/libspeex/.libs/libspeex.a /usr/local/src/speex-1.2rc1/libspeex/.libs/libspeexdsp.a /usr/local/src/opus-1.0.2/.libs/libopus.a /usr/local/src/libvpx/libvpx.a /usr/local/src/libvpx/libgtest.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_cpp.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc++.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_server++.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_server_cgi++.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_server_pstream++.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_packetsocket.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_server_abyss++.a /usr/local/src/xmlrpc-c-1.16.35/src/libxmlrpc.a /usr/local/src/xmlrpc-c-1.16.35/src/libxmlrpc_server.a /usr/local/src/xmlrpc-c-1.16.35/src/libxmlrpc_server_abyss.a /usr/local/src/xmlrpc-c-1.16.35/src/libxmlrpc_server_cgi.a /usr/local/src/xmlrpc-c-1.16.35/lib/abyss/src/libxmlrpc_abyss.a /usr/local/src/xmlrpc-c-1.16.35/lib/expat/xmltok/libxmlrpc_xmltok.a /usr/local/src/xmlrpc-c-1.16.35/lib/expat/xmlparse/libxmlrpc_xmlparse.a /usr/local/src/xmlrpc-c-1.16.35/lib/libutil/libxmlrpc_util.a /usr/local/src/mp4v2/.libs/libmp4v2.a /usr/local/src/webrtc/trunk/out/Release/obj/webrtc/common_audio/libcommon_audio.a -lva -lrt -lgsm -lz -lsrtp -lcrypto -lxmlrpc -lbz2"
	rm -fr mcu/mcu/build/
	make -C mcu/mcu \
		CC="ccache gcc" \
		CXX="ccache g++" \
		STATIC=yes \
		LOG=yes \
		DEBUG=no \
		FLASHSTREAMER=no \
		VADWEBRTC=no \
		SRCDIR=$(shell pwd)/mcu/mcu \
		TARGET=/usr/local \
		WEBRTCINCLUDE=/usr/local/src/webrtc/trunk/webrtc/ \
		WEBRTDIROBJ=/usr/local/src/webrtc/trunk/out/Debug/obj/webrtc \
		INCLUDE="-I$(shell pwd)/mcu/mcu/include -I/usr/local/src/ffmpeg/ -I/usr/local/src/x264 -I/usr/local/src/speex-1.2rc1/include -I/usr/local/src/opus-1.0.2/include -I/usr/local/src/libvpx -I/usr/local/src/webrtc/trunk/webrtc -I/usr/local/src/webrtc/trunk -I/usr/local/src/xmlrpc-c-1.16.35" \
		LDFLAGS="-pthread /usr/lib/x86_64-linux-gnu/libbz2.a /usr/local/src/ffmpeg/libavcodec/libavcodec.a /usr/local/src/ffmpeg/libavdevice/libavdevice.a /usr/local/src/ffmpeg/libavfilter/libavfilter.a /usr/local/src/ffmpeg/libavformat/libavformat.a /usr/local/src/ffmpeg/libavresample/libavresample.a /usr/local/src/ffmpeg/libavutil/libavutil.a /usr/local/src/ffmpeg/libpostproc/libpostproc.a /usr/local/src/ffmpeg/libswresample/libswresample.a /usr/local/src/ffmpeg/libswscale/libswscale.a /usr/local/src/x264/libx264.a /usr/local/src/speex-1.2rc1/libspeex/.libs/libspeex.a /usr/local/src/speex-1.2rc1/libspeex/.libs/libspeexdsp.a /usr/local/src/opus-1.0.2/.libs/libopus.a /usr/local/src/libvpx/libvpx.a /usr/local/src/libvpx/libgtest.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_cpp.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc++.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_server++.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_server_cgi++.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_server_pstream++.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_packetsocket.a /usr/local/src/xmlrpc-c-1.16.35/src/cpp/libxmlrpc_server_abyss++.a /usr/local/src/xmlrpc-c-1.16.35/src/libxmlrpc.a /usr/local/src/xmlrpc-c-1.16.35/src/libxmlrpc_server.a /usr/local/src/xmlrpc-c-1.16.35/src/libxmlrpc_server_abyss.a /usr/local/src/xmlrpc-c-1.16.35/src/libxmlrpc_server_cgi.a /usr/local/src/xmlrpc-c-1.16.35/lib/abyss/src/libxmlrpc_abyss.a /usr/local/src/xmlrpc-c-1.16.35/lib/expat/xmltok/libxmlrpc_xmltok.a /usr/local/src/xmlrpc-c-1.16.35/lib/expat/xmlparse/libxmlrpc_xmlparse.a /usr/local/src/xmlrpc-c-1.16.35/lib/libutil/libxmlrpc_util.a /usr/local/src/mp4v2/.libs/libmp4v2.a /usr/local/src/webrtc/trunk/out/Release/obj/webrtc/common_audio/libcommon_audio.a -lva -lrt -lgsm -lz -lsrtp -lcrypto -lxmlrpc -lbz2"

install:
	sudo make -C mcu/mcu DEBUG=no install
	sudo make -C mcu/mcu DEBUG=yes install

clean:
	make -C mcu/mcu clean
	rm -fr mcu/mcu/build mcu/mcu/bin

dependencies:
	sudo apt-get -y install build-essential ccache subversion git-core libxmlrpc-core-c3-dev libsrtp0-dev libnss3-dev libgtk2.0-dev texinfo
	sudo apt-get -y build-dep x264
	sudo mkdir -p /usr/local/src
	sudo chown -R `whoami` /usr/local/src
	touch $@

/usr/local/src/depot_tools:
	git clone https://chromium.googlesource.com/chromium/tools/depot_tools.git $@

# http://www.webrtc.org/reference/getting-started
/usr/local/src/webrtc: dependencies /usr/local/src/depot_tools
	mkdir -p /usr/local/src/webrtc
	cd $@; PATH="$$PATH":/usr/local/src/depot_tools gclient config http://webrtc.googlecode.com/svn/trunk
	cd $@; PATH="$$PATH":/usr/local/src/depot_tools gclient sync --force
	cd $@; PATH="$$PATH":/usr/local/src/depot_tools gclient runhooks --force
	cd $@/trunk; ninja -C out/Release/ common_audio
	cd $@/trunk; ninja -C out/Debug/ common_audio

mp4v2-1.9.1+svn479~dfsg0:
	apt-get source mp4v2
	sudo apt-get -y build-dep mp4v2
	cd $@; ./configure ; CC='ccache gcc' make -C $@ && sudo make -C $@ install

/usr/local/src/mp4v2:
	svn checkout http://mp4v2.googlecode.com/svn/trunk/ $@
	cd $@ ; autoreconf -fiv; ./configure ; make -C $@
	sudo make -C $@ install install-man dist

/usr/local/src/libvpx: dependencies
	git clone http://git.chromium.org/webm/libvpx.git $@
	cd $@; ./configure --enable-shared ; CC='ccache gcc' make -C $@

speex-1.2rc1.tar.gz:
	wget http://downloads.xiph.org/releases/speex/speex-1.2rc1.tar.gz

/usr/local/src/speex-1.2rc1: dependencies speex-1.2rc1.tar.gz
	tar xzf speex-1.2rc1.tar.gz -C /usr/local/src
	cd $@; ./configure ; CC='ccache gcc' make -C $@

opus-1.0.2.tar.gz:
	wget -o opus-1.0.2.tar.gz http://downloads.xiph.org/releases/opus/opus-1.0.2.tar.gz

/usr/local/src/opus-1.0.2: dependencies opus-1.0.2.tar.gz /usr/local/src/speex-1.2rc1
	tar xzf opus-1.0.2.tar.gz -C /usr/local/src
	ln -s . $@/include/opus
	cd $@; ./configure ; CC='ccache gcc' CFLAGS="-I/usr/local/src/speex-1.2rc1/include -L/usr/local/src/speex-1.2rc1" make -C $@

/usr/local/src/x264: dependencies
	git clone git://git.videolan.org/x264.git $@
	sudo dpkg -i yasm_1.2.0-1_amd64.deb
	cd $@; ./configure --enable-debug --enable-shared --enable-pic ; CC='ccache gcc' make -C $@
	sudo make -C $@ install

/usr/local/src/ffmpeg: dependencies
	git clone git://source.ffmpeg.org/ffmpeg.git $@
	cd $@; ./configure --enable-avresample --enable-shared --enable-gpl --enable-nonfree --disable-stripping --enable-zlib --enable-avresample --enable-decoder=png ; CC='ccache gcc' make -C $@ 
	sudo make -C $@ install

xmlrpc-c-1.16.35.tgz:
	wget http://downloads.sourceforge.net/project/xmlrpc-c/Xmlrpc-c%20Super%20Stable/1.16.35/xmlrpc-c-1.16.35.tgz

/usr/local/src/xmlrpc-c-1.16.35: xmlrpc-c-1.16.35.tgz
	tar xzf xmlrpc-c-1.16.35.tgz -C /usr/local/src
	cd $@; ./configure ; CC='ccache gcc' make -C $@
	sudo make -C $@ install

mcu: dependencies
	svn checkout svn://svn.code.sf.net/p/mcumediaserver/code/trunk mcu
	touch $@

#	apt-get -y install make build-essential libgsm1-dev libspeex-dev libavcodec-dev libspeex-dev libspeexdsp-dev libxmlrpc-core-c3-dev
#	dpkg -i libopus0_1.0.1-0ubuntu1_amd64.deb libopus-dev_1.0.1-0ubuntu1_amd64.deb
