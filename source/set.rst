Set commands
==============


**language**
-----------------
    Set up language for your guild.

``Arguments``
~~~~~~~~~
  - language: Union[`english`, `russian`, `ukrainian`, `indonesian`, `german`]

``Aliases``
~~~~~~~~~
  - lang

Example
~~~~~~~~~
  - !set lang ru
  - !set lang en
  - !set language ru
  - !set language english
  - !set language indonesian



**reaction**
-----------------
    Set up role by reaction on the message.

``Arguments``
~~~~~~~~~
  - message_id: :class:`Integer`
  - emoji: Union[:class:`Emoji`, :class:`Name`, :class:`ID`, :class:`Unicode`]
  - role: Union[:class:`Mention`, :class:`Name`, :class:`ID`]

``Aliases``
~~~~~~~~~
  - r
  - react

Example
~~~~~~~~~
  - !set r 638220363951636505 <a:Tsumiki:489815657228009479> 489814446210809886
  - !set react 638220363951636505 Tsumiki @Role
  - !set reaction 638220363951636505 489815657228009479 @Role



**emoji**
-----------------
    Set up money emoji.

``Arguments``
~~~~~~~~~
  - emoji: Union[:class:`Emoji`, :class:`Name`, :class:`ID`, :class:`Unicode`]

``Aliases``
~~~~~~~~~
  - money

Example
~~~~~~~~~
  - !set emoji Tsumiki
  - !set emoji 489815657228009479
  - !set money <a:Tsumiki:489815657228009479>