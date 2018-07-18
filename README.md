# buildyourowninternet.github.io

To build and test this website locally:  
```
sudo apt install jekyll 
jekyll s --incremental
```
Then go to https://localhost:4000 to see your changes to the site before pushing them.  

If you have ssh access to the hosting server, you can update https://buildyourowninter.net by running the following commands from your local machine after making changes to the repo,

```
jekyll build
scp -r _site/* root@buildyourowninter.net:/var/www/buildyourowninter.net/public/.
```

