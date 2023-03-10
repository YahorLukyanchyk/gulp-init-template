# Gulp starter template
You can use this template to init starter gulp template for your gulp project

## Template structure 
```bash
.
├── src
│   ├── assets                            # additional page files
│   │   ├── fonts                         # fonts folder
│   │   │   └── ...
│   │   └── img                           # images folder
│   │   │   └── ...
│   │   └── js                            # scripts folder
│   │   │   └── components                # folder for js components
│   │   │   │    └── component.js
│   │   │   │        └── ...
│   │   │   └── main.js                   # js file which will contain all the code 
│   │   └── scss                          # from /components/*name*.js files
│   │       ├── base
│   │       │    ├── reset.scss
│   │       │    └── ...
│   │       ├── components
│   │       │    └── ...
│   │       ├── layout                    
│   │       │    └── ...
│   │       ├── pages                     
│   │       │    └── ...
│   │       ├── ...
│   │       └── style.scss                # primary Sass file
│   │      
│   └── template                          # page template folder
│   │   ├── data
│   │   │   ├── data.json                 # .json file with data for pages
│   │   │   └── ...
│   │   ├── layouts
│   │   │   ├── default.html              # default template file (several tempaltes could be created)
│   │   │   └── ...
│   │   └── partials                      # parts for the template/page
│   │       ├── head.html
│   │       ├── header.html
│   │       ├── footer.html
│   │       └── ...
│   │    
│   └── index.html                        # main html file
│
├── gulpfile.js                           # gulp config file
└── package.json                          # contains all info about packages/project
└── README.md
```

## How to use:  
1. Download/copy repository 
2. Run 'npm i' in the terminal in your project folder
3. Run 'gulp' command in your terminal 
4. Start building your own project!

## Useful links:
- [gulp documentation](https://gulpjs.com/)
- [npm packages](https://www.npmjs.com/)

## Installed npm packages
[browser-sync](https://www.npmjs.com/package/browser-sync) 2.27.10  
[del](https://www.npmjs.com/package/del) 6.0.0  
[gulp](https://www.npmjs.com/package/gulp) 4.0.2  
[gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer) 8.0.0  
[gulp-cssbeautify](https://www.npmjs.com/package/gulp-cssbeautify) 3.0.1  
[gulp-cssnano](https://www.npmjs.com/package/gulp-cssnano) 2.1.3  
[gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin) 7.1.0  
[gulp-notify](https://www.npmjs.com/package/gulp-notify) 4.0.0  
[gulp-plumber](https://www.npmjs.com/package/gulp-plumber) 1.2.1  
[gulp-rename](https://www.npmjs.com/package/gulp-rename) 2.0.0  
[gulp-rigger](https://www.npmjs.com/package/gulp-rigger) 0.5.8  
[gulp-sass](https://www.npmjs.com/package/gulp-sass) 5.1.0  
[gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps) 3.0.0  
[gulp-strip-css-comments](https://www.npmjs.com/package/gulp-strip-css-comments) 2.0.0  
[gulp-uglify](https://www.npmjs.com/package/gulp-uglify) 3.0.2  
[gulp-webp](https://www.npmjs.com/package/gulp-webp) 4.0.1  
[gulp-babel](https://www.npmjs.com/package/gulp-babel) 8.0.0   
[panini](https://www.npmjs.com/package/panini) 1.7.2  
[sass](https://www.npmjs.com/package/sass) 1.56.1  
