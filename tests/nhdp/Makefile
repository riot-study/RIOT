include ../Makefile.tests_common

BOARD_BLACKLIST := arduino-duemilanove arduino-leonardo \
                   arduino-mega2560 arduino-nano \
                   arduino-uno chronos mega-xplained \
                   msb-430 msb-430h telosb waspmote-pro \
                   wsn430-v1_3b wsn430-v1_4 z1
BOARD_INSUFFICIENT_MEMORY := i-nucleo-lrwan1 nucleo-f031k6 nucleo-f042k6 \
                             nucleo-l031k6 nucleo-f030r8 \
                             nucleo-f303k8 nucleo-f334r8 nucleo-l053r8 \
                             stm32f0discovery stm32l0538-disco

USEMODULE += gnrc_ipv6
USEMODULE += gnrc_sock_udp
USEMODULE += nhdp

include $(RIOTBASE)/Makefile.include
