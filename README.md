# Normal-probability-calculator
calculates probability from inputs {mean, standard deviation, lower bound, upper bound} using riemann sums

# Usage
compile using go compiler
```
go build Calculate.go reimann.go
```
when executed, the user is prompted with 
```
Please enter:(mean stdev x0 xn)
```
enter mean, stdev, lower bound, and upper bound seperated by spaces or newlines (or a combination of both)
acceptable entries include 
```
0 1 -1 1
```
```
64
4
58
65
```
```
90 10
100 110
```
