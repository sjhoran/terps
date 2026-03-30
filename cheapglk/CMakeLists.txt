cmake_minimum_required(VERSION 3.10)

add_library(glk
  cgfref.c cggestal.c cgmisc.c cgstream.c cgstyle.c cgwindow.c cgschan.c
  cgdate.c cgunicod.c main.c gi_dispa.c gi_blorb.c gi_debug.c cgblorb.c)
