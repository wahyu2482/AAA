## @file
# Copyright (c) 2020, vit9696. All rights reserved.
# SPDX-License-Identifier: BSD-3-Clause
##

PROJECT = PeCoff
PRODUCT = $(PROJECT)$(INFIX)$(SUFFIX)
OBJS    = $(PROJECT).o \
	PeCoffDebug.o \
	PeCoffHash.o \
	PeCoffInfo.o \
	PeCoffInit.o \
	PeCoffLoad.o \
	PeCoffRelocate.o
VPATH   = $(UDK_PATH)/MdePkg/Library/BasePeCoffLib2:$
include ../../User/Makefile
