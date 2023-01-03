# REGULAR EXPRESSION

* What is Regular expression and why do I care ?

## Usage

* The simplest regex expression is just a caracter / letter
* regex matches all the characters by default anywhere inside the strings
* `^a` the carrot means it must begin with the lettre a

## Anchors

* `^a`everything that starts with the letter a => lock it to the begining
* `a$` everything that ends with the letter a => lock it at the end
* `^foot$` just the word foot
* `cat|dog` the | will combine the two together : it's the `OR` operator  
* `(cat|dog)foot` either car or dog the followed by foot
* `.` everything; any single Character e.g: `^.....$` / `^.{5}$` any strings that have 5 characters 
* `^.{5,7}$` any strings that has 5 to 7 characters 
* `^.{5,}$` anything that has 5 or more characters / `^.{,7}$` anything that has 7 or less characters 
* `^.+$` anything that has 1 or more characters / `^.*` anything that has 0 or more of that things (.) === anything at all 

## Sets

Sets are made using `[]`

* `[a]` anything that has a in it
* `[^a]` anything that doesn’t have a in it
* `^[^a]` anything that doesn’t start with a
* `[^a]$` anything that doesn’t end with a
* `[a-o]$` anything that ends with a letter a through z
