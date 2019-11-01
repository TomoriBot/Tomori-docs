Admin module
==============


**say**
-----------------
    Send your text via bot's account.

``Arguments``
~~~~~~~~~
  value: Optional[Union[:class:`text`, :class:`embed json`]]

``Returns``
~~~~~~~~~
  Your message or embed object.

Example
~~~~~~~~~
  - !say I love Minami!!!
  - !say {"title": "ぼくわ美波大好き", "color": 2802150}



**webhook**
-----------------
    Send your text via choosen webhook.

``Arguments``
~~~~~~~~~
  name: :class:`text`
  value: Optional[Union[:class:`text`, :class:`embed json`]]

``Returns``
~~~~~~~~~
  Your message or embed object.

``Aliases``
~~~~~~~~~
  - wh

Example
~~~~~~~~~
  - !wh test I love Minami!!!
  - !webhook news {"title": "ぼくわ美波大好き", "color": 2802150}



**clear**
-----------------
    Delete messages from current chat.

``Arguments``
~~~~~~~~~
  count: :class:`integer`=1
  user: Optional[Union[:class:`Mention`, :class:`Name`, :class:`ID`]]

``Aliases``
~~~~~~~~~
  - cl

Example
~~~~~~~~~
  - !cl
  - !cl 100
  - !cl 100 Naneynonn
  - !clear 373 @Naneynonn#0101
  - !clear 373 496569904527441921