cmake_minimum_required(VERSION 3.8)
project(libvterm)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        bin/unterm.c
        bin/vterm-ctrl.c
        bin/vterm-dump.c
        include/vterm.h
        include/vterm_keycodes.h
        src/encoding.c
        src/keyboard.c
        src/mouse.c
        src/parser.c
        src/pen.c
        src/rect.h
        src/screen.c
        src/state.c
        src/unicode.c
        src/utf8.h
        src/vterm.c
        src/vterm_internal.h
        t/harness.c)

add_executable(libvterm ${SOURCE_FILES})