include ../Makefile.tests_common

BOARD_BLACKLIST := arduino-duemilanove arduino-leonardo \
                   arduino-mega2560 arduino-nano \
                   arduino-uno chronos mega-xplained \
                   msb-430 msb-430h telosb waspmote-pro wsn430-v1_3b \
                   wsn430-v1_4 z1

BOARD_INSUFFICIENT_MEMORY := nucleo-f031k6 nucleo-f042k6

CFLAGS += -DTHREAD_STACKSIZE_MAIN=\(5*THREAD_STACKSIZE_DEFAULT\)
USEPKG += hacl
USEMODULE += random
USEMODULE += embunit

include $(RIOTBASE)/Makefile.include
