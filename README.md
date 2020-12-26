# Python-Functions
The documentation of the interesting python functions or tips I learnt

# set(iterable)
set() method is used to convert any of the iterable to sequence of iterable elements with distinct elements, commonly called Set. 

lis1 = [ 3, 4, 1, 4, 5 ]

set(lis1)

output:

{1, 3, 4, 5}

# all()
The all() function returns True if all items in an iterable are true, otherwise it returns False. If the iterable object is empty, the all() function also returns True.

def flush(hand):
    "Return True if all the cards have the same suit."
    suit = [s for r,s in hand]
    return all(s == suit[0] for s in suit) # check if each element in the list is equal to the first element
