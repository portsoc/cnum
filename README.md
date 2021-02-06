# Cistercian Numerals
This [one-page app](https://portsoc.github.io/cnum/) recreates [Cistercian numberals](https://en.wikipedia.org/wiki/Cistercian_numerals) for numbers between 0 and 9999.

# Stages

## Stage 0
* Blank web page

## Stage 1
* add SVG soc
* Dimensions 600x600
* Single line
* Zero (!)

## Stage 2
* Aim: Easier coordinates
* Add a viewbox (x y w h)
* GOOD path changes to start at 0,0

## Stage 3
* Aim: Centre line starts at 0,0
* Change coords
* halve viewbox to allow us to use 2x3 grid

## Stage 4
* Aim: fix cliping
* Solution: adjust viewbox by half the width of the page

## Stage 5
* Aim: Simplify drawing
* Separate the styles

## Stage 6
* Aim : Draw 1
* Add second line

## Stage 7
* Aim : Make draing fit!
* adjust viewbox

## Stage 8
* Aim : Draw 2
* Move second line

## Stage 9
* Aim : Draw 9
* Longer path
* add stroke-linejoin

## Stage 10
* Aim: Re-usable drawing components
* use <defs>
* add <use> with href
* Make joins pretty

## Stage 11
* Aim: make ALL the number shapes

## Stage 12
* Aim: prepare for user input
* Add input box
* autofocus
* type min max
* placeholder
* value
* Style it (use grid for body)

## Stage 13
* Aim: react to input
* Add Script
* Add input event listener
* Report on requested number

## Stage 14
* Aim: Changing 0-9
* Add an ID to the use
* use the script to change its href
* breaks on numbers above 9.

## Stage 15
* Aim: prepare for larger numbers
* Add placeholders
* Flip image components

## Stage 16
* Aim: make all numbers work
* reverse the string by converting to an array
* loop over the elements in the array

## Stage 17
* Prettify and UX








