
quick hack to create passwords with variable length and allowed value requirments

```
./mkpwd -l 12 -e [a-z] " " 9 '"' "'" '`'
pwd: 'P/&NF.USB<K='

./mkpwd -l 12 -e
Option exclude requires an argument
Usage: ./mkpwd --l[ength]  --e[xclude] a-z "'" '"' 0-9

./mkpwd -l
Option length requires an argument
Usage: ./mkpwd --l[ength]  --e[xclude] a-z "'" '"' 0-9
```
