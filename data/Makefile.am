SUBDIRS = countries extensions fonts keymaps hw_info

dist_pkgdata_DATA = \
	encoding.conf \
	keymap.xml \
	menu.xml \
	prev.png \
	black.mvi \
	rcpositions.xml \
	setup.xml \
	skin_default.xml \
	skin_subtitles.xml \
	startwizard.xml \
	skin.xml \
	freesat.t1 \
	freesat.t2 \
	timezone.xml \
	unicable.xml \
	pic_frame.png
	

if HAVE_TEXTLCD
dist_pkgdata_DATA += skin_text.xml
else
SUBDIRS += display
endif
