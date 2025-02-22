# topsis python package
a python package to choose the best alternative from a finite set of decision alternatives using TOPSIS.

## overview
the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) library provides an implementation of the TOPSIS decision-making method. this technique is used to rank alternatives based on multiple criteria by comparing their distance from an ideal best and an ideal worst solution.

## features
<ul>
  <li>normalize decision matrices</li>
  <li>apply weights and impacts to criteria</li>
  <li>calculate performance scores and rankings</li>
</ul>

## usage
format: ```python 102203883.py <input_file> <weights> <impacts> <output_file>``` <br>
example: ```python 102203883.py 102203883-data.csv "1,1,1,1,1" "+,-,+,+,+" 102203883-result.csv```
