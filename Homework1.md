cd documents/dat8/data

1)
tail chipotle.tsv
tail chipotle.tsv

each row represents an order of chipotle. the first column is the order ID, the second column is quantity, the third column 
is the item name, the fourth is a description, and the fifth column is the price.

2) there are 1834 orders of chipotle

3)

wc -l chipotle.tsv

4623 lines

4) grep -i "chicken burrito" chipotle.tsv | wc -l 
grep -i "steak burrito" chipotle.tsv | wc -l

chicken burritos are more popular

5) grep -i 'chicken burrito' chipotle.tsv | grep -i 'black beans' | wc -l
grep -i 'chicken burrito' chipotle.tsv | grep -i 'pinto beans' | wc -l

black beans are more popular 

6) cd documents/dat8
find . -name *.?sv

7)grep -ir 'dictionary' . | wc -l
13 times




