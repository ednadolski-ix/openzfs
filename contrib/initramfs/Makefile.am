include $(top_srcdir)/config/Shellcheck.am

initrddir = /usr/share/initramfs-tools

dist_initrd_SCRIPTS = \
       zfsunlock

SUBDIRS = conf.d conf-hooks.d hooks scripts
SHELLCHECKDIRS = hooks scripts
SHELLCHECK_OPTS = --enable=all

EXTRA_DIST = \
	README.initramfs.markdown
