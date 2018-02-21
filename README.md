# Ice cream mining

A project undertaken to apply various data mining principles and techniques on an ice cream dataset, collected as a survey. The goal is to analyse various factors and crystallize as to which brand and flavor of ice creams would be in high demand in a given locality.

### Installation

If you're running anaconda, then there's no need to install any additional packages. Just run the following command 

```sh
$ jupyter notebook
```

and select IceCream.ipynb

else, first install virtualenv and create a new environment

```sh
$ pip install virtualenv
$ virtualenv ice_cream
```

After that's done, activate your environment

```sh
$ source ./ice_cream/bin/activate
```
Finally install the dependencies and run jupyter notebook
```sh
$ pip -r requirements.txt
$ jupyter notebook
```