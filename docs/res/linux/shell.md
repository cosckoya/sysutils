# Shell
```markdown
          ===.
      =====.==`.               __,------._
         ===`.8=);   _/)    .-'           ``-.
         _ (G^ @@__ / '.  .' By Toutatis, the `.
   ,._,-'_`-/,-^( _).__: .' druid's potion has :
  (    / .MMm.Y_)/      ,'   turned me into    |
   `'(|.oMMMM       __,',-'`._  ascii art!   ,'
   d88:'mOom        `--'      `-..______,--''
   88::(::\d88b
   Y88  ':88888
_________888P__________________________________________________
```

## Useful scripts
### Get Colors from Shell
```bash
#!/bin/bash

for x in {0..8}; do
  for i in {30..37}; do
    for a in {40..47}; do
      echo -ne "\e[$x;$i;$a""m\\\e[$x;$i;$a""m\e[0;37;40m ";
    done;
  echo;
  done;
done
```
## References
- [Awesome Shell](https://github.com/alebcay/awesome-shell)
- [Bash](https://tiswww.case.edu/php/chet/bash/bashtop.html)
- [Awesome Bash](https://github.com/awesome-lists/awesome-bash)
- [ZSH](https://www.zsh.org/)
- [Awesome ZSH](https://github.com/unixorn/awesome-zsh-plugins)
