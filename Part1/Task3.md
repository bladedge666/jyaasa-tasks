a) bce , bbcde , bbbcdde , <u>`bbbbcddde`</u>

The general form: `bb{x-times}cd{x-times}e` (In regular grammar terms: `bb*cd*e`)

b) bcace , bcacacace , bcacacacacace , <u>`bcacacacacacacace`</u>

The general form: `b(ca){x-times}ca(ca){x-times}ce` (In regular grammar terms: `b(ca)*ca(ca)*ce`)


c) <u>`accdd`</u> , abcccdd , abbccccdd , abbbcccccdd , …

The general form: `ab*c*dd`
Here, I looked at the pattern to see that every term has two `d`s and one `a`. Only `b` and `c` are varying and increase by 1 in each progression. 

---
Footnote: `*` means 0 or more number of times. `{}` means a specific number of times. 