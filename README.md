# About

IPLocate is a Python-based CLI (Command-Line Interface) tool, developed by [@sayanbiswas9](https://github.com/sayanbiswas9) with assistance from AI for error testing and syntax alignment. This tool allows users to get detailed information about an IP address. Its main motive is to bring the ipinfo search together in a simple program. You can use it just by typing `iplocate` followed by the IP address you want to know info about or your own _Public IP Address_. Additionally, some new options are available that are different from any other tool available on the internet.

## Installation



### Windows x86/x64

Make sure to install _curl_ and _python_ before running these commands:

```cmd
curl -o iplocate.py https://raw.githubusercontent.com/sayanbiswas9/iplocate/main/iplocate
move iplocate.py %USERPROFILE%
pip install requests
setx PATH "%PATH%;%USERPROFILE%
```

*Note: You need to use "python iplocate.py" instead of "iplocate", which is supported only in Unix environments.
### Ubuntu/Debian

```bash
sudo apt update && sudo apt install python3 python3-pip && pip install requests
curl -o iplocate https://raw.githubusercontent.com/sayanbiswas9/iplocate/main/iplocate && chmod +x iplocate
sudo mv iplocate /usr/bin/
```

### Termux

```bash
pkg update && pkg install curl python3 python3-pip && pip install requests
curl -o iplocate https://raw.githubusercontent.com/sayanbiswas9/iplocate/main/iplocate && chmod +x iplocate && mv iplocate $PREFIX/bin/
```

### Arch Linux

```bash
curl -o iplocate https://raw.githubusercontent.com/sayanbiswas9/iplocate/main/iplocate
mkdir -p ~/.local/bin/
chmod +x iplocate
mv iplocate ~/.local/bin/
echo 'PATH=$PATH:$HOME/.local/bin/' >> ~/.bashrc && source ~/.bashrc
```



## Features

- **Reputed API**: Uses a reputed API with enhanced security and data protection.
- **User-specific fields**: Ability to get only the fields specified by the user.
- **Cross-platform**: Developed with Python, ensuring no cross-platform issues.
- **Support**: Developer aims to fix any issues within 48 hours.
- **Community-driven**: Anyone can join the developer to manage the project.

## Connect with Me

- [GitHub](https://github.com/sayanbiswas9)
- [Instagram](https://instagram.com/sayanbiswas9)
  E-mail: anonys0101@duck.com

*Thank you for using IPLocate! If you encounter any issues or have suggestions, feel free to reach out or fork this repository.*
