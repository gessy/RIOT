include ../Makefile.tests_common

BOARD_INSUFFICIENT_MEMORY := arduino-duemilanove arduino-uno nucleo-f031k6

FEATURES_REQUIRED = periph_uart
FEATURES_OPTIONAL = periph_lpuart  # STM32 L0 and L4 provides lpuart support

USEMODULE += periph_uart_dma_tx
USEMODULE += shell
USEMODULE += xtimer

include $(RIOTBASE)/Makefile.include
