# These tests hit an assert when used with gnrc_netif, but they exactly for
# testing this netdev simulating framework, so I it's better if the assert is
# ignored.
CFLAGS += -DNDEBUG
include ../Makefile.tests_common

BOARD_INSUFFICIENT_MEMORY := arduino-duemilanove arduino-leonardo arduino-nano \
                             arduino-uno nucleo-f031k6

DISABLE_MODULE = auto_init

USEMODULE += gnrc
USEMODULE += gnrc_neterr
USEMODULE += gnrc_netif
USEMODULE += netdev_eth
USEMODULE += netdev_test
USEMODULE += od

CFLAGS += -DGNRC_PKTBUF_SIZE=200

include $(RIOTBASE)/Makefile.include
