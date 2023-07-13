# color_echo_sh

## Description

Shell script to source if you would like colored echo commands

## How to use
Add the following line to the top of your shell script to pull in the latest version.
```Shell
source <(curl -s https://raw.githubusercontent.com/u-clarkdeveloper/color_echo_sh/main/color_echo.sh)
```

## Commands
![example colors](https://github.com/u-clarkdeveloper/color_echo_sh/blob/main/colr_examples.png?raw=true)
<!-- <style>
    .gray{color: #AEB7B9;}
    .red{color: #FF96A2;}
    .green{color: #9EE57B;}
    .yellow{color: #FFED72;}
    .orange{color: #F8B270;}
    .purple{color: #B6A0F8;}
    .blue{color: #77D5F1;}
    .white{color: #ECFFFC;}
</style>
<p class="blue">title</p>
<p class="green">header</p>
<p class="blue">footer</p>
<p class="red">error</p>
<p class="yellow">warning</p>
<p class="gray">info</p>
<p class="green">good</p>
<p class="white">highlight</p> -->


## How to get the list of colors 
```shell
for (( i = 30; i < 38; i++ )); do echo -e "\033[0;"$i"m Normal: (0;$i); \033[1;"$i"m Light: (1;$i)"; done
```