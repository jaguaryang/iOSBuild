#iOSBuild



Usage: ./iOS-build [lua openssl curl uv x264 xvid ffmpeg isofs]

FAQ:

    build libuv require MacPorts http://www.macports.org
    # sudo port install automake autoconf libtool
    
    ld: file not found: /usr/lib/system/host/libdyld.dylib for architecture i386
    # sudo mkdir -p /usr/lib/system/host
    # sudo ln -s /usr/lib/system/libdyld.dylib /usr/lib/system/host/libdyld.dylib
