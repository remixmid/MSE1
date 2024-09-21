## Exercises: Boolean Algebra

### Exercise 1: Numeral Systems Recap

RGBA is an extension to the (R)ed (G)reen (B)lue color model, which includes an (A)lpha channel representing the level of opacity from 0.0 to 1.0, where 0.0 is fully transparent (i.e. invisible) and 1.0 is fully opaque.
The four channels are represented by 1 byte each, often expressed in hexadecimal, where for instance #A01009FF corresponds to RGBA(160, 16, 9, 1.0), a fully opaque almost perfect red.

a. What is the maximum decimal value for any of the RGB channels?
<details>
<br>
<summary> </summary>
$255$
</details>
<br>

b. What is the hexadecimal value for an opacity of 0.5?
<details>
<br>
<summary> </summary>
$\approx 79$ or $80$
</details>
<br>

c. What is the cardinality (or the order) of the set of all possible RGB colors?
<details>
<br>
<summary> </summary>
$16^{6} = 16 777 216$
</details>
<br>

d. What is the cardinality (or the order) of the set of all possible RGBA colors, if all colors with an alpha of 0 are considered the same?
<details>
<br>
<summary> </summary>
$16^{6} \cdot (16^2-1) + 1 = 16 777 216 \cdot 255 + 1 = 4 278 190 081$
</details>
<br>

e. Express an opacity level of 0.8 in binary.
<details>
<br>
<summary> </summary>
$255 \cdot 0.8 = 204_{10} = 11001100_2$
</details>
<br>

### Exercise 2: Boolean Calculation

Calculate the following:

a. $1 \cdot \overline{1}$  
<details>
<br>
<summary> </summary>
$0$
</details>
<br>

b. $\overline{1} + \overline{0}$  
<details>
<br>
<summary> </summary>
$1$
</details>
<br>

c. $\bar{1 + 0} \cdot 1$

<details>
<br>
<summary> </summary>
$0$
</details>
<br>
