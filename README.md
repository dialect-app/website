# Dialect's Website


## Development

The only dependency to build the website is the [Hugo](https://gohugo.io/) static site generator extended edition.

See the [installation instructions](https://gohugo.io/installation/).

```sh
sudo dnf install hugo  # Fedora
```

To start the hugo live server run:

```sh
hugo server
```

## Building

To build a copy of the website to the `/public` folder run:

```sh
hugo -D
```

## License

The code of this website is licensed under the [MIT license](https://github.com/dialect-app/website/blob/main/LICENSE).

The content of the website is licensed under the [CC BY-SA 4.0 license](http://creativecommons.org/licenses/by-sa/4.0/).
