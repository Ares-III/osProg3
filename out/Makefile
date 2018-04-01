KBUILD_EXTRA_SYMBOLS := /home/jbn/osProg3/in/Module.symvers

obj-m += charkmod-out.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules

clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
