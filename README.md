# buildyourowninternet.github.io

To build and test this website locally:  
```
sudo apt install jekyll 
jekyll s --incremental
```
If you have ssh access to the hosting server, you can update https://buildyourowninter.net by,

```
cd buildyourowninternet.github.io
git pull
jekyll build
cp -r _site/* /var/www/buildyourowninter.net/public/.
```

Then go to https://localhost:4000 to see your changes to the site before pushing them.  
