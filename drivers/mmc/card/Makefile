#
# Makefile for MMC/SD card drivers
#

obj-$(CONFIG_MMC_BLOCK)		+= mmc_block.o
mmc_block-objs			:= block.o queue.o
obj-$(CONFIG_MMC_TEST)		+= mmc_test.o

obj-$(CONFIG_SDIO_UART)		+= sdio_uart.o
obj-$(CONFIG_SDIO_CARD)		+= sdio_card.o
obj-$(CONFIG_SDIO_CHANNEL)		+= sdio_channel.o
