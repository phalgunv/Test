ifneq ($(KERNELRELEASE),)



    obj-m	:= hello.o
        else
    KDIR	:= /lib/modules/$(shell uname -r)/build
    PWD		:= $(shell pwd)

    default:
	$(MAKE) -C $(KDIR) SUBDIRS=$(PWD) modules
    endif
