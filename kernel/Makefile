obj-y += memory.o
obj-y += process.o
obj-y += entry.o
KDIR := /src
PWD := $(shell pwd)

all:
    make -C $(KDIR) M=$(PWD) modules

clean:
    make -C $(KDIR) M=$(PWD) clean
