lib-y		:= bitops.o clear_user.o delay.o copy_from_user.o	\
		   copy_to_user.o copy_in_user.o copy_page.o		\
		   clear_page.o csum.o memchr.o memcpy.o		\
		   memset.o memcmp.o strcmp.o strncmp.o strlen.o	\
		   strnlen.o strchr.o strrchr.o tishift.o

CFLAGS_REMOVE_atomic_ll_sc.o := -pg

obj-$(CONFIG_CRC32) += crc32.o
