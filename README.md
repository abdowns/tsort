# T-Sort

Sorting algorithm visualiser in the terminal

I was bored so I made this
pretty cool

## Dependencies
1. NCurses library (most linux systems already should have this)
1. A terminal
1. A computer

## Installation
`git clone https://github.com/abdowns/tsort.git`

`cd tsort`

`sudo make clean install`

To uninstall:

`sudo make clean uninstall`

## Usage

Example command (all flags are optional):

`tsort -t bubble -d 5 -n 158`

`-t` followed by algorithm choice (e.g. bubble, quick, bogo)

`-d` followed by time delay (in milliseconds)

`-n` (not reccomended for now) how many numbers to sort

Current implemented algorithms:

- Bubble Sort
- Quick Sort
- Cocktail Sort
- Insertion Sort
- Gnome Sort
- Bogo Sort