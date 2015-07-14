# Roman Numerals

![roman numeral visual](https://s3-us-west-2.amazonaws.com/web-dev-readme-photos/js-vowels/roman_numerals.jpg)

## Background

The Romans were a clever bunch. They conquered most of Europe and ruled it for hundreds of years. They invented concrete and straight roads and even bikinis. One thing they never discovered though was the number zero. This made writing and dating extensive histories of their exploits slightly more challenging, but the system of numbers they came up with is still in use today. For example the BBC uses Roman numerals to date their programmes.

The Romans wrote numbers using letters - I, V, X, L, C, D, M. (notice these letters have lots of straight lines and are hence easy to hack into stone tablets).

```
 1  => I
 2  => II
 3  => III
 4  => IV
 5  => V
 6  => VI
 7  => VII
 8  => VIII
 9  => IX
10  => X
11  => XI
12  => XII
13  => XIII
14  => XIV
15  => XV
16  => XVI

etc.
```

There is no need to be able to convert numbers larger than about 3000. (The Romans themselves didn't tend to go any higher)

Wikipedia says: Modern Roman numerals ... are written by expressing each digit separately starting with the left most digit and skipping any digit with a value of zero.

To see this in practice, consider the example of 1990.

In Roman numerals 1990 is MCMXC:

```
1000 => M
900  => CM
90   => XC
```

2008 is written as MMVIII:

```
2000 => MM
8    => VIII
```

See also: [Roman Number System](http://www.novaroma.org/via_romana/numbers.html)

## Instructions

Review the `toRoman.js` file inside the `lib` directory, and then the `toRoman.spec.js` file inside the `spec` directory. Review each of the tests, and then start implementing your solutions to make each test pass in `toRoman.js`.

Run the testing suite to get started.

## Resources

* [Roman Number System](http://www.novaroma.org/via_romana/numbers.html)
* [Number Chart](http://literacy.kent.edu/Minigrants/Cinci/romanchart.htm)
