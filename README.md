# inetum-bootstrap

![inetum](doc/inetum.png)

[inetum.world](https://inetum.world) boostrap theme.

## Examples

See [doc/index.html](doc/index.html) for some examples 

## Usage

### CSS

You can directly download the css from [dist/](dist/)

### CDN

Use [jsdelivr](https://www.jsdelivr.com/package/npm/inetum-bootstrap?path=dist%2Fcss)

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/inetum-bootstrap@4.5.3-rc1/dist/css/inetum.min.js" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>

### NPM and Sass

    npm install --save inetum-bootstrap@latest

Then follow bootstrap tutorials:
https://getbootstrap.com/docs/4.5/getting-started/webpack/#importing-precompiled-sass

Then include the sass to your project

    @import "custom";
    @import "~inetum-bootstrap/scss/inetum";

## Version

Version follow bootstrap versioning + an additional pre-release identifier as describe in [Semantic Versioning](https://semver.org/#spec-item-9)

| inetnum-bootstrap | boostrap      |
|:-----------------:| ------------- |
| 4.5.3-rc1         | ^4.5.3        |
| 4.5.3-rc2         | ^4.5.3        |
| 4.6.0-rc1         | ^4.6.0        |

etc.

## Colors

![colors](doc/colors.jpg)

## Credits

Inspired from:
- https://bootswatch.com/
- https://pikock.github.io/bootstrap-magic/
