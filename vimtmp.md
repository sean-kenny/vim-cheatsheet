# Vim

## Basic Movement
Command     | Effect
------------|--------------------------
`h j k l`   |Left, Right, Up, Down
`b w`       |Word back, Word forward
`ge e`      |End of word left, right
`{ }`       |Beginning of previous, next paragraph
`( )`       |Beginning of previous, next sentence
`0 gm`      |Beginning, middle of line
`^ $`       |First, last character of line
`nG ngg`    |Line _n_, default last, first
`n%`        |Percentage _n_ of the file
`%`         |Match of next brace, bracket, comment, #define
`nH nL`     |Line n from start, bottom of window
`M`         |Middle line of window

## Insertion & Replace -> Insert Mode
Command     | Effect
------------|--------------------------
`i a`       |Insert before, after cursor
`I A`       |Insert at beginning, end of line
`gI`        |Insert text in first column
`o O`       |Open new line below, above current
`rc`        |Replace character under cursor with _c_
`grc`       |Like `r` but without affecting layout
`R`         |Replace characters starting at cursor
`gR`        |Like `R` but without affecting layout
`cm`        |Change text of movement command _m_
`cc` or `S` |Change current line
`C`         |Change to end of line
`s`         |Change one character and insert
`~`         |Switch case and advance cursor
`g~m`       |Switch case of movement comment _m_
`gum gUm`   |Lowercase, Uppercase text of movement _m_
`<m >m`     |Shift left, right text of movement _m_
`n<< n>>`   |Shift _n_ lines left, right

## Deletion
Command     | Effect
------------|--------------------------
`x X`       |Delete character under, before cursor
`dm`        |Delete text of movement _m_
`dd D`      |Delete current line, to the end of the line
`J gJ`      |Join current line with next, without space
`:rd<CR>`   |Delete range _r_ lines
`:rdx<CR>`   |Delete range _r_ lines into register _x_