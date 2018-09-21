Instructions on how to install the necessary programs to run this project.
1. Initiate the Node Package Manager for in the project's root directory by typing "npm init" in your terminal.
2. Install sass by typing "npm install sass".
3. Install bootstrap by typing "npm install bootstrap".
4. If you would link to have browser sync installed, then type "npm install browser-sync".
5. After installing sass, bootstrap and browser sync, we will need to convert sass to css and sass converted into bootstrap.
6. To convert sass to css and also use sass to convert to bootstrap, we will need to use three files. These files are input.scss, main.scss and output.css.
We will be using input.scss for css coding, main.scss for bootstrap overwriting and we will use output.css to show the conversions.
7. We will import input.scss and the bootstrap directory into main.scss. To do this type
"@import "node_modules/bootstrap/scss/bootstrap" and @import "input.scss" " into main.scss. Make sure that the imports are below your code for main.scss to overwrite the bootstrap code.
8. To make sass watch for changes; write in your terminal "sass --watch main.scss:output.css" make sure that there is a link for output.css in your index.html.
9. To see your changes on your html automatically, first type cmd+t to create another terminal window and type "../node_modules/.bin/browser-sync start --server --files "output.css".
10. Write some css code in input.scss or bootstrap code in main.scss and see if the changes show up in your html. 
