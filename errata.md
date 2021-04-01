# Errata for *Programming Algorithms in Lisp*

On **page 20** [Summary of error]:
 
Details of error here. Highlight key pieces in **bold**.

THe following snippet doesn't compile beacause it is incorrect:

'''
(do ((i 0 (1+ i))
(prompt (read-line) (read-line)))
((> i 1) i)
(print (pair i prompt))
(terpri))
'''
Error (in sbcl REPL):
'''
; 
; caught STYLE-WARNING:
;   undefined function: COMMON-LISP-USER::PAIR
; 
; compilation unit finished
;   Undefined function:
;     PAIR
;   caught 1 STYLE-WARNING condition

'''
***

On **page xx** [Summary of error]:
 
Details of error here. Highlight key pieces in **bold**.

***
