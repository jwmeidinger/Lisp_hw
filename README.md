# Lisp_hw
LISP! is SUPER fun

;; ---------------------------------------------------------------------------------
;;
;; CS372 Comparative Programming Languages
;; 
;; Grading Criteria:
;; -  At least two test cases exist in final report demonstrating potential corner conditions 
;;    and functionality 
;; - Output included in report along with code
;; - Code file must load and run in the Lisp interpreter with no syntax errors
;; - Use the FORMAT function to print results at run-time
;;
;; ---------------------------------------------------------------------------------

;; ---------------------------------------------------------------------------------
;; Problem # 1 (10 Points)
;;
;; Lambda expression can be useful when you wish to simply preform an operation 
;; on a list without going into creating a whole function for them.  Languages
;; such as Python, C# and Java have adopted the lambda expression for this reason.
;;
;; Use the lambda expression in Lisp to multiply every element in the list by 2
;;
;;  Example: (2 4 6 8) => (4 8 12 16)
;;      AND: (2 4 N 8) => (4 8 NIL 16)
;; ---------------------------------------------------------------------------------

;; ---------------------------------------------------------------------------------
;; Problem # 2 (10 Points)
;;
;; Define MAKE-SET, A function that takes a list and returns a set of that list.  
;; A set is a list that contains no duplicate items
;;
;;  Example: (MAKE-SET '(A B C A D C)) => (A B C) 
;; ---------------------------------------------------------------------------------

;; ---------------------------------------------------------------------------------
;; Problem # 3 (10 Points)
;;
;; Define IS-SET, a procedure that takes a list as its argument and 
;; returns a True if the list is a set, false otherwise 
;;
;;  Example: (IS-SET '(a b c d)) => T 
;;       AND (IS-SET '(a a b c d)) => nil
;; ---------------------------------------------------------------------------------

;; ---------------------------------------------------------------------------------
;; Problem # 4 (10 Points)
;;
;; Write a recursive my-len function that returns the length of a list
;;      Example: (my-len '(1 2 3 4 5)) => 5
;; ---------------------------------------------------------------------------------

;; ---------------------------------------------------------------------------------
;; Problem # 5 (10 Points)
;;
;; Write a recursive my-sum function that returns the sum of a list
;;      Example: (my-sum '(1 2 3 4 5 6 7 8 9)) => 45
;; ---------------------------------------------------------------------------------

;; ---------------------------------------------------------------------------------
;; Problem # 6 (10 Points)
;;
;; Use your my-len and my-sum functions to implement a my-average that takes 
;;     a list of numbers and returns the mean (average) value
;;     Example: (my-average '(1 2 3 4 5 6 7 8 9)) => 5.0
;;     Example: (my-average '(123 233 324 445 526) => 330.2
;; ---------------------------------------------------------------------------------

;; ---------------------------------------------------------------------------------
;; Problem #7 (20 Points)
;;
;; Write a function that uses my-len function from #7
;; to recursively find and return a sub-list with
;; the maximum length
;; Example:
;;      (max_sub_list '(1 (1 2 3 4) (1 2 3))) => (1 2 3 4)
;; ---------------------------------------------------------------------------------

;; ---------------------------------------------------------------------------------
;; Problem #8 (20 Points)
;;
;; Write A recursive function named MYMEMBER that takes an ATOM (atm) and a LIST (lst) 
;; and returns the ATOM if it is a MEMBER, otherwise NIL
;;
;; Example:
;;        (MYMEMBER 船 '(A B C D E F G) returns => D
;;        (MYMEMBER 践 '(A B C D E F G) returns => NIL
;;
;; ---------------------------------------------------------------------------------

