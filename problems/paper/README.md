
# Stats of input formulas

lastupdate: Tue, 25 Nov 2014 03:17:41 +0900 (JST), 95c8ba4

|                  file|idx|#v|#q|atom|poly|=,<>|<,<=|prenex|abs|ratpoly|ratexp|qdeg|fdeg|stod|
|:----|--:|--:|--:|--:|--:|--:|--:|:-:|:-:|:-:|:-:|--:|--:|--:|
|delinpol              | 1| 4| 1|  2| 2| 0| 2|o| | | | 3| 1|10|
|dorato97              | 1| 4| 3|  5| 5| 0| 5|o| | | | 4| 1|83|
|hong97                | 1| 2| 2|  3| 3| 0| 3|o| | | |12| 0|367|
|hong97                | 2| 3| 3|  5| 5| 0| 5|o| | | | 4| 0|226|
|hong97                | 3| 3| 3|  8| 8| 0| 8|o| | | | 4| 0|344|
|makepdq               | 1| 2| 1|  2| 2| 1| 1|o| | | | 2| 2| 6|
|makepdq               | 2| 3| 1|  2| 2| 1| 1|o| | | | 2| 2| 9|
|total                 | 7|21|14| 27|27| 2|25|7|0|0|0|31| 6|1045|

- `file`: file name
- `idx`: index
- `#v`: number of variables
- `#q`: number of quantified variables
- `atom`: number of atomic formulas
- `poly`: number of distinct polynomials appearing in the formula
- `=,<>`: number of atomic formulas of the form `f=0` or `f<>0`
- `<,<=`: number of atomic formulas of the form `f<0` or `f<=0`
- `prenex`: `o` if the formula is prenex normal form
- `abs`: `o` if the formula contains `abs()`
- `ratpoly`: `o` if the formula contains rational functions
- `ratexp`: `o` if the formula contains rational exponents
- `qdeg`: max degree of quantified variables
- `fdeg`: max degree of free variables
- `stod`: sum of total degree
