# Pure.css Typography 

A tiny Typography extension for Pure.css. Inspied by Ionic Framework's typography

## Usage

```
$ git clone
$ cd pure-typography
$ npm install
$ npm build:scss
```
You can get the minified CSS with source-map  from the  `dist/css/` folder.

Building SCSS.
```
package.json
{
...
    "autoprefixer": "postcss -u autoprefixer -r dist/css/*.css",
    "scss": "node-sass --source-map true --output-style compressed -o dist/css src/scss",
    "build:scss": "npm run scss && npm run autoprefixer",
...
    "devDependencies": {
        ...
        "autoprefixer": "^6.7.3",
        "node-sass": "^4.5.0",
        "postcss": "^5.2.14",
        "postcss-cli": "^3.0.0-beta",
        ...
    }
}
```

## Contribution

Thank you for taking the time to contribute! See [code of conduct](http://contributor-covenant.org) for contribution guidelines and details

## License

This project is licensed under the Apache 2.0 License - see the [License](https://choosealicense.com/licenses/apache-2.0/) for details
# pure-typography
Typography extension for Pure.css


         <h1>References</h1>  
        <ul>
            <li><a href="http://purecss.io" target="_blank">Pure.css</a></li>
            <li><a href="https://ionicframework.com/docs/components/#colors" target="_blank">Ionic V1</li>
            <li><a href="https://saeedalipoor.github.io/icono/" target="_blank">ICONO - Pure.css Icons</a></li>
        </ul>
        
        </div>