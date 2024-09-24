# simple-numpy-stacker-plugin

This is a plugin for Stacker, enabling basic operations with numpy to be used within Stacker.

## Installation

- 1. Download Stacker
~~~bash
git clone git@github.com:remokasu/stacker.git
~~~

- 2. Download this plugin
```bash
$ clone git@github.com:remokasu/simple-numpy-stacker-plugin.git
```

- 3. Place this plugin in the Stacker's plugin directory
```bash
$ cp -r simple-numpy-stacker-plugin/plugins/ stacker/stacker/
```

- 4. Install Stacker
```bash
$ cd stacker
$ pip install .
```

- 4.1 If an older version of Stacker is already installed, uninstall it before re-installing
```bash
$ pip uninstall pystacker
$ pip cache purge
$ rm -rf build dist *.egg-info
$ pip install .
```

- 4.2 Alternatively, place this plugin in the current directory when launching Stacker
```bash
$ cd simple-numpy-stacker-plugin
$ stacker
```

## Features

The following operations can be performed using calculations with numpy.


### Basic Operators

| Operator | Description                                           |
|----------|-------------------------------------------------------|
| +        | Add                                                   |
| -        | Subtract                                              |
| *        | Multiply                                              |
| .*       | Element-wise Multiplication                           |
| /        | Divide                                                |
| ./       | Element-wise Division                                 |
| \\       | Left Division                                         |
| .\\      | Element-wise Left Division                            |
| ^        | Power                                                 |
| .^       | Element-wise Power                                    |
| or       | Logical OR                                            |
| and      | Logical AND                                           |
| not      | Logical NOT                                           |
| xor      | Logical XOR                                           |
| ==       | Equality                                              |
| '        | Transpose                                             |
| dot      | Dot Product                                           |
| inv      | Inverse                                               |
| det      | Determinant                                           |
| rank     | Rank                                                  |
| trace    | Trace                                                 |
| ones     | Ones                                                  |
| zeros    | Zeros                                                 |
| diag     | Diagonal                                              |
| all      | All                                                   |
| any      | Any                                                   |


### Math Operator

| Operator | Description                                           |
|----------|-------------------------------------------------------|
| abs      | Absolute value                                        |
| exp      | Exponential                                           |
| log      | Natural logarithm                                     |
| log10    | Common logarithm (base 10)                            |
| log2     | Logarithm base 2                                      |
| sin      | Sine                                                  |
| cos      | Cosine                                                |
| tan      | Tangent                                               |
| asin     | Arcsine                                               |
| acos     | Arccosine                                             |
| atan     | Arctangent                                            |
| sinh     | Hyperbolic sine                                       |
| cosh     | Hyperbolic cosine                                     |
| tanh     | Hyperbolic tangent                                    |
| asinh    | Inverse hyperbolic sine                               |
| acosh    | Inverse hyperbolic cosine                             |
| atanh    | Inverse hyperbolic tangent                            |
| sqrt     | Square root                                           |
| ceil     | Ceiling                                               |
| floor    | Floor                                                 |
| round    | Round                                                 |
| roundn   | Round to specified decimal places                     |
| float    | Convert to floating-point number                      |
| int      | Convert to integer                                    |
| gcd      | Greatest common divisor                               |
| !        | Factorial                                             |
| radians  | Convert degrees to radians                            |
| random   | Generate a random floating-point number between 0 and 1|
| randint  | Generate a random integer within a specified range    |
| uniform  | Generate a random floating-point number within a specified range |
