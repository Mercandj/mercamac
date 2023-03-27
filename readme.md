# mercan_network_macos

This is a menu bar app for Mac OS.

## How to run the app

- Download the latest zip version
- Unzip
- Double click on the `mercamac.app` file

## How to run the app on my mac from sources

Copy past the following lines in a mac terminal

```shell
git clone https://github.com/Mercandj/mercamac.git # Get the sources
pushd mercamac # Change directory to the sources code
xcodebuild -scheme mercamac build CONFIGURATION_BUILD_DIR=./build # 
popd mercamac
cp ./mercamac/build/mercamac.app ./mercamac.app
rm -rf ./mercamac/build
open ./mercamac.app
```

## How to build the app

- On macos, open the terminal
- Type the following command
- `git clone https://github.com/Mercandj/mercamac.git` 
- `cd mercamac`
- `xcodebuild -scheme mercamac build CONFIGURATION_BUILD_DIR=./build`
- The app will be on `./build/mercamac.app`

## How to run the app

- Follow steps `How to build the app`
- Then, on finder, double click on the `mercamac.app` or via the terminal `open ./build/mercamac.app`

This app is based on
- the [Up&Down](https://github.com/gjiazhe/Up-Down) app version 1.1
- the command line tool [nettop](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/nettop.1.html).