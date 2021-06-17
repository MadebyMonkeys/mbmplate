# mbmplate
Basic folder setup to start with mbmCSS


## Getting started!

1. make a project folder:
```
mkdir projectName && cd projectName
```

2. Clone this repo with the git clone command:
```
git clone https://github.com/MadebyMonkeys/mbmplate.git .
```

3. Install the mbmcss modules via npm:

```
npm install sass mbmcss css-minify
```


_Optional_:
Add these lines under "scripts" in your pacakge.json

```
"dev": "sass src/sass/main.scss:src/css/mbmcss.css",
"build": "sass src/sass/main.scss:src/css/mbmcss.css && css-minify -d src/css/ -o dist/css/"
```
