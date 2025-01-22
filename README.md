java c
CSC/MAT A67   Tutorial   1 —   Introduction to   Propositional   Logic
Winter   2025
1          introduction
Tutorials   in   this   course   will   run   as   follows:
•    Tutorial   exercises   /   questions   will   be   posted   on   the   course   website   before   Tuesday.
•   In tutorial,   your   TA   may
–   review   relevant   course   material,
–    present   solutions   to   one   or   more   example   problems,
–   give   you   ideas   on   how   to   work   through   the   tutorial   exercises   /   questions,
–    answer   your   questions   and   give   you   suggestions,   as   you   work   through   the   exercises.
•   In tutorial,   you   may
–   work   on   the   tutorial   exercises,   either   with   another   student      (encouraged!)      or   indepen-   dently,
–      seek   help   from   your   TA.
•   You   will   submit   your   solutions   on   Crowdmark   before   9   a.m.   on   the   following   Tuesday.
•   We   will   check   your   submission   and   assign   a   grade,   before   the   end   of that   week.    For   each   set   of   questions,   you   will   receive:
–    2   marks:   if   there   is   a   solid   attempt   at   a   solution   for   all   questions,   even   if   there   are   some mistakes.
–    1   mark:   if   there   is   a   solid   attempt   at   a   solution   to   many   of   the   questions,   or
–    0   marks:   otherwise.
•   If you   are   unable   to   complete   the   solution   to   a   question,   then   write   what   you   tried   to   do   and   why   it   doesn’t   work.
•      For   tutorial   exercises,   you   can   work   with   other   students   (encouraged!),   and   you   can   consult other materials as long as   you   write   your   own   solutions.    But remember   that   the   main   purpose   of   these exercises is to help you master the material.   If   you simply copy someone else’s solutions   then   you   will   miss   out   on   the   benefits   of working   through   the   problems.   You   are   not   allowed to   use   ChatGPT   or   any   similar   software.
2          exercises   (to   practice,   do   not   submit)
Analyse   the   logical   forms   of   these   statements:
1.      Either   John   and   Bill   are   telling   the   truth,   or   neither   of them   is.
2.   I’ll   have   either   fish   or   chicken,   but   I   won’t   have   both   fish   and   mashed   potatoes.
3          exercises   (to   be   submitted)
Analyse   the   logical   forms   of   these   statements:
1.      Either   both   Ralph   and   Ed   are   tall,   or   both   of them   are   handsome.
2.      Both   Ralph   and   Ed   are   either   tall   or   handsome.
3.      Both   Ralph   and   Ed   are   neither   tall   nor   handsome.
4.      Neither   Ralph   nor   Ed   is   both   tall   and   handsome.
5.      Either   both   Ralph   and   Ed   are   tall,   or   neither   of them   is.
6.    Either   Ralph   is   tall   and   Ed   is   handsome,   or   vice   versa.
4          exercises   (to   be   submitted)Let   T   stand   for   the   statement      “taxes   will   go   up”,   and   D   stand   for   the   statement      “the   deficit   will   go   up”   .    What   English   sentences   are   represented   by   the   following   formulas?    Try   to   come   up   with simple,   short   solutions.
1.   T   ∨ D
2.    ¬   (T Λ D) Λ ¬   (¬T Λ ¬D)
3.    (T Λ ¬D) ∨   (D   Λ ¬T)
5          arguments   and   truth   tables   (to   be   submitted)All truth tables   must   be written   in   standard   format.    The   first variable   has value   T   in   the   first   half   of   the   rows   and   F   in   the   second   half.    The   second   variable   has   value    T   in   the   first   quarter   of   the   rows,   F   in the   second   quarter, 代 写CSC/MAT A67 Tutorial 1 — Introduction to Propositional Logic Winter 2025R
代做程序编程语言  T   in the third   quarter,   and   F   in the   fourth   quarter   of the   rows.    The   third   variable   has   value   T   in   the   first   eighth   of the   rows,   etc.    For   example,   a   truth   table   with   the   four variables   A,C,R,Q will   look   like   this:
A            C            R            Q            ........
T            T            T            T            ........
T            T            T            F               ........
T            T            F            T            ........
T            T            F             F               ........
T            F            T            T            ........
T            F            T            F               ........
T            F            F            T            ........
T            F            F             F               ........
F            T            T            T            ........
F            T            T            F               ........
F            T            F            T            ........
F            T            F             F               ........
F            F            T            T            ........
F            F            T            F               ........
F            F            F            T            ........
F            F            F             F               ........
Demonstrate   whether   these   arguments   are   valid   or   not.
1.      Either   my   dog   is   spotted   or   my   cat   is   spotted.    My   dog   is   not   spotted   or   my   cat   is   not   spotted.   Therefore   either   my   dog   is   spotted   or   my   cat   is   not   spotted.
2.      Either   John   or   Bill   is   telling   the   truth.      Either   Sam   or   Bill   is   lying.      Therefore,   either   John   is   telling   the   truth   or   Sam   is   lying.
3.      Jane   and   Pete   won’t   both   win   the   math   prize.      Pete   will   win   either   the   math   prize   or   the   chemistry   prize.   Jane   will   win   the   math   prize.   Therefore,   Pete   will   win   the   chemistry   prize.
6          logical   equivalences      (to   be   submitted)
For   each   pair   of expressions,   either   prove   that   the   two   are   equivalent   or   prove   that   they   are   not.
1.    (a   ∧ b)   ∨   (b   ∧ c)   ∨   d   and    (a ∧ b   ∧ c)   ∨ d
Notice   that   since   (a ∧ b) ∧ c    eqv    a ∧   (b   ∧ c),   we   omit   parentheses   and   write   a ∧ b   ∧ c.    This   is   simply   a   shorthand.
2.    ¬   (a ∨   b)   ∧   ¬c   and   ¬   (a   ∨   b   ∨   c)
3.    ¬   (a ∧   b)   ∨ c   and   ¬a   ∨   ¬   (b   ∧   ¬c)
4.    ¬   (P ∨ Q)   ∨ ¬Q   and   ¬Q
5.    ¬A ∧ ¬(B ∧ C)   and   ¬   (A ∨ B) ∨ ¬   (A ∨ C)
Show   that   the   following   pairs   of expressions   are   not   equivalent:
1.    a   →   b   and   a   ∧   b
2.    a   →   b   and   ¬a   →   ¬b
3.    (a   →   b)   ∧   (b   →   c)   and    (a ∧ b)   →   c
7          conditional   statements   (do   not   submit)
A   few   ways   of   expressing   P   →   Q   in   mathematics:
•   P   implies   Q.
•   if P   then   Q.
•   Q,   if   P.
•   P   is   a   sufficient   condition   for   Q.
•   Q   is   a   necessary   condition   for   P.
Analyse   the   logical   forms   of each   of the   following   English   statements.
1.    Mary   will   sell   her   house   only   if   she   can   get   a   good   price   and   find   a   nice   apartment.
2.    Having   both   a   good   credit   history   and   an   adequate   down   payment   is   a   necessary   condition   for getting   a   mortgage.
3.      Being enrolled full time   and demonstrating   financial   need   is   a   sufficient   condition   for   applying   for   assistance.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
