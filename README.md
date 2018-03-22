# TN_test_Lem_in

The purpose of this series of shell scripts is to provide tests for the lem_in project.
Lem_in is a program that finds the quickest way to get n ants across a graph ([Subject here](https://www.dropbox.com/s/1wlvsos3fg2w5ju/lem-in.en.pdf?dl=0))

It tests 150+ relevant examples of invalid text inputs, as well as memory leaks using valgrind.

## Installing & running the tests

To install it, simply put the content of the TN_test_Lem_in folder in your lem_in folder, then do :

```
sh TN_test_Lem_in.sh
```
## Disclaimer

The definition of "invalid" is debatable. Make sure you check the logs.

For the valid_tests, the script checks if you return "ERROR" or not.

## Authors

* **Victor Tenneroni** - [Website](http://victor-tenneroni.com/)
* **tbailly-**
