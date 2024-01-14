
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