# equality-elimination-for-ITCP(GAP)
# Introduction

The function symCHM of ITCP treats the problem ![equation](https://latex.codecogs.com/svg.latex?%5Ctext%7BProj%7D_%7B%5Cboldsymbol%7Bh%7D_p%7D%28%5CGamma_N%5Ccap%20%5Cmathcal%7BL%7D_%7B%5Cmathsf%7BA%7D%7D%29) as a polytope projection under the assumption that the projected region is full-dimensional. The full-dimensionality won't be satisfied if equality exists among the dimensions indexed by ![equation](https://latex.codecogs.com/svg.latex?%5Cboldsymbol%7Bh%7D_p). You can find in this folder a GAP versin equality elimination function that is capable of removing all the equalities in ![equation](https://latex.codecogs.com/gif.latex?%5CGamma_%7BN%7D%20%5Ccap%5Cmathcal%7BL%7D_%7B%5Cmathsf%7BA%7D%7D) to get a full-dimensional polytope.


## Usage

```GAP
ncinstance := [[[[3,4],[3,4,5]],[[2,3],[2,3,4]]],3,6];
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
