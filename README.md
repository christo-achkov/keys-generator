# Keys.lol generator
This repository contains the key generator for [Keys.lol](https://keys.lol)

## Building and installing
1. install required packages with `go get`
2. build the executable with `go build`
3. include the executable in `$PATH`: `sudo cp keys-generator /usr/local/bin`

## Usage
For generating keys, run:

```bash
keys-generator btc <page number>
keys-generator eth <page number>
```

For searching by private key, run:
```bash
keys-generator btc-search <btc private key>
keys-generator eth-search <eth private key>
```

## License

This project is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
