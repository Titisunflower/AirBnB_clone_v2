[![MasterHead](https://camo.githubusercontent.com/d8a348e1fceb92d45fa8981ac42a6223e454acefe89750896e80fd1287cab92b/68747470733a2f2f7777772e706e676974656d2e636f6d2f70696d67732f6d2f3133322d313332323132355f7472616e73706172656e742d6261636b67726f756e642d616972626e622d6c6f676f2d68642d706e672d646f776e6c6f61642e706e67header.gif)]
## Description

Project attempts to clone the the AirBnB application and website, including the database, storage, RESTful API, Web Framework, and Front End.

* __Environment:__ Ubuntu 14.04 LTS
* __python version:__ Python 3.4.3
* __style:__ PEP 8 (v. 1.7.0)

## Testing

This project uses python library, `unittest` to run tests on all python files.  All unittests are in the `./tests` directory with the command:

* `python3 -m unittest discover -v ./tests/`

This bash script executes all unittests, checks `pep8` style, and clears the storage file, `file.json`

```
$ ./dev/init_test.sh
```

### Interactive Tests

This project uses python library, `cmd` to run tests in an interactive command line interface.  To begin tests with the CLI, run this script:

```
$ ./console.py
```

## Authors

* Jerrica Jackson, [@Jerrica1](https://github.com/Jerrica1)
* Henriette Uwizeyimana, [@Titisunflower](https://github.com/Titisunflower)

## License

Public Domain, no copyright protection
