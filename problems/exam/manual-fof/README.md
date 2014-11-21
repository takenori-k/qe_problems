
# Stats of input formulas

lastupdated: Fri, 21 Nov 2014 17:45:58 +0900 (JST), 2607bc1

|                  file|idx|#v|#q|atom|poly|=,<>|<,<=|prenex|abs|ratpoly|ratexp|qdeg|fdeg|stod|
|:----|--:|--:|--:|--:|--:|--:|--:|:-:|:-:|:-:|:-:|--:|--:|--:|
|hokudai1999-Bun-2-3-m | 1| 2| 1|  3| 3| 1| 2|o| | | | 3| 1| 7|
|hokudai1999-Bun-2-3-m | 2| 2| 1|  3| 3| 0| 3|o| | | | 2| 1| 5|
|hokudai1999-Bun-2-3-m | 3| 2| 1|  5| 5| 2| 3|o| | | | 2| 3|10|
|hokudai1999-Ri-3-3-m  | 1| 3| 2|  2| 2| 2| 0|o|o| |o| 2| 1| 9|
|hokudai1999-Ri-3-3-m  | 2| 2| 1|  5| 5| 0| 5| | | | | 1| 1| 6|
|hokudai1999-Ri-3-3-m  | 3| 3| 1|  3| 3| 3| 0|o|o| |o| 1| 2|10|
|hokudai2011-Ri-3-m    | 1| 3| 0|  3| 3| 3| 0|o| | | | 0| 2|19|
|hokudai2011-Ri-3-m    | 2| 5| 2|  4| 4| 4| 0|o| | | | 2| 2|43|
|kyoto1999-Bun-4-3-m   | 1| 8| 8| 17|17|17| 0|o| |o| | 4| 0|8488|
|kyoto1999-Bun-4-3-m   | 2| 8| 6| 16|16|16| 0|o| |o| | 4| 4|8484|
|kyoto1999-Ri-2-m      | 1| 6| 0|  3| 3| 1| 2|o| | |o| 0| 4|33|
|kyoto1999-Ri-6-m      | 1| 3| 1|  4| 4| 2| 2|o| |o| | 4| 1|29|
|kyushu1999-Ri-3-2-m   | 1| 4| 2|  3| 3| 2| 1|o| | | | 3| 1| 9|
|kyushu1999-Ri-3-2-m   | 2| 8| 6| 11| 9| 8| 3| | | | | 3| 1|29|
|kyushu1999-Ri-5c-1-m  | 1|15|12| 12|12|12| 0|o| | | | 2| 1|75|
|kyushu1999-Ri-5c-1-m  | 2|15|12| 12|12|12| 0|o| | | | 2| 1|75|
|nagoya1999-Ri-1-2-m   | 1| 6| 2|  2| 2| 2| 0|o| | | | 2| 2|32|
|nagoya1999-Ri-2-m     | 1| 4| 1|  2| 2| 2| 0|o| | |o|12| 1|36|
|osaka1999-Bun-2-1-m   | 1| 6| 4|  6| 6| 6| 0|o| | | | 2| 1|24|
|osaka1999-Bun-2-2-m   | 1| 6| 5|  7| 7| 6| 1|o| | | | 4| 2|45|
|tohoku1999-Ri-2-m     | 1| 4| 1|  6| 6| 5| 1| | | | | 2| 2|47|
|tohoku2009-Bun-4-m    | 1| 3| 2|  2| 2| 1| 1|o|o| |o| 2| 2|10|
|tohoku2009-Bun2-4-m   | 1| 3| 3|  4| 4| 1| 3|o| | | | 4| 0|40|
|tohoku2009-Bun2-4-m   | 2| 7| 6|  9| 9| 2| 7| | | | | 2| 4|107|
|tohoku2009-Bun2-4-m   | 3| 3| 3|  4| 4| 1| 3|o| | | | 4| 0|40|
|tohoku2009-Bun2-4-m   | 4| 3| 2|  4| 4| 0| 4|o| | | | 2| 4|40|
|tohoku2009-Ri-1-m     | 1| 3| 3|  2| 2| 2| 0|o| | | | 3| 0|15|
|tohoku2009-Ri-1-m     | 2| 3| 3|  2| 2| 0| 2|o| | | | 3| 0|15|
|tohoku2009-Ri-6-m     | 1| 5| 4|  7| 7| 4| 3|o|o| |o| 2| 1|30|
|tohoku2010-Ri-1-m     | 1| 3| 2|  3| 3| 0| 3|o| |o| | 4| 4|99|
|tokyo1999-Bun-3-m     | 1| 5| 2|  3| 3| 3| 0|o| | | | 2| 1|12|
|tokyo1999-Bun-3-m     | 2| 6| 4|  3| 3| 3| 0|o| | | | 2| 2|24|
|tokyo1999-Ri-4-m      | 1|14|11| 12|12| 4| 8| | | |o| 2| 1|85|
|tokyo1999-Ri-4-m      | 2|17|15| 16|14| 4|12| | | | | 2| 1|103|

- `file`: file name
- `idx`: index
- `#v`: number of variables
- `#q`: number of quantified variables
- `atom`: number of atomic formulas
- `poly`: number of polynomials appearing in the formula
- `=,<>`: number of atomic formulas whose form are `f=0` or `f<>0`
- `<,<=`: number of atomic formulas whose form are `f<0` or `f<=0`
- `prenex`: `o` if the formula is prenex normal form
- `abs`: `o` if the formula contains `abs()`
- `ratpoly`: `o` if the formula contains rational functions
- `ratexp`: `o` if the formula contains rational exponents
- `qdeg`: max degree of quantified variables
- `fdeg`: max degree of free variables
- `stod`: sum of total degree
