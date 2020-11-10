# 2048-unison

A [Unison](https://www.unisonweb.org/) implementation of the game [2048](https://play2048.co/) that uses the terminal as the user interface.

![Screenshot](https://i.imgur.com/1ApdWF7.png)

## Installation

First, pull down this repo into `ucm`. Here we pull the entire repo into a local namespace called `_2048`: 

```
.> pull https://github.com/samgqroberts/2048-unison _2048
```

Then, `run` `.trunk.cli.play2048`
```
.> run _2048.trunk.cli.play2048
```

## Acknowledgements

- Gabrielle Cirulli ([@gabrielecirulli](https://github.com/gabrielecirulli)) who created [the original version of the game](https://github.com/gabrielecirulli/2048).
- The contributors to [2048-cli](https://github.com/tiehuis/2048-cli), which was a very helpful reference in how to put 2048 in the terminal.
- [@atacratic](https://github.com/atacratic) who created [the one external library this application uses](https://github.com/atacratic/unison-random-mersenne) (for random number generation).
