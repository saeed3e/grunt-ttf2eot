# grunt-ttf2eot

Grunt task to create a EOT font from a TTF font.

## Getting Started
This plugin requires Grunt `~0.4.1`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out
 the [Getting Started](http://gruntjs.com/getting-started) guide, as it
 explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as
 well as install and use Grunt plugins. Once you're familiar with that process,
 you may install this plugin with this command:

```shell
npm install grunt-ttf2eot --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile
 with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-ttf2eot');
```

## The "ttf2eot" task

### Overview
In your project's Gruntfile, add a section named `ttf2eot` to the data
 object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  ttf2eot: {
    your_target: {
      // Target-specific file lists go here.
    }
  }
})
```

### Options

#### src
Type: `string`

SVG fonts to convert. Wildcards are supported.

#### dest
Type: `string`

Directory in wich to save the converted font.

### Example

```js
grunt.initConfig({
  ttf2eot: {
   default: {
     src: 'fonts/*.ttf',
     dest: 'fonts/'
   }
  }
})
```

### Contributing / Issues

Please submit TTF to EOT related issues to the
 [ttf2eot project](https://github.com/fontello/ttf2eot)
 on wich grunt-ttf2eot is built.

This repository issues is only for grunt and grunt tasks related issues.

You may want to contribute to this project, pull requests are welcome if you
 accept to publish under the MIT licence.
