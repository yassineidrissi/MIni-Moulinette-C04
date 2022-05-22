# PREAMBLE
This is an edit of prev c03est made by @yaidriss to fit with the 2022 project c03. <br/>
(ORIGINAL REP : https://github.com/yassineidrissi) <br/>
This update was made by @yaidriss <br/>

# Mini-Moulinette
<img align="right" src="./srcs/img_readme.png" width="50%"/>
This repository contains script to test your c03 project.

| Project  | Links |
| ------------- | ------------- |
| How to use it (in darija)  | [on this page](https://github.com/y3ll0w42/Mini-Moulinette-c03/blob/master/supported_functions.md)  |
| C02  | [on this page](https://github.com/yassineidrissi/Mini_Moulinette_C02)  |
| C03  | [on this page](https://github.com/yassineidrissi/Mini-Moulinette-C03) |
| C04  | [on this page](https://github.com/yassineidrissi/Mini-Moulinette-C04)  |

The script will do the following tests :

- Check if the author file exists
- Check content of the author file
- Compil library
- Check norminette errors
- Check forbidden functions
- Tests functions

At the end of the tests, a deepthought file will be created, inside which you
can find all the results and error/failure messages. You can also see your
results in tests directory.

The script will compil your files with your c03.

:warning:All the tests made are not the official tests:warning:

## Getting Started

### Installation

```bash
git clone https://github.com/y3ll0w42/Mini-Moulinette-c03
```

### Configuration

If you run the script for the first time, it will automatically create
`my_config.sh` file and ask you to edit it with the path of your c03
project.
You can also choose the colors that will be used and the path where the

### Options available
| Option | Description |
| --- | --- |
| `-h`<br />`--help` | Display help and exit |
| `-d` | Allows to perform the tests even if the files are in directories |
| `-c` | Disable color |
| `-s` | Disable searching Makefile and author files |
| `-m` | When compiling library, test all the Makefile's rules (instead of doing only make re and checking if other rules exist). |


Add successively all options you want, in the order you want.
For example :
```bash
bash grademe.sh ft_strcmpy -f ft_ -n
```

### Supported functions
All the supported functions are listed [on this page](https://github.com/yassineidrissi/Mini-Moulinette-c03/blob/master/supported_functions.md).

### Contributors
- yaidriss : https://github.com/yassineidrissi
# C_tester_1337
# Mini-Moulinette
