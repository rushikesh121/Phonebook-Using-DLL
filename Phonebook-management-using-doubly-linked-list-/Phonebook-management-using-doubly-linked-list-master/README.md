

# Taught data structures
1.Array<br />
2.LinkedList<br />
 a.Singly Linked List<br />
 b.Doubly Linked List<br />
 c.Circular Linked List<br />
3.Stack<br />
4.Queue<br />

# Topic: THIS DEMONSTRATES THE PHONEBOOK MANAGEMENT SYSTEM WITH DOUBLY LINKED LIST SO THAT TRAVERSING CAN BE EASY.....
# In eclipse

#Phonebook management have three main operations:<br />
#1.Searching<br />
#2.Sorting<br />
#3.Deleting<br />
These three operation can be performed efficiently(among above data structures) with Linked List.
Doubly Linked List because while searching first element but the current status of pointer is in between middle and first element so it should traverse backward because then it will take less time.


# Time complexities in O

1.Searching O(n)<br />
2.Deletion O(n)<br />
3.Sorting O(n*Log n)<br />

# OPERATIONS IMPLEMENTED.............
1)DELETE SAME NUMBER<br />
2)DELETE SAME NAME<br />
3)SEARCH<br />
4)DELETE CONATCT<br />
5)DISPLAY CONTACT-In sorted(bubble sort) display<br />
6)UPDATE DETAILS-A)NAME<br />
                 B)NUMBER<br />
                 C)G-MAIL<br />
7)INSERT CONTACT<br />

# OUTPUT:-In eclipse java

**************                                PHONE BOOK                          ********************

WHAT IS YOUR NAME?
Priti jha


!!!!!!!!!!!!!!!!!!!!!!!   WELCOME Priti jha   !!!!!!!!!!!!!!!!!!!!!


LET'S CREATE OUR PHONEBOOK Priti jha  

ENTER NAME      :vijay
ENTER NUMBER    :1234567890
ENTER G-MAIL    :priti@gmail.com
DO YOU WANT TO CONTINUE?????????y
ENTER NAME      :rahul
ENTER NUMBER    :1234567890
ENTER G-MAIL    :rahh ul@gmail.com
DO YOU WANT TO CONTINUE?????????n




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
1


NAME  ::	rahul
NUMBER::	+91-1234567890
G-MAIL::	priti@gmail.com

NAME  ::	vijay
NUMBER::	+91-1234567890
G-MAIL::	rahul@gmail.com

DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
2
ENTER NAME      :akshay
ENTER NUMBER    :9819140108
ENTER G-MAIL    :akshay@gmail.com
DO YOU WANT TO CONTINUE?????????y
ENTER NAME      :Vijay
ENTER NUMBER    :1234567890
ENTER G-MAIL    :vijay@gmail.com
DO YOU WANT TO CONTINUE?????????n


DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
3 1


NAME  ::	Vijay
NUMBER::	+91-1234567890
G-MAIL::	priti@gmail.com

NAME  ::	akshay
NUMBER::	+91-1234567890
G-MAIL::	rahul@gmail.com

NAME  ::	rahul
NUMBER::	+91-9819140108
G-MAIL::	akshay@gmail.com

NAME  ::	vijay
NUMBER::	+91-1234567890
G-MAIL::	vijay@gmail.com

DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
3


ENTER THE NAME OF PERSON WHOSE DETAILS YOU WANT TO UPDATE...
Vijay

WHAT DO YOU WANT TO UPDATE?
1.NAME
2.PHONE NUMBER
3.G-MAIL
1
ENTER NEW-NAME=Priti
DO YOU WANT TO CONTINUE UPDATING?n


DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
1


NAME  ::	Priti
NUMBER::	+91-1234567890
G-MAIL::	priti@gmail.com

NAME  ::	akshay
NUMBER::	+91-1234567890
G-MAIL::	rahul@gmail.com

NAME  ::	rahul
NUMBER::	+91-9819140108
G-MAIL::	akshay@gmail.com

NAME  ::	vijay
NUMBER::	+91-1234567890
G-MAIL::	vijay@gmail.com

DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
4

ENTER THE NAME YOU WANT TO DELETE FROM PHONEBOOK
Priti
YOUR CONTACT IS SUCCESSFULLY DELETED



DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
1


NAME  ::	akshay
NUMBER::	+91-1234567890
G-MAIL::	rahul@gmail.com

NAME  ::	rahul
NUMBER::	+91-9819140108
G-MAIL::	akshay@gmail.com

NAME  ::	vijay
NUMBER::	+91-1234567890
G-MAIL::	vijay@gmail.com

DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
2
ENTER NAME      :akshay
ENTER NUMBER    :1234567980
ENTER G-MAIL    :akshay@gmail.com
DO YOU WANT TO CONTINUE?????????n


DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
1


NAME  ::	akshay
NUMBER::	+91-1234567890
G-MAIL::	rahul@gmail.com

NAME  ::	akshay
NUMBER::	+91-9819140108
G-MAIL::	akshay@gmail.com

NAME  ::	rahul
NUMBER::	+91-1234567890
G-MAIL::	vijay@gmail.com

NAME  ::	vijay
NUMBER::	+91-1234567980
G-MAIL::	akshay@gmail.com

DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
5


NAME  ::	akshay
NUMBER::	+91-1234567890
G-MAIL::	rahul@gmail.com

NAME  ::	rahul
NUMBER::	+91-1234567890
G-MAIL::	vijay@gmail.com

NAME  ::	vijay
NUMBER::	+91-1234567980
G-MAIL::	akshay@gmail.com

DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
1


NAME  ::	akshay
NUMBER::	+91-1234567890
G-MAIL::	rahul@gmail.com

NAME  ::	rahul
NUMBER::	+91-1234567890
G-MAIL::	vijay@gmail.com

NAME  ::	vijay
NUMBER::	+91-1234567980
G-MAIL::	akshay@gmail.com

DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
3


ENTER THE NAME OF PERSON WHOSE DETAILS YOU WANT TO UPDATE...
rahul

WHAT DO YOU WANT TO UPDATE?
1.NAME
2.PHONE NUMBER
3.G-MAIL
2
ENTER NEW PHONE-NUMBER?1234567890
DO YOU WANT TO CONTINUE UPDATING?n


DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
1


NAME  ::	akshay
NUMBER::	+91-1234567890
G-MAIL::	rahul@gmail.com

NAME  ::	rahul
NUMBER::	+91-1234567890
G-MAIL::	vijay@gmail.com

NAME  ::	vijay
NUMBER::	+91-1234567980
G-MAIL::	akshay@gmail.com

DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
6


NAME  ::	akshay
NUMBER::	+91-1234567890
G-MAIL::	rahul@gmail.com

DO YOU WANT TO CONTINUE OPERATIONS?????????y




1) DISPLAY YOUR PHONE BOOK
2) INSERT NEW CONTACT
3) UPDATE DETAILS ON EXISTING CONTACT
4) DELETE CONTACT
5) DELETE SAME NAME IN PHONEBOOK
6) DELETE SAME NUMBERS IN PHONEBOOK
7) SEARCH
7
1.SEARCH BY NAME
2.SEARCH BY NUMBER
3.SEARCH BY GMAIL1
ENTER THE NAME TO BE SEARCHED
akshay
NAME FOUND
CONTACT DETAILS ARE BELOW:



NAME  ::	akshay
NUMBER::	+91-1234567890
G-MAIL::	rahul@gmail.comDO YOU WANT TO CONTINUE SEARCHING?????????n


DO YOU WANT TO CONTINUE OPERATIONS?????????n


