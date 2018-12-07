# Project Title

Autonomous Racing - Project Group - TU Dortmund

[![Build Status](https://travis-ci.com/Autonomous-Racing-PG/ros.package.svg?branch=master)](https://travis-ci.com/Autonomous-Racing-PG/ros.package)

## Getting Started

These instructions will get you a copy of the project up and running

### Move to ROS Workspace

```
cd ros_ws
```

### Build ROS packages

```
catkin_make
```

### Run tests

```
catkin_make run_tests
```

### Run nodes

```
source devel/setup.zsh
roslaunch dev.launch
```

### Python setup

This project uses `autopep8` for automatic code formatting.
Before you first use it, you need to install it like this:

    sudo apt-get install pip
    pip install --upgrade autopep8

## Contributing

These instructions will help you contribute code to the project.

### Git Hooks

To install the repos git hooks run
```sh
scripts/hooks/_install.sh
```

### Format C++ and Python code

```
./scripts/format/format-src.sh
```

The python code is formatted with [autopep8](https://github.com/hhatto/autopep8).
It is currently configured with the aggressive flags.
Thus, you need to review the changes it made.

## Documentation

* For general information and documentation checkout the [wiki page](https://github.com/Autonomous-Racing-PG/ros.package/wiki).
* For source code documentation checkout the auto-generated [Doxygen documentation](https://autonomous-racing-pg.github.io/ros.package/html/index.html).

## Authors

* TODO

## License

This project is licensed under the MIT and GPLv3 dual licensed - see the [MIT.LICENSE](MIT.LICENSE) and [GPLv3.LICENSE](GPLv3.LICENSE) file for details

## Acknowledgments

* TU Dortmund

