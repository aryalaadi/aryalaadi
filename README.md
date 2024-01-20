visit [aryalaadi.github.io](https://aryalaadi.github.io)
```asm
; one must imagine the cpu happy
_start:
  pushq %rbp
  movq %rsp, %rbp
_loop:
  jmp _loop

;         _          ________
;        / \_       /        \
;        \ /       /          \
;        /_______//            \
;       /________/|            |                       ||||||||
;      /          |            |                  |||||
;     /           |            |          ||||||||
;    / \           \          /   ||||||||
;    |  \            \______/|||||
;    |   |       ||||||||||||
;   /    |_ |||||
;  /_  |||||
;|||||| IS HE ACTUALLY HAPPY?
```
