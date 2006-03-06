# Makefile.am for bluetooth/src

yncludedir = @yncludedir@/bluetooth

client_DATA =			\
	bluetooth.ycp		\
	bluetooth_auto.ycp	\
	bluetooth_proposal.ycp

ynclude_DATA =			\
	helps.ycp		\
	wizards.ycp		\
	dialogs.ycp		\
	complex.ycp

desktop_DATA =			\
	bluetooth.desktop

module_DATA =			\
	Bluetooth.ycp

bluetooth:
	ln -sf . bluetooth

ycpchook = bluetooth

EXTRA_DIST = $(client_DATA) $(ynclude_DATA) $(module_DATA) $(desktop_DATA)

include $(top_srcdir)/Makefile.am.common
