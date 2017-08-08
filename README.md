# About
testcase for [PPCA 2017](https://acm.sjtu.edu.cn/wiki/PPCA_2017#.E6.9C.BA.E5.99.A8.E5.AD.A6.E4.B9.A0.E7.B3.BB.E7.BB.9F) deep learning system

# Test Description
| no |    name     | test item |
|----| ----------- | --- |
| 1  | adder       | basic computation graph |
| 2  | initializer | global initializer |
| 3  | assign      | assign op |
| 4  | context     | 'with' statement support |
| 5  | autodiff    | automatic differentiation |
| 6  | optimizer   | gradient descent optimizer |
| 7  | multilayer perceptron | relu activation |
| 8  | adam        | adam optimizer |
| 9  | CNN 0       | correctness of convolution and maxpool layer |
| 10 | CNN 1       | simple CNN |
| 11 | CNN 2       | simple CNN with dropout |

# How to run test
```bash
python run_test.py name_of_your_model
```

Since our API is the same as tensorflow, you can use tensorflow to pass all the tests
```bash
python run_test.py tensorflow
```
