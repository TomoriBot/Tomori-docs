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
  12 hours |custom|.

Example
~~~~~~~~~
  - !timely



**work**
-----------------
    Goes to a work.

``Returns``
~~~~~~~~~
  50 |custom| |money| after 30 |custom| minutes.

Example
~~~~~~~~~
  - !work



**br**
-----------------
    Play bet-roll.

``Arguments``
~~~~~~~~~
  amount: Optional[Union[:class:`integer`, :class:`all`]]

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



**cash**
-----------------
    Gets user's balance.

``Arguments``
~~~~~~~~~
  user: Optional[Union[:class:`Mention`, :class:`Name`, :class:`ID`]]

``Returns``
~~~~~~~~~
  User's balance.

``Aliases``
~~~~~~~~~
  - $
  - balance

``Example``
~~~~~~~~~
  - !$
  - !$ Naneynonn
  - !cash @Naneynonn#0101
  - !balance 496569904527441921



**gift**
-----------------
    Get money from.. nothing.

``Permissions``
~~~~~~~~~
  - :class:`Administrator` or :class:`Owner`

``Arguments``
~~~~~~~~~
  amount: :class:`integer`

``Returns``
~~~~~~~~~
  Updates user's balance with that amount of |money|.

``Aliases``
~~~~~~~~~
  - pay

``Example``
~~~~~~~~~
  - !gift 373
  - !pay 373