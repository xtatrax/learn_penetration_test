# NMAP

公式日本語Reference
https://nmap.org/man/ja/index.html

### 基本的な使い方

```
nmap -sV -T5 -oN outlog.file テスト先IP 
```

### よく使うオプション
```
-sV # ポートを使っている Service と version を調べる
-T5 # -T<0-5> 高速化
-oN path # 結果をファイルに出力 
```


