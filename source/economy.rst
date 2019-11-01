Economy module
==============


**timely**
-----------------
    Get timely award.

``Returns``
~~~~~~~~~
  500 |custom| |money|.

``Cooldown``
~~~~~~~~~
  12 hours|custom|.

Example
~~~~~~~~~
  - !timely



**br**
-----------------
    Play bet-roll.

``Arguments``
~~~~~~~~~
  amount: Optional[Union[`integer`, `all`]]

``Returns``
~~~~~~~~~
  An embed message with the game result (win or lose).

``Aliases``
~~~~~~~~~
  - bet-roll

``Example``
~~~~~~~~~
  - !br
  - !br 1000
  - !bet-roll 
  - !bet-roll 373