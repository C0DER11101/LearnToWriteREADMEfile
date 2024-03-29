# $\LaTeX{}$ Mathematical symbols in Markdown file

## Power and indices

Powers are inserted using the `^` symbol(similar to $\LaTeX{}$).

`$n^2$`  gives   $n^2$


Indices are inserted using `_`.

`$2_a$` gives  $2_a$

If power or indices include more than one character, group them using curly brackets {...}.

`$b_{a-2}$` produces $b_{a-2}$

## Greater than equal to
`$\geq$` $\geq$

## Fractions

Fractions are inserted using `$$\frac{numerator}{denominator}$$`


Example:

| Example | Output |
|:-------:|:------:|
|`$$\frac{a}{3}$$`|$$\frac{a}{3}$$|
|`$$\frac{y}{\frac{3}{x}+b}$$`|$$\frac{y}{\frac{3}{x}+b}$$|

## Roots

Square root symbols are inserted using `$$\sqrt{...}$$` where `...` is replaced by the square root content. If a magnitude is required it can be added using optional square brackets `[...]`.

Example:

| Example | Output |
|:-------:|:------:|
|`$$\sqrt{y^2}$$`|$$\sqrt{y^2}$$|
|`$$\sqrt[x]{y^2}$$`|$$\sqrt[x]{y^2}$$|

## Sums and integrals

To show the summation we use `$$\sum_{lowerLimit}^upperLimit expression$$`

Example:

| Example | Output |
|:-------:|:------:|
|`$$\sum_{x=1}^3 y^z$$`|$$\sum_{x=1}^3 y^z$$|
|`$$\sum_{x=1}^{10} y^z$$`|$$\sum_{x=1}^{10} y^z$$|

To show the integral we use `$$\int_lowerBound^upperBound f(variable)$$`

Example:

| Example | Output |
|:-------:|:------:|
|`$$\int_a^b f(x)$$`|$$\int_a^b f(x)$$|
|`$$\int_a^{10} f(x)$$`|$$\int_a^{10} f(x)$$|

## Greek letters

| Code | Symbol |
|:----:|:------:|
|`$\alpha$`|$\alpha$|
|`$\beta$`|$\beta$|
|`$\delta$`|$\delta$|
|`$\Delta$`|$\Delta$|
|`$\theta$`|$\theta$|
|`$\Theta$`|$\Theta$|
|`$\mu$`|$\mu$|
|`$\pi$`|$\pi$|
|`$\Pi$`|$\Pi$|
|`$\sigma$`|$\sigma$|
|`$\Sigma$`|$\Sigma$|
|`$\phi$`|$\phi$|
|`$\psi$`|$\psi$|
|`$\Psi$`|$\Psi$|
|`$\omega$`|$\omega$|
|`$\Omega$`|$\Omega$|
|`$\lambda$`|$\lambda$|
|`$\Lambda$`|$\Lambda$|

Modulus in Markdown using $\LaTeX{}$:

$$\left\lvert4\right\rvert$$

$$(\sum_{i=1}^N {\left\lvert p_i - q_i \right\rvert}^P)^\frac{1}{P}$$

[Click here](https://stackoverflow.com/questions/37411920/how-to-write-equation-including-abs-inside-using-rmarkdown) if you want to learn how to write something within absolute symbol(| |).


**Also, an important point to remember:**

You insert the simple \| symbol using `\|`

**If you didn't understand this :point_up:, just go [here](https://stackoverflow.com/questions/23723396/how-to-show-the-pipe-symbol-in-markdown-table)**.

$Hello\ this\ is\ some\ text\ written\ in\ maths\ mode\ in\ \LaTeX{}$

$hello this is some more text$

---
