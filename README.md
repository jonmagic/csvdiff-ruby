csvdiff-ruby
============

In order to compare two csv files and get something more meaningful than normal line diffs you can choose an identifier column in your data that will be used to match rows. If no identifier column is chosen you can of course fall back to the line number as the unique identifier.

Once a row from two revisions is matched you can compare the values in every other cell in that row and show the changes in a meaningful way.

For text normal red/green comparisons are handy, but things get much more interesting when you start comparing cells with numerical values as you can show the change in value. Date and time cells could show a change in days, hours, minutes, seconds, or all of the above. If you can determine the column type more meaningful comparisons can be done.

This repository is my attempt at building a csv differ in Ruby.
