java c
MATH1052 Assignment   2 
Due:    Fri   10   May   2024,   5   pm
●   Write   your   answers   clearly.   Illegible   assignments   will   not   be   marked.
●   Show   all   your   working.   Correct   answers   without justi    cation   will   not   receive   full   marks.
●   Wherever   possible,   answers   should   be   given   in   exact   form.
●   This   assignment   is   worth   7.5%   of the   total   assessment   for   the   course.
●   Submit your assignment as a single   pdf       levia   the   Assignment   1   Gradescope   submission   link   on   Blackboard      >    Assignments.
●   Submit   all   applications   for   extensions   via   the   my.UQ   portal.
●   Undertaking   this   assessment   deems   your   commitment   to   UQ's   academic   integrity   pledge   as   summarised   in   the   following   declaration:I certify that I   have   completed this   assessment in   an honest, fair and trustworthy   manner,   that   my submitted answers   are   entirely   my   own   work,   and I make   this   declaration   in full knowledge   of an   understanding   that,   should   it   be found   to   be false,   I will   be   subject   to   disciplinary   action   under   Student   Integrity   and   Misconduct   Policy   3.60.04   of   The    University   of   Queensland.
●   Marking:
✕ The   maximum   mark   for   the   assignment   is   50.   ✕ Marking   Scheme   for   questions   worth   1   mark:
*   Mark   of   0:    You    have      not   submitted   a   relevant   answer,   or   you   have   no   strategy   present   in   your   submission.
*   Mark   of   1/2:   You   have   the   right   approach,   but   need   to       ne   tune   some   aspects   of   your justi    cation/calculations.
*   Mark of 1:   You have   demonstrated a good understanding of   the topic and techniques   involved,   with   clear justi    cation   and   well-executed   calculations.
✕ Marking   Scheme   for   questions   worth   2   marks:
*   Mark   of   0:    You    have      not   submitted   a   relevant   answer,   or   you   have   no   strategy   present   in   your   submission.
*   Mark of 1:   You have the right   approach,   but   need   to         ne   tune   some   aspects   of your   justi    cation/calculations.
*   Mark of   2:   You have demonstrated a good understanding of   the topic and techniques   involved,   with   clear justi    cation   and   well-executed   calculations.
✕ Marking   Scheme   for   questions   worth   3   marks:
*   Mark   of   0:    You    have      not   submitted   a   relevant   answer,   or   you   have   no   strategy   present   in   your   submission.
*   Mark   of   1:    Your    submission   has   some   relevance,   but   does   not   demonstrate   deep   understanding   or   sound   mathematical   technique.   This   topic   needs   more   attention!
*   Mark   of 2:   You have the right   approach,   but need   to         ne   tune   some   aspects   of your   justi    cation/calculations.
*   Mark of   3:   You have demonstrated a good understanding of   the topic and techniques   involved,   with   clear justi    cation   and   well-executed   calculations.
1.   The   equation   of a   quadratic   curve   is
2x2   + √3xy   + y2   - 10 = 0.
(a)    (2 marks) Use   MATLAB   to   plot   the   graph   of   the   quadratic   curve.   What   does   the   curve look   like?Just   because   the   curve   looks   like   ....    doesn't   mean   it   is    ....    Seeing   is   not   believing   in   maths!      We   will   now   PROVE   that   it   is   indeed   a   ...      !      Let   us   begin   with   the   general   equation   of a   quadratic   curve:
Ax2   + Bxy   + Cy2   + Dx   +   Ey   +   F = 0.
We will eliminate the xy-term in the equation by   a   rotation   of the   coordinate   axes.    Such   a   cool   idea   but   it   will   take   some   work   so   brace   yourself!
(b)    (3   marks)   Suppose   P   =   (x,   y)   is   a   point   on   the   xy-plane.    Now   rotate   the   coordinate   axes   anticlockwise   about   the   origin   through   an   angle   Q.   Let   the   coordinates   of P   with   respect   to   the   new   coordinate   axes   be   (x,   ,   y,   )   (see       gure   below).    Show   that
x =   x,   cos   Q   - y,   sin   Q,   y   = x,   sin   Q   + y,   cos   Q.Useful   tip:    Recall   the   sum   formula   for   cosine    and   sine.      If   you   can't   remember   what   these   are,   go   to   the   FYLC.   I've   posted   the   formula   on   one   of the   walls   in   the   room   :).   While   you're   there,   say   hello   to   the   FYLC   tutors   -   they   can   de      nitely   help   you   with this   question.
(c)    (2 marks) The   equation   Ax2   +Bxy+Cy2   +Dx+Ey+F   = 0, B  0, maybe   transformed into   a   new   quadratic   equation   A,x,2   +   B,x,y,   +   C,y,2   +   D,x,   +   E,y,   +   F,      =   0.   Determine an   expression   for   B,    in   terms   of   A,B,   C   and   Q.
(d)    (2   marks)   To   eliminate   the   cross   term   in   the   new   quadratic   equation   in   (c),   show   that   Q   must   satisfy
The   angle   Q   gives   the   angle   of   rotation   of the   coordinate   axes   to   produce   a   quadratic   equation   with   no   cross   term.
(e)    (1   mark)   Determine   Q   for   the   quadratic   equation   2x2    + √3xy   + y2    - 10 = 0.
(f)    (3   marks)   Find   an   equation   for   2x2    + √3xy   + y2    - 10   =   0   in   the   x,y,-plane.    Describe代 写MATH1052 Assignment 2Matlab
代做程序编程语言 the   curve.
2.   The       gure below shows a   point   P   (x0   ,   y0   )   on   the   parabola   y2      =   4px.    The line   L   is   tangent   to   the   parabola   at   P.   The   parabola's   focus   lies   at   F   (p,   0).   The   ray   L,    extending   from   P   to   the right   is   parallel   to   the   x-axis.    We   show   that   light   from   F   to   P   will   be   re      ected   out   along   L,   by   showing   that   β   equals   Q.   This   result   establishes   the   re    ective   property   of parabolas.
(a)    (3   marks)   Show   that   tan   β   = 2p/y0   .
(b)    (1   mark)   Show   that   tan   φ   = y0   / (x0    -   p).
(c)    (3   marks)   Use   the   identity
to   show   that   tan   Q   = 2p/y0   .    Hence   show   that   Q   = β   .
(d)    (3   marks)   You   have just   proved   the   re    ective   property   of   parabolas!    This   property   is   used   in   car   headlights   and   satellite   dishes.      Write   an   amusing   essay    (maximum    150   words)   on   an   interesting   application   of the   re    ective   property   of   parabolas.    You   may   include   illustrations   in   your   essay.(e)    (2    marks)    The         gure   below   shows   a   method   for   constructing   a   parabola.       You      will   require   a   ruler   and   a   string   the   length   of   the   ruler.      Draw   a   line   on   a   piece   of   paper.This   is   the   directrix   of the   parabola.   Choose   a   point   F   on   the   paper.   This   is   the   focus   of   the   parabola.    Pin   one   end   of   the   string   to   F   and   the   other   end   of   the   string   to   the upper   end   of   the   ruler.   Hold   the   string   taut   against   the   ruler   with   a   pencil,   and   slide   the ruler   along   the   directrix.   As   the   ruler   moves,   the   pencil   will   trace   a   parabola.   Explain
why.   Hint:   recall that a parabola is the   set   of points in   a   plane   equidistant   from   a   given   xed   point   and   a   given       xed   line   in   the   plane.
(f)    (Optional)    Try      the      construction      in      (e)    for      fun!       Special      MATH1052    Prize      for      best   parabola   model   based   on   this   idea.       Submit    your    model    to    Poh    (Room    67-556)    by   Friday   10   May,   5   pm.    If   Poh   is   not   in   her   room,   leave   the   model   on   the   table   located   outside   her   room.   Please   write   your   name   and   Student   ID   on   the   model.
3.    Let
(a)    (3   marks)   Sketch   (by   hand)   the   graph   of   z   = f(x,   y).
(b)    (3 marks) Is f continuous at (0,   0)?    Justify your answer using the de    nition of   continuity.
(c)    (3   marks)   Use   the   sketch   in   (a)   to      guess    and       at   (0,   0). Check   that   your   guess   is   correct   for   using   the   de      nition   of   the   partial   derivative.
(d)    (2   marks)   What   conclusion,   if any,   can   you   make   about   the   existence   of partial   deriva-   tives   and   continuity   for   a   function   f(x,   y)?4.   Let's   learn   some   vector   calculus   ahead   of   time!       Let r(t)    =    x(t)i + y(t)j +   z(t)k be   the position   vector   of   particle   at   time   t. The   velocity   vector   is   given   by   v(t)   = i + j + k.
An   important   fact   about   the   velocity   vector   is   that   it   is   tangent   to   the   path   of   motion.   That's   all   you   need   to   know   for   this   problem!   In   preparation   for   a   spectacular   Taylor   Swift concert   at   UQ,   MATH1052   students   at   UQ   constructed   a   surface   given   by   the   equation   xz2   -   yz   + cos(xy) =   1.
(a)    (1   mark)   Show   that    (0,   0, 1)   is   on   the   surface.    This   is   the   point   on   the   surface   where   Taylor   Swift will   land.
(b)    (3   marks)   Construct   the   equation   of   the   platform   tangent   to   the   surface   at    (0,   0, 1).   Hint:   in   page   171   of the   workbook,   you   have   the   following   geometrical   property   about   gradient   vectors   in   the   plane:          If   f      is   di      erentiable      at      (a,   b),    the   gradient      ▽f   (a,   b)   is   perpendicular   to   the   contour   line   through   (a,   b).”   Generalise   this   result   to   gradient   vectors   in   space   to   help   you   construct   the   equation   of Swift's   platform.
(c)    (3   marks)   Taylor   Swift   will   glide   through   UQ's   exhibition   hall   along   the   path r(t)   =   (ln   t)i + (tlnt)j +   tk, t   > 0.   Show   that   the   curve   is   tangent   to   the   surface.    Phew!   That was   a   smooth   landing!
5.   A   MATH1052   trophy   is   constructed   by   rotating   the   following   region   about   the   x-axis.
(a)    (2   marks)   Compute   the   volume   of the   trophy.
(b)    (2   marks)   Find   the   volume   V   (r,   s)   of   a   similar   solid   created   by   rotating   a   region   with dimensions   r   and   s   instead   of 3   and   2   respectively.
(c)    (3   marks)   Ooops!!    The   original   numbers    "2"    and   "3"   were   rounded   o       numbers.    The   actual   quantities   are   o         by   up   to   0.5   in   either   direction.    Use   linear   approximation   to estimate   the   maximum   possible   error   in   your   answer   to   (a).



         
加QQ：99515681  WX：codinghelp
