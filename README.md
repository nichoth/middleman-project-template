###### Help make the world a better place, use [EditorConfig](http://editorconfig.org/)

See the [Wiki](https://github.com/fellswoop/middleman-project-template/wiki)


## Image slider and grid components

    $ rake preview
    $ open http://0.0.0.0:4567/component-demo

The slider is made with flexslider, grid is with bootstrap.

Both take `url` and `imgs` fields in the `section` part of `data/pages.json`. If the `url` field is not defined, the template will default to the `images_path` variable.

### Raodmap

* add image optimization to build process (scale, compress, inline?)
* Find the best way to include the Javascript for flexslider. It is being bundles with project wide JS, should be local to component.
* test slider on small screens

