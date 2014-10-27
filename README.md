# harp-bootstrap

> Bootstrap is a LESS library, providing a powerful front-end framework for faster and easier web development.

## Dependencies

* [NodeJS](http://nodejs.org/) – _Server-side JavaScript runtime_
* [Harp](http://harpjs.com/) – _The static web server with built-in preprocessing_

## Install

To install Bootstrap, you can [download this repository](https://github.com/harp/bootstrap/archive/master.zip) or use the  [Component](http://component.io) package manager.

```bash
npm install -g component
component install harp/bootstrap
```

Your project will look something like this…

```
myproject/                  <-- your project root (or public dir if in framework-mode)
  |- components/            <-- harp puts components here
  |   +- harp/    <-- where this lib gets installed
  |      +- bootstrap/
  |         …
  |- main.less              <-- where you reference Bootstrap 
  +- index.jade             <-- where you reference main.css
```

## Link

Now, from within a `.less` file in your project, you can `@import` Bootstrap:

```less
@import "components/harp/bootstrap/3.0.2/less/bootstrap.less";
```

Or, just a portion of Bootstrap:

```less
@import "components/harp/bootstrap/3.0.2/less/_variables.less";
@import "components/harp/bootstrap/3.0.2/less/_mixins.less";
@import "components/harp/bootstrap/3.0.2/less/_grid.less";
```

## Resources

* [Harp documentation](http://harpjs.com/docs)
* [LESS documentation](http://lesscss.org)
* [Bootstrap documentation](http://getbootstrap.com)

## License

This component is [Bootstrap](http://github.com/twbs/bootstrap), which is Apache 2.0 licensed.
