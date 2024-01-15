
## git
```
git clone https://github.com/fuseimatome/docs.git
git remote set-url origin https://github.com/fuseimatome/docs.git
cd fuseimatome
jb create test-book
cd test-book
jb clean .
jb build .
cd fuseimatome/docs
ghp-import -n -p -f _build/html
```

## Twitter Card

<meta name="twitter:card" content="summary">
<meta name="twitter:title" content="ＥＮＥＯＳの内部通報制度に関する訴訟について">
<meta name="twitter:description" content="現在の法律の下では、通報に対して適切に対応していないことを通報者に分からないように隠すことが容易に行えますので、内部通報制度に関する法律は課題があります。">
<meta name="twitter:image" content="https://fuseimatome.github.io/docs/_static/eyecatch.png">

