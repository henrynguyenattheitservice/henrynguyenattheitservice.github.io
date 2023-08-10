# henrynguyenattheitservice.github.io
This is the project for my website

To construct this website, I use hugo.

I maintain the content (md files) on a diffrent git repository.

I run the hugo command to generate the html files in the public directory
```
hugo -D
```

I maintain the public directory to the henrynguyenattheiservice.github.io repo.


TO-DO:
I will develop another website using reactjs, vuejs or nextjs to test out the deployment to the website if possible.

Folowing are the steps used to create the henrynguyenattheitservice.github.io.

- Create the tits website by running hugo new site <tits>
```
hugo new site tits
cd tits
git init .
git submodule  add <hugo-book-theme>
```
- Configure the config.toml to support the theme and site location
- Create the content files in the content directory
- Run hugo -D to generate the html files in the public directory
- Perform git remote push all file from the public directory
