### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:



  def check_for_ace(self, card):
    # if statement should be ==
    if card.value = 1:
      return True
    else
      return False
   
#typo def                     ,missing coma
  dif highest_card(self, card1 card2):
  #no indentation
  if card1.value > card2.value:
    #variable name wrong
    return card
  else:
    return card2
  

#indentation wrong
def cards_total(self, cards):
  total # should be assigned to 0?
  for card in cards:
    total += card.value
    #return should be outside for loop
    return "You have a total of" + total
  
```
