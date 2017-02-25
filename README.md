# Pure.css Typography [`pure-typography-i`]

## Usage

### npm

```
npm install pure-typography-i 
```
Than you can link the compiled css from the `dist`folder.

## Develop

```
$ git clone https://github.com/zsim0n/pure-typography.git
$ cd pure-typography
$ npm install
$ npm start 
```

npm build scripts and live server included.


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
## References & Credit

* [Pure.css](http://purecss.io)
* [Pure.css Icons(ICONO)](https://saeedalipoor.github.io/icono/)
* [Ionic Framework (V1)](https://ionicframework.com/docs/components/#colors)

## Contribution

Thank you for taking the time to contribute! See [code of conduct](http://contributor-covenant.org) for contribution guidelines and details

## License

This project is licensed under the Apache 2.0 License - see the [License](https://choosealicense.com/licenses/apache-2.0/) for details

