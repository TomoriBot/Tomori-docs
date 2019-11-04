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
  - amount: Optional[Union[:class:`integer`, :class:`all`]]

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



**slots**
-----------------
    Play a slot machine.

``Arguments``
~~~~~~~~~
  - amount: Optional[Union[:class:`integer`, :class:`all`]]

``Returns``
~~~~~~~~~
  An embed message with the game result (win or lose).

``Aliases``
~~~~~~~~~
  - slot

``Example``
~~~~~~~~~
  - !slot
  - !slot 1000
  - !slots 
  - !slots 373



**cash**
-----------------
    Gets user's balance.

``Arguments``
~~~~~~~~~
  - user: Optional[Union[:class:`Mention`, :class:`Name`, :class:`ID`]]

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



**give**
-----------------
    Send |money| to another user.

``Arguments``
~~~~~~~~~
  - user: Union[:class:`Mention`, :class:`Name`, :class:`ID`]
  - amount: Optional[Union[:class:`integer`, :class:`all`]]

``Returns``
~~~~~~~~~
  Your |money| will move to that user.

``Aliases``
~~~~~~~~~
  - send

``Example``
~~~~~~~~~
  - !send Naneynonn
  - !send @Naneynonn#0101 373
  - !send 496569904527441921 all
  - !give Naneynonn
  - !give @Naneynonn#0101 373
  - !give 496569904527441921 all



**gift**
-----------------
    Get |money| from.. nothing.

``Permissions``
~~~~~~~~~
  - :class:`Administrator` or :class:`Owner`

``Arguments``
~~~~~~~~~
  - amount: :class:`integer`

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



**take**
-----------------
    Take |money| from user.

``Permissions``
~~~~~~~~~
  - :class:`Administrator` or :class:`Owner`

``Arguments``
~~~~~~~~~
  - user: Union[:class:`Mention`, :class:`Name`, :class:`ID`]
  - amount: Optional[Union[:class:`integer`, :class:`all`]]

``Returns``
~~~~~~~~~
  Takes that amount of user's |money|.

``Example``
~~~~~~~~~
  - !take Naneynonn
  - !take @Naneynonn#0101 373
  - !take 496569904527441921 all



**shop**
-----------------
    Shows roles shop.

``Arguments``
~~~~~~~~~
  - page: :class:`integer`=1

``Returns``
~~~~~~~~~
  An embed message with selected page of roles shop.

``Example``
~~~~~~~~~
  - !shop
  - !shop 3



**buy**
-----------------
    Buy role from roles shop.

``Arguments``
~~~~~~~~~
  - role: Union[:class:`Mention`, :class:`Name`, :class:`ID`, :class:`number in shop`]

``Returns``
~~~~~~~~~
  You will receive that role from shop.

``Example``
~~~~~~~~~
  - !buy 3
  - !buy Role
  - !buy @Role
  - !buy 489814446210809886