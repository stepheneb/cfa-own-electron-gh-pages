cfa-own-electron-gh-pages

Extract of gh-pages branch from now private repository: https://github.com/stepheneb/cfa-own-electron

```
git clone -b gh-pages --single-branch git@github.com:stepheneb/cfa-own-electron.git cfa-own-electron-gh-pages
cd cfa-own-electron-gh-pages
rm -rf .git
git init .
git remote add origin git@github.com:stepheneb/cfa-own-electron-gh-pages.git
...
git push -u origin main
```