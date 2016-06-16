# whatsapp-mimic

![](http://i.imgur.com/eTcVtNZ.png)

Add the typical "WhatsApp bar" to movies without using WhatsApp.

## Installation

1. Make sure you've installed all requirements
2. Clone this repository:
  `git clone https://github.com/frdmn/whatsapp-mimic`

## Usage

Here's a short explanation how to use `whatsapp-mimic`:

```shell
./mimic input.mov "Text to add"
```

## Contributing

1. Fork it
2. Create your feature branch: `git checkout -b feature/my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/my-new-feature`
5. Submit a pull request

## Requirements / Dependencies

* `ffmpeg` (compiled with `--enable-libfreetype`)

If you're using brew, you can pass `enable-libfreetype` while installing:

```shell
brew install ffmpeg --with-freetype
```

## Version

0.0.1

## License

[MIT](LICENSE)
