# dazai

This is the shell script which generate hankaku/zenkaku random character string.



## getting start

```bash
$ git clone https://github.com/ontheroadjp/dazai
$ PATH="path/to/clone/this/repository:$PATH"
```



## usage

```bash
# 20 character string with HANKAKU and ZENKAKU char.
$ sh dazai
hぬﾋ№∠ﾔルλ}＝ﾟгﾞヅ∨ﾌ⑪ｸЮ０

# 20 character string with HANKAKU char.
$ dazai han
ﾟｳGﾌ^Uﾝﾍﾃﾞ*ﾞTﾊﾍﾕﾌｹﾑs

# 20 character string with ZENKAKU char.
$ dazai zen
⑬ЁЬ㍽…ゴミ┤∩ポゲ㌧ゝＡΛΣЦ┌づτ

# 20 character string with HANKAKU char exclude symbol chars.
$ dazai han --no-symbol
60gBQVdSUUucJ4k9iuu1

# 20 character string with ZENKAKU char exclude symbol chars.
$ dazai zen --no-symbol
５ぶまＣペぺをそぎこヌン３８タドｒにＱズ

# 50 character string with HANKAKU char exclude symbol chars.
$ dazai han --no-symbol -l 50
84E5jFtQdTXu9uqWx5WD0JEz8W4CdsNcTk1BfisMuYp0ueIHmk

# 5 lines of 50 character string with HANKAKU char exclude symbol chars.
$ dazai han --no-symbol -n 5
ifm2lnTVG5kC5oFlk2Xi
SJE6CZaItuI2HbYaMffi
Nc9YrEc3pGkF8zPut5al
2Lazkq9eykUpVNhhyCXJ
3vIODNaiU0dk2ZGIRQQ9

# 5 lines of 35 character string with HANKAKU char exclude symbol chars.
$ dazai han --no-symbol -n 5 -l 35
Y8XbvReoddj9x0ISZNqnovVpdEgl14iXQHW
sQpyFxWasbg5aiDtI7eBHZKoZd9WLMyFEFy
5xbjlOCEhxLjMPtJvl52zRbap4gp3Rv0IAR
n5kuU1ie6ihcFrgllmQEs3jw6FAlNay0NhC
syerhN9ywqAxmyZbfeu2uqCiBJwmSGUCItk
```



## optios

```bash
Options:
  -h, --help                     Show help.
  -v, --version                  Show script version.
  -n, --length ARG               length of output chars.
  -n, --number ARG               number of output char lines.
      --no-symbol                No symbol within output.
      --verbose                  Print various logging information
```

