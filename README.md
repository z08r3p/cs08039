java c
CSE 101 
Final Review Problems 
1.       Determine whether the following statements are True or False.    No   justification   is required.
a.         n√n   =   Ω(n2)
b.         nπ =   O(n3)
c.       n2 = Θ (9log3 (n))
d.       n √3n   =   ω   (√n)
e.         n2      =   o(n3)
f.         ln(n)   =   o(n)
g.         2n      =   O(n2)
h.       n1.5      = ω (n1.45)
i.         n ln(n)   =   Θ(ln(ln(n)))
j.         f(n)   =   ω   (f(n)) for   any   function   f(n)
2.       Given a Binary   Search Tree based on the   following   C++   struct
struct Node{
int   key;
Node*   left;
Node*   right;
};Complete the recursive   C++   function below   called   TreeWalk()   that   takes   as   input   a Node   pointer   R   and a string   s, then returns a string consisting of   all keys in the subtree rooted at R,   separated by   spaces.   The   order   of the   keys   depends   on   the   input   string    s,   which   will   be   either    "pre",   "in"   or   "post",   indicating   a pre-order,   in-order   or   a post-order tree walk, respectively.      If   the   input   s   is   not   one   of   the   strings   "pre",   "in"   or   "post",   then   your   function   will   return   the   empty   string.       The   recursion   will   terminate when R   has the value nullptr.
std::string TreeWalk(Node* R, std::string s){ 
// your code starts here 
// your code ends here 
}
3.       Perform. Dijkstra(G,   s)   on the weighted digraph below with source   vertex   s    =    5.    If   at some point   two   vertices   have   equal   minimum   d-values,   extract   the   one   with   smaller   label   first   from   the   min   Priority   Queue.

a.       Determine the order in which vertices are   extracted   from the   min Priority   Queue.
b.       For   each   vertex   x, determine   the   values   d[x]   and   p[x].
Solution: 
x 
1 
2 
3 
4 
5 
6 
7 
8 
9 
10 
d[x] 










p[x] 









4.       Insert   the   keys:       5,   9,   7,   2,   6,   4,   8,   3,    1,    10      (in   order)   into   an   initially   empty   Binary   Search   Tree T   .   (Note: use the Binary Search Tree Insert   algorithm to   do this.)
a.       Give the keys in the order printed by   a pre-order tree walk.
b.       Give the keys in the order printed by a post-order tree walk.Note: the three questions below do not refer in any way to the Red Black Tree Insert algorithm.   Instead   they ask if   it is possible to assign colors in   the   BST T,   which you   found   above,   so   as   to   satisfy   the RBT   properties.    Be   sure   to   include   nil   children   when   computing   the   black-height   of T.
c.       Is    it   possible   to   assign   the   colors   {Red,   Black}   to   the   vertices   of T   so   that   the   Red-Black   Tree   properties   are   satisfied,   and bh(T)   =   1?      If it   is possible,   specify   all   such   colorings by   stating,   for   each   coloring, the   set   of   keys   belonging   to   red   nodes.
d.       Is   it   possible   to   assign   the   colors   {Red,   Black}    to   the   vertices   of T   so   that   the   Red-Black   Tree   properties   are   satisfied,   and bh(T)   =   2?      If it   is possible,   specify   all   such   colorings by   stating,   for   each   coloring, the   set   of   keys   belonging   to   red   nodes.
e.       Is    it   possible   to   assign   the   colors   {Red,   Black}   to   the   vertices   of T   so   that   the   Red-Black   Tree   properties   are   satisfied,   and bh(T)   =   3?      If it   is possible,   specify   all   such   colorings by   stating,   for   each   coloring, the   set   of   keys   belonging   to   red   nodes.
5.       Insert the keys: 6, 2,   1, 4, 3, 5 into an initially empty Red-Black Tree (using the RB_Insert() algorithm),   then draw the resulting tree T   .    Indicate the color   of   each   node   in T   .





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
