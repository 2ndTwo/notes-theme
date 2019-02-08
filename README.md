# Notes

Notes is a [Hugo](https://gohugo.io/) theme specifically created for writing and studying notes.

This project has a few goals:

* Provide features that improve retention of the material
* Make it extremely easy to add and edit notes
* Limit distracting elements or styles

## Quick Start

The easiest way to start with this theme is to create a new Hugo site and create a test note. `cd` into your favorite folder and enter the following commands.

```bash
$ hugo new site SITE_NAME
$ cd SITE_NAME/themes
$ git clone https://github.com/2ndTwo/notes-theme.git
$ cd ..
$ echo 'theme = "notes-theme"' >> config.toml
```

Your site should now be set up and configured to use the theme! Make sure to create a class before you add any notes by doing the following:

```bash
hugo new CLASS_NAME/_index.md -k class
```

And then to add notes:

```bash
hugo new CLASS_NAME/NOTE.md -k note
```

Don't have Hugo installed? Check out [this link](https://gohugo.io/getting-started/installing/).

## Configuration

TODO

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)