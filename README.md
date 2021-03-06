# &lt;hello-world&gt; ![Bower Version](https://badge.fury.io/bo/hello-world-element.svg)

> Web Component example using [VanillaJS](http://vanilla-js.com/).

## Demo

[Check it live!](http://webcomponents.github.io/hello-world-element)

## Usage

1. Install the component using [Bower](http://bower.io/):

    ```sh
    $ bower install hello-world-element --save
    ```

2. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

3. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/hello-world-element/src/hello-world.html">
    ```

4. Start using it!

    ```html
    <hello-world></hello-world>
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`name`     | *string*                  | `World`             | Who do you want to say hello?

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

2. Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

3. To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt
    ```

4. To publish a new version, bump package version, create tag, commit and push.

    ```sh
    $ grunt bump       # v0.0.1
    $ grunt bump:minor # v0.1.0
    $ grunt bump:major # v1.0.0
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/webcomponents/hello-world-element/releases).

## License

[MIT License](http://webcomponentsorg.mit-license.org/) © WebComponents.org
