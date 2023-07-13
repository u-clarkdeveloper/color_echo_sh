# color_echo_sh

## Description

Shell script to source if you would like colored echo commands

## How to use
Add the following line to the top of your shell script to pull in the latest version.
```shell
source <(curl -s https://raw.githubusercontent.com/u-clarkdeveloper/color_echo_sh/main/color_echo.sh)
```

## Commands
![example colors](https://github.com/u-clarkdeveloper/color_echo_sh/blob/main/color_examples.png?raw=true)

## How to get the list of colors 
```shell
for (( i = 30; i < 38; i++ )); do echo -e "\033[0;"$i"m Normal: (0;$i); \033[1;"$i"m Light: (1;$i)"; done
```