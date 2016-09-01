# snapchat-mimic

![](http://i.imgur.com/eTcVtNZ.png)

Add a Snapchat overflay to movies without using Snapchat, just using `ffmpeg` and Bash.

## Installation

1. Make sure you've installed all requirements
2. Clone this repository:
  `git clone https://github.com/frdmn/snapchat-mimic`

## Usage

Here's a short explanation how to use `snapchat-mimic`:

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

If you're using brew, you can pass `--with-freetype` while installing:

```shell
brew install ffmpeg --with-freetype
```

## Version

1.0.0

## License

[MIT](LICENSE)
