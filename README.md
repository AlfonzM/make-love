# make-love

A script to automate distribution of LÖVE (Lua) games for Windows and MacOS platforms.

## Setup

Download the latest Windows 32/64-bit and the MacOS X zipped executables from https://www.love2d.org.

Create a directory `~/.love`, then place the executable files there, renaming the `love-0.x.x-win` folder to just `windows`.

i.e.

```
~/.love
├── windows
	├──love.dll
	├──love.exe
	├──OpenAL32.dll
	├──lua51.dll
	├──SDL2.dll
	├──etc...
├── love.app
```

## Usage

```
$ cd path/to/project
$ make-love
```

This will generate the builds in the `build` folder.