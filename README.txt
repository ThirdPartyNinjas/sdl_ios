sdl_ios
==============================================================================

A build script for compiling libSDL2.a for iOS

1) Grab the latest version of SDL from their Mercurial repository.

hg clone http://hg.libsdl.org/SDL

2) Copy sdl_ios.sh into the iOS project folder

cp sdl_ios.sh SDL/Xcode-iOS/SDL/sdl_ios.sh

3) Build it

./sdl_ios.sh

4) Resulting output lib/libSDL2.a is a fat library containing
	iphonesimulator
		i386
		x86_64
	iphoneos
		armv7
		armv7s
		arm64
		