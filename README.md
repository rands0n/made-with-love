# [&lt;made-with-love&gt;](http://rands0n.github.io/made-with-love/)

A web component showing what you did with love

## Demo

> See the [component page](http://rands0n.github.io/made-with-love).

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install made-with-love --save
```

Or [download as ZIP](https://github.com/rands0n/made-with-love/archive/master.zip).

## Usage

1.Import Web Components' polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
```

2.Import Custom Element:

```html
<link rel="import" href="bower_components/made-with-love/made-with-love.html">
```

3.Start using it!

```html
<made-with-love name="John Doe" url="http://example.com" color="#F62459"></made-with-love>
```

## Options

Attribute | Options       | Default                         | Description
---       | ---           | ---                             | ---
`name`    | *string*      | `Randson`                       | The name of user
`url`     | *string*      | `https://github.com/rands0n`  | The url of user or organization
`color`   | *string*      | `#333333`                       | The color of font

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/rands0n/made-with-love/releases).

## Credits

Built on top of [Polymer Boilerplate](https://github.com/webcomponents/polymer-boilerplate).

## License

[MIT License](./LICENSE) © Randson Oliveira
