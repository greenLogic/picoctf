# The Numbers

This challenge is a visual one! Since it is cryptographical, we may assume it is mathematical too!

![The Numbers](./the_numbers.png)

It is an introductory challenge. Let's take a look and note whatever we notice:

## Information 

1. All are positive numbers
2. The maximum number is 21 and the minimum is 1
3. There are an opening curly braced and after certain number (of numbers?) a closing bracket

## Assumptions

1. The numbers represent letters
2. The curly brackets contains our flag
3. It follows the template for picoCTF flags

The template looks like this:

`picoCTF{Theflagishereinsidewhereelsecoulditbe}`

## Replacements

picoCTF is the string before the flag. You can read the annexed table of the english alphabet letters and their indices.

But let's do it one by one, because is helpful to be accustomed to memorize  them.

```json
20 => T
8 => H
5 => E
14 => N
21 => U
13 => M
2 => B
18 => R
19 => S
15 => O
```

Well, we already have at hand what is needed, we just put them in their places:

```json
picoCTF{THENUMBERSMASON}
```

And that's all. I try to avoid giving the answers away, but, in cases like this, that you followed the steps (I hope so!) it's ok, I think.

## Annex

| Letter | Index |
| :----: | :---: |
|   A    |   1   |
|   B    |   2   |
|   C    |   3   |
|   D    |   4   |
|   E    |   5   |
|   F    |   6   |
|   G    |   7   |
|   H    |   8   |
|   I    |   9   |
|   J    |  10   |
|   K    |  11   |
|   L    |  12   |
|   M    |  13   |
|   N    |  14   |
|   O    |  15   |
|   P    |  16   |
|   Q    |  17   |
|   R    |  18   |
|   S    |  19   |
|   T    |  20   |
|   U    |  21   |
|   V    |  22   |
|   W    |  23   |
|   X    |  24   |
|   Y    |  25   |
|   Z    |  26   |
