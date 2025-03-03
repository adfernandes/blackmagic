.PHONY: default

default:
	rm -rf build
	meson setup build --cross-file cross-file/native-adfernandes.ini
	meson compile -C build
#   meson compile -C boot-bin # does not built at the moment

