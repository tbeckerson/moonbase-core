echo '/* not used */' > include/curl/types.h &&

OPTS+=" --enable-threaded-resolver \
        --enable-versioned-symbols \
        --disable-curldebug \
        --disable-manual \
        --disable-static \
        --without-libpsl \
        --without-librtmp \
        --with-zlib"

default_build &&

install -m644 {,/usr/}include/curl/types.h
