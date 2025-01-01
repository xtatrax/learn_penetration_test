# Reverse Shell

### 攻撃側(待ち受け)
```
nc -lvnp ポート

l : リッスン(待ち受け)モード  
v : 出力  
n : DNSの名前解決を行わない  
p : ポート指定  
```

### 被害者側
Kali 標準スクリプト
/usr/share/webshells/
  - perl/perl-reverse-shell.pl
  - php/php-reverse-shell.php

リバースシェルチートシート  
https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet

