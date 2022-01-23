# AUTOMETA AND COMPILER DESIGN

### DATE:19/01/2022

## STATE CHANGE

    every system has a state and appling and removing something changes

Example

1)let computer be off

2. by pressing powerbutton u change its state to on
3. after boot up clicking on any file u will open it u can edit add remove basically chage its state

pressing power button and pressing open/save button is considered as state changing Actions

# AUTOMETA

### defination

    AUtomata is a system where enery, metrials and info is tranfered and used to perform some
    functions without involvent of humans directly

Automate simple basic steps by a pice of hard ware/software to do

Example
like tosting a bread,timed light bulb(turns on if sun is down)

---

## Basics fundaments of AUTOmeta

### symbol

    it is an entity or individial objects ,which can be any letter ,alphabet or any picture

Example:

letters : (A to Z )english alphabet, japanese alphabet etc

Digits : (0 to 9) non-english numbers

special characters # % ^ & () etc

---

### Alphabets

    an alphabet is a non empty finate set of symbols denoted by by sysbol ⅀ (sigma)

⅀ = {a,b,c} is an alphabet consisting of letters

⅀ = {0,1,2..} is a alphabet consisting of digits

⅀ ={a,0} is an alphabet constiting of letter 'a' and digit '0'

---

### STRING

string/word is defined as a finate collection of symbols from alphabets
denoted by " _W_ "

empty string is denoted by Ɛ
length of string is denoted as |w|

#### Examples:

⅀ = {a,b}

string w={a,b,aa,ab,ba,bb,aaa,aab ....}

⅀ ={0,1}

string w={0,1,00,01 ...}

---

#### String Operation

#### CONCATINATION OF STRING:

    the concatination odf string is the formsted by white space the first string
    followed by the second string with no space

#### Lenth of a string:

    the lenth of string w denoted by |w| number of symbols in string

#### Empty string :

    empty string denoted by λ or Ɛ it contains * ZERO SYMBOLS *
    |λ|=|Ɛ|==0

#### Reverse string :

    for a string w =a₁a₂...aₙ the reverse of string is denoted by w^R which is aₙaₙ₋₁....a₂a₁

#### substring

    for a string W="abcd" any *consecutive charactors from w is called substring of w

#### types of substrings ::

> Prefix: A prefiix of string is any number of leading symbols (starting) of that string
> Example w= "abcd" all prefix are "Ɛ,a ,ab,abc,abcd,"

> Sufix: A sufix od string is any number of traling Symbols(last ) of string
> Example w= "abcd" all sufix are "Ɛ,d,cd,bcd,abcd"

> proper prefix / proper sufix : A prefix or sufix that dosent contain itself

> _NOTE_-Ɛ is always a valid prifix /sufix for any sting

#### sets of String :

    if ⅀ is an alphabet then ⅀* (read as sigma closure) is a set of string obtained by concatination of 0(ZERO) or more symbols from ⅀ .

⅀* always contains Ɛ
⅀⁺=⅀* -{Ɛ} (⅀⁺ read as sigma +ve closure )

> _NOTE_:f ⅀ is finate but ⅀\* and ⅀⁺ are infinate.

_Examples_:
⅀ ={a,b}
⅀\* = {Ɛ,a,b,aa,ab,ba,bb,aaa ....}
⅀⁺ = {a,b,aa,ab,ba,bb,aaa ....}

---

### Language

    A lamguage is a set of sttrings of symbols from one alphabet (⅀)

A language _L_ is a ssubset of ⅀*
i.e L ⊆ ⅀*

> NOTE empty set ϕ and the set consisting of empty string i.e {Ɛ} two distint languages

Example:
1.The set of palindrome over alphabet ⅀= {0,1} is an infinate language
The language is ⅀\* = {Ɛ ,0,1,11,010,101,00100,......}

2. the set of all strings over fixed alphabet 'a'
   if ⅀ ={a} then language is⅀* ={Ɛ,a,aa,aaa,aaaa, ......}
   if ⅀={a,b} then language is⅀*={Ɛ,a,b,aa,ab,bb,aaa .....}

here both language is infinate

---

---

### Language operations:

#### complimet of language :

    the compliment of a language L is denoted by 

