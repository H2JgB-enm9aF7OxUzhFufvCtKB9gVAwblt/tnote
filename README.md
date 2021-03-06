## tnote

This is my experiment and learning process for Python, github, etc. Sorry!

[![GitHub license](https://img.shields.io/pypi/l/pyzipcode-cli.svg)](https://img.shields.io/pypi/l/pyzipcode-cli.svg) [![Supported python versions](https://img.shields.io/pypi/pyversions/Django.svg)]([![PyPI](https://img.shields.io/pypi/pyversions/Django.svg)]()) [![Requirements Status](https://requires.io/github/prodicus/tnote/requirements.svg?branch=master)](https://requires.io/github/prodicus/tnote/requirements/?branch=master) [![Join the chat at https://gitter.im/prodicus/tnote](https://badges.gitter.im/prodicus/tnote.svg)](https://gitter.im/prodicus/tnote?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

```
t
	note
```

A dead simple command line note taking app built for me!

## Demo

Watch a live demo of it working here

[![asciicast](https://asciinema.org/a/35557.png)](https://asciinema.org/a/35557)

*Here's the [link to previous version](https://asciinema.org/a/35378) if you are interested!*

## Features

- **Dead simple to use**: Even your granny would be able to use it. No seriously!
- **Feature rich** Add your precious note with it's _title_ , _content_ , _tags_
- **Secure**: Encrypts your database using standard **AES-256 in CBC mode**. So even if anybody gets hand of your database file. He cannot make any sense of it. [A little demo of what I am doing using it](https://github.com/prodicus/tnote/wiki/So-you-say-it-is-encrypted-eh%3F)

**NOTE**
  _This feature is available/tested only on linux based systems. Support for other OS's coming soon!_

- **Text Highlighting is cross platform** - Supports Linux, Windows, MAC for the terminal based highlighting.
- **Searching for notes is hassle free** in `tnote`: It supports full text search for notes based on _content_, _tags_
    - The search query if found in the database will be highlighted if found. Looks pleasing to the eyes
- Ability to add and remove tags for each note.
- Adds timestamp for each note which has been added.
- Written in uncomplicated python.

Need I say more?

## Installation

```sh
$ git clone https://github.com/prodicus/tnote
$ cd tnote && pip install -r requirements.txt
```

**NOTE** 

On **linux** system, install `libsqlcipher-dev` 

```sh
$ sudo apt-get install libsqlcipher-dev
```

On **Mac OS** systems, you can install it by 

```sh
$ brew install sqlcipher
```

Fire it up! :volcano:

`$ ./tnote.py`


## Operating system support

| OS | Support status |
| --- | --- |
| Linux | :white_check_mark: Full support |
| OS X | :white_check_mark: Full support  |
| Windows | :ballot_box_with_check: encrytion of the Database for windows not yet supported |

## Contributing

This app was created in a timespan of 2 hours while learning to use [peewee (ORM)](https://github.com/coleifer/peewee). So don't be shy to make some PR's here :smile:

#### To-do
    
- [ ] Add **unit tests**. Like real quick!
- [x] Encrypt the `.db` file using **Sqlcipher**
- [ ] Add better UI using **urwid**

#### Contributers

A big shout out to all the contributers, more specifically to these guys

- [@maxwellgerber](https://github.com/maxwellgerber)
- [@BrandtM](https://github.com/BrandtM)

## Motivation

Why not!

## Issues

You can report the bugs at the [issue tracker](https://github.com/prodicus/tnote/issues)

**OR**

You can [tweet me](https://twitter.com/tasdikrahman) if you can't get it to work. In fact, you should tweet me anyway.

## License

Built with ♥ and after a lot of pizzas by [Tasdik Rahman](http://tasdikrahman.me) under [MIT License](http://prodicus.mit-license.org)

You can find a copy of the License at http://prodicus.mit-license.org/
