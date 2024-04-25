# Zed vale extension

This extension adds Vale spelling and grammar checking to Zed.

## Installation

Go to Zed's extension manager and search for `vale`. Click install.

## Configuration

Configure Vale by creating a `.vale.ini` file in the project root.
An example would look like:

```ini
StylesPath = .github/styles
MinAlertLevel = suggestion

# Packages = Microsoft, proselint, write-good, alex, Readability, Joblint
Packages = write-good

[*.md]
BasedOnStyles = Vale, write-good
```

Synchronize all configured styles by running: `vale sync`.

## Contributing

Please see the [contributing guide](.github/CONTRIBUTING.md).

## License

Apache 2.0
