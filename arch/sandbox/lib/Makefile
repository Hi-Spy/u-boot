#
# Copyright (c) 2011 The Chromium OS Authors.
#
# (C) Copyright 2002-2006
# Wolfgang Denk, DENX Software Engineering, wd@denx.de.
#
# SPDX-License-Identifier:	GPL-2.0+
#

obj-y	+= interrupts.o
ifndef CONFIG_SPL_BUILD
obj-$(CONFIG_PCI)	+= pci_io.o
endif
obj-$(CONFIG_CMD_BOOTM) += bootm.o
