# QMK config for Ferris Bling using Lafayette layout

```
/!\ This project is not yet tested.
```

Lafayette layout want to provide a great experience for those who write in
english, french and do some devs.

See projects:
https://qwerty-lafayette.org
https://ergol.org/

## 0️⃣ QWERTY Lafayette (layer 0)
```
  ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓ ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓
  ┃ Q   │ W   │ E   │ R   │ T   ┃ ┃ Y   │ U   │ I   │ O   │ P   ┃
  ┃ q   │ w   │ e   │ r   │ t   ┃ ┃ y   │ u   │ i   │ o   │ p   ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ A   │ S   │ D   │ F   │ G   ┃ ┃ H   │ J   │ K   │ L   │ ¨   ┃
  ┃ a   │ s   │ d   │ f   │ g   ┃ ┃ h   │ j   │ k   │ l   │ ★   ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ Z   │ X   │ C   │ V   │ B   ┃ ┃ N   │ M   │ ;   │ :   │ ?   ┃
  ┃ z   │ x   │ c   │ v   │ b   ┃ ┃ n   │ m   │ ,   │ .   │ /   ┃
  ┗━━━━━┷━━━━━┷━━━━━╅─────┼─────┨ ┠─────┼─────╆━━━━━┷━━━━━┷━━━━━┛
                    ┃ ⇧   │ 2️⃣   ┃ ┃ 3️⃣   │ ↵   ┃
                    ┃     │ ␣   ┃ ┃ ⌫   │     ┃
                    ┗━━━━━┷━━━━━┛ ┗━━━━━┷━━━━━┛
```
## 1️⃣ [★] QWERTY Lafayette accents and diacritics (layer 1) 
```
  ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓ ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓
  ┃ Æ   │ É   │ È   │ Ê   │ “   ┃ ┃ ”   │ Ù   │ Î   │ Œ   │ Ô   ┃
  ┃ æ   │ é   │ è   │ ê   │ «   ┃ ┃ »   │ ù   │ î   │ œ   │ ô   ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ À   │ ẞ   │ ±   │ ¡   │ –   ┃ ┃ °   │ Û   │ ¶   │ §   │ `   ┃
  ┃ à   │ ß   │ ≠   │ ¬   │ —   ┃ ┃     │ û   │     │     │     ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ Â   │ ¤   │ Ç   │ ¢   │ ¥   ┃ ┃ Ñ   │ º   │ •   │ …   │ ¿   ┃
  ┃ â   │     │ ç   │ £   │     ┃ ┃ ñ   │ µ   │ ·   │     │ ÷   ┃
  ┗━━━━━┷━━━━━┷━━━━━╅─────┼─────┨ ┠─────┼─────╆━━━━━┷━━━━━┷━━━━━┛
                    ┃     │ ’   ┃ ┃ ‰   │     ┃
                    ┃     │     ┃ ┃ €   │     ┃
                    ┗━━━━━┷━━━━━┛ ┗━━━━━┷━━━━━┛
```
## 2️⃣ Numbers and mods (layer 2)
```
  ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓ ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓
  ┃UNDO │ CUT │COPY │PASTE│ ESC ┃ ┃ DEL │ HOME│ END │ INS │REDO ┃
  ┃     │     │     │     │     ┃ ┃     │     │     │     │     ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ 1   │ 2   │ 3   │ 4   │ 5   ┃ ┃ 6   │ 7   │ 8   │ 9   │ 0   ┃
  ┃     │     │     │     │     ┃ ┃     │     │     │     │     ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ !   │ @   │ #   │ $   │ %   ┃ ┃ ^   │ &   │ *   │ (   │ )   ┃
  ┃     │     │     │     │     ┃ ┃     │     │     │     │     ┃
  ┗━━━━━┷━━━━━┷━━━━━╅─────┼─────┨ ┠─────┼─────╆━━━━━┷━━━━━┷━━━━━┛
                    ┃ ⇧   │     ┃ ┃ ❖   │ ⎇   ┃
                    ┃     │     ┃ ┃     │     ┃
                    ┗━━━━━┷━━━━━┛ ┗━━━━━┷━━━━━┛
```
## 3️⃣ Alt-Gr (layer 3)
```
  ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓ ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓
  ┃ 4️⃣   │ [   │ ]   │ $   │ %   ┃ ┃ ^   │ &   │ *   │ '   │ 0️⃣   ┃
  ┃     │     │     │     │     ┃ ┃     │     │     │     │     ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ {   │ (   │ )   │ }   │ =   ┃ ┃ +   │ -   │ <   │ >   │ "   ┃
  ┃     │     │     │     │     ┃ ┃     │     │     │     │     ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ ~   │ `   │ |   │ _   │ /   ┃ ┃ \   │ @   │ #   │ !   │ ?   ┃
  ┃     │     │     │     │     ┃ ┃     │     │     │     │     ┃
  ┗━━━━━┷━━━━━┷━━━━━╅─────┼─────┨ ┠─────┼─────╆━━━━━┷━━━━━┷━━━━━┛
                    ┃LOCK │TERM ┃ ┃     │SIGQT┃
                    ┃     │     ┃ ┃     │     ┃
                    ┗━━━━━┷━━━━━┛ ┗━━━━━┷━━━━━┛
```
## 4️⃣ ERGO-L (layer 4)
```
  ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓ ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓
  ┃ Q   │ G   │ O   │ W   │ K   ┃ ┃ B   │ M   │ ¨   │ L   │ F   ┃
  ┃ q   │ g   │ o   │ w   │ k   ┃ ┃ b   │ m   │ ★   │ l   │ f   ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ A   │ S   │ E   │ T   │ D   ┃ ┃ H   │ N   │ I   │ R   │ U   ┃
  ┃ a   │ s   │ e   │ t   │ d   ┃ ┃ h   │ n   │ i   │ r   │ u   ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ Z   │ X   │ ?   │ C   │ V   ┃ ┃ J   │ P   │ ;   │ :   │ Y   ┃
  ┃ z   │ x   │ -   │ c   │ v   ┃ ┃ j   │ p   │ ,   │ .   │ y   ┃
  ┗━━━━━┷━━━━━┷━━━━━╅─────┼─────┨ ┠─────┼─────╆━━━━━┷━━━━━┷━━━━━┛
                    ┃     │ 2️⃣   ┃ ┃ 3️⃣   │     ┃
                    ┃ ⇧   │ ␣   ┃ ┃ ⌫   │ ↵   ┃
                    ┗━━━━━┷━━━━━┛ ┗━━━━━┷━━━━━┛
```
## 5️⃣ [★] ERGO-L accents and diacritics (layer 5)
```
  ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓ ┏━━━━━┯━━━━━┯━━━━━┯━━━━━┯━━━━━┓
  ┃ Æ   │ ¡   │ Œ   │ Ô   │ “   ┃ ┃ ”   │ º   │ `   │ ¢   │ ¥   ┃
  ┃ æ   │ ¬   │ œ   │ ô   │ «   ┃ ┃ »   │ µ   │     │ £   │     ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ À   │ É   │ È   │ Ê   │ ±   ┃ ┃ ¤   │ Ñ   │ Î   │ Û   │ Ù   ┃
  ┃ à   │ é   │ è   │ ê   │ ≠   ┃ ┃     │ ñ   │ î   │ û   │ ù   ┃
  ┠─────┼─────┼─────┼─────┼─────┨ ┠─────┼─────┼─────┼─────┼─────┨
  ┃ Â   │ ẞ   │ –   │ Ç   │ §   ┃ ┃ ¶   │ °   │ •   │ …   │ ¿   ┃
  ┃ â   │ ß   │ —   │ ç   │     ┃ ┃     │     │ ·   │     │ ÷   ┃
  ┗━━━━━┷━━━━━┷━━━━━╅─────┼─────┨ ┠─────┼─────╆━━━━━┷━━━━━┷━━━━━┛
                    ┃     │ ’   ┃ ┃ ‰   │     ┃
                    ┃     │     ┃ ┃ €   │     ┃
                    ┗━━━━━┷━━━━━┛ ┗━━━━━┷━━━━━┛
```

# Troubleshoot and test
Before pushing and saw error you can build localy by setup zmk:
https://zmk.dev/docs/development/setup

Then you can run by using these command:
```
qmk compile -kb ferris/0_2/bling -km lafayette
```
