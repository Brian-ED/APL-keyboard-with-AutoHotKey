# APL keyboard with AutoHotKey
 The modification keys are alt and shift. This is only supposed to work on danish keyboard but AutoHotKey is usually simple enough to read and change to your liking.
Keyboard layout: (github breaks it)
```
┌────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬─────────┐
│    │  ⌶ │  ⍫ │  ⍒ │  ⍋ │  ⌽ │  ⍉ │  ⊖ │  ⍟ │  ∨ │  ∧ │  × │  ÷ │Backspace│
│    │1   │2   │3   │4 ≤ │5 = │6 ≥ │7 > │8 ≠ │9 ⍱ │0 ⍲ │+   │´   │         │
├────┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬──────┤
│Tab    │  ⌸ │  ⍵ │  ∊ │  ⍴ │    │  ↑ │  ↓ │  ⍳ │  ○ │  ← │  → │    │      │
│       │q ⌺ │w   │e ⍷ │r   │t   │y   │u   │i ⍸ │o ⍥ │p ⍞ │å ⍬ │¨   │      │
├───────┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴──────┤
│Caps    │  ⍺ │  ⌈ │  ⌊ │  ¯ │  ∇ │    │  ∘ │  ⊢ │  ⌷ │  ≡ │  ≢ │Enter     │
│Lock    │a   │s   │d   │f   │g   │h   │j ⍤ │k ⊣ │l ⎕ │æ ⍎ │ø ⍕ │          │
├────────┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──────────┤
│Shift      │  ⊂ │  ⊃ │  ∩ │  ∪ │  ⊥ │  ⊤ │    │; ⍝ │: ⍀ │_ ⌿ │Shift       │
│           │z ⊆ │x   │c   │v ∪ │b   │n   │m   │, ⍪ │.   │/ ⍠ │            │
├───────┬───┴─┬──┴───┬┴────┴────┴────┴────┴────┴┬───┴──┬─┴────┼─────┬──────┤
│Ctrl   │Win  │Alt   │                          │Alt Gr│Win   │Menu │Ctrl  │
│       │     │      │                          │      │      │     │      │
└───────┴─────┴──────┴──────────────────────────┴──────┴──────┴─────┴──────┘
```

keylist:
first row means what key, second row means alt+key gives that character. third row means alt+shift need to be held to get the character.

```
Q ⌸ ⌺
W ⍵
E ⍷ ∊ 
R ⍴
Y ↑
U ↓
I ⍸ ⍳
O ⍥ ○
P ⍞ ←
å → ⍬
a ⍺ 
S ⌈
D ⌊
F ¯
G ∇
J ⍤ ∘
K ⊢ ⊣
L ⌷ ⎕
æ ≡ ⍎ 
ø ≢ ⍕
Z ⊂ ⊆
X ⊃
C ∩
V ∪
B ⊥
N ⊤
, ⍝ ⍪
. ⍀
- ⍠ ⌿
ESC ⋄ 
1 ⌶
2 ⍱ ¨
3 ⍒
4 ⍋ ≤
5 ⌽ ≥
6 ⍉ 
7 ⊖
8 ⍟ ≠
9 ∨ ⍱
0 ∧ ⍲
+ ×
´ ⌹ ÷
* ⍣
~   ⍨
```
UNUSED:
TP'M
