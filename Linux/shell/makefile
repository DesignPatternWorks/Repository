CC = g++
a = `cd ..;ls`
all:bin

bin:
	@if [ -d "/bin" ] ; then\
		echo "bin have"; \
	else \
		echo "bin have no"; \
	fi 
	
ifdef CC	
	@echo  "yes"
	@ls
	@whoami
	@echo $(a)
else
	@echo  "no"
endif

ifeq ($(CC),gcc)
	@echo "CC is gcc"
else ifeq ($(CC),g++)
	@echo "CC is g++"
endif
