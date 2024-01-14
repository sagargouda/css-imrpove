1. SASS = sass is css preprocessor , an extension of css that adds power and elegance to basic language

2. sass code is compiled into css code using sass compiler

3.sass is used for reusablity 4. 4. sass gives features like variable , nesting , opeartors , partails and imports , mixins(reusable code) , function , extends(inheritance)

4. we use scss syntax which is similar synatx

5.install sass locally

i) npm install -g sass or npm install node-sass --save-dev (dev dependcies)
ii) sass --version
iii) sass index.scss index.css
iv) after this make sure you icluded index.css in your link tag in html
v) that's it

=> npm init = intializes a project we get a package.json file

=> we need package.json because i can share it and you can recreate node modules by installing them by using npm install

=> wiritng scripts for sass
"compile:sass": "node-sass sass/main.scss css/index.css"

rendering = npm run compile:sass

=> how to keep watching sass file , just add -w flag in script
ex =
"compile:sass": "node-sass Natours/starter/sass/main.scss Natours/starter/css/style.css -w"

=> automatic reloading using npm package
which is live-server
npm install live-server -g

=> in one temrinal write live-server , in another use sass
