# cs170-homework-6-solved
**TO GET THIS SOLUTION VISIT:** [CS170 Homework 6 Solved](https://www.ankitcodinghub.com/product/cs170-homework-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96694&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS170 Homework 6 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
2 2-SAT

In the 2SAT problem, you are given a set of clauses, where each clause is the disjunction (OR) of two literals (a literal is a Boolean variable or the negation of a Boolean variable). You are looking for a way to assign a value true or false to each of the variables so that all clauses are satisfied that is, there is at least one true literal in each clause. For example, heres an instance of 2SAT:

(x1 ∨x2)∧(x1 ∨x3)∧(x1 ∨x2)∧(x3 ∨x4)∧(x1 ∨x4)

This instance has a satisfying assignment: set x1, x2, x3, and x4 to true, false, false, and true, respectively.

The purpose of this problem is to lead you to a way of solving 2SAT efficiently by reducing it to the problem of finding the strongly connected components of a directed graph. Given an instance I of 2SAT with n variables and m clauses, construct a directed graph GI = (V, E) as follows.

􏰎 GI has 2n nodes, one for each variable and its negation.

􏰎 GI has 2m edges: for each clause (α ∨ β) of I (where α, β are literals), GI has an edge

from from the negation of α to β, and one from the negation of β to α.

Note that the clause (α ∨ β) is equivalent to either of the implications α =⇒ β or β =⇒ α.

In this sense, GI records all implications in I.

(a) Show that if GI has a strongly connected component containing both x and x for some

variable x, then I has no satisfying assignment.

(b) Now show the converse of (a): namely, that if none of GI’s strongly connected compo- nents contain both a literal and its negation, then the instance I must be satisfiable. (Hint: Assign values to the variables as follows: repeatedly pick a sink strongly con- nected component of GI . Assign value true to all literals in the sink, assign false to their negations, and delete all of these. Show that this ends up discovering a satisfying assignment.)

(c) Conclude that there is a linear-time algorithm for solving 2SAT.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3 Perfect Matching on Trees

A perfect matching in an undirected graph G = (V, E) is a set of edges E′ ⊆ E such that for every vertex v ∈ V , there is exactly one edge in E′ which is incident to v.

Give an algorithm which finds a perfect matching in a tree, or reports that no such matching exists. Describe your algorithm, prove that it is correct and analyse its running time.

4 Huffman Coding

In this question we will consider how much Huffman coding can compress a file F of m characters taken from an alphabet of n = 2k characters x0, x1, … , xn−1 (each character appears at least once).

(a) Let S(F) represent the number of bits it takes to store F without using Huffman coding (i.e., using the same number of bits for each character). Represent S(F) in terms of m and n.

(b) Let H(F) represent the number of bits used in the optimal Huffman coding of F. We define the efficiency E(F) of a Huffman coding on F as E(F) := S(F)/H(F). For each m and n describe a file F for which E(F) is as small as possible.

(c) For each m and n describe a file F for which E(F) is as large as possible. How does the largest possible efficiency increase as a function of n? Give you answer in big-O notation.

5 Minimum Spanning k-Forest

Given a graph G(V, E) with nonnegative weights, a spanning k-forest is a cycle-free collection of edges F ⊆ E such that the graph with the same vertices as G but only the edges in F has k connected components. For example, consider the graph G(V,E) with vertices V = {A, B, C, D, E} and all possible edges. One spanning 2-forest of this graph is F = {(A,C),(B,D),(D,E)}, because the graph with vertices V and edges F has components {A, C}, {B, D, E}.

The minimum spanning k-forest is defined as the spanning k-forest with the minimum total edge weight. (Note that when k = 1, this is equivalent to the minimum spanning tree). In this problem, you will design an algorithm to find the minimum spanning k-forest. For simplicity, you may assume that all edges in G have distinct weights.

(a) Define a j-partition of a graph G to be a partition of the vertices V into j (non-empty) sets. That is, a j-partition is a list of j sets of vertices Π = {S1,S2 …Sj} such that every Si includes at least one vertex, and every vertex in G appears in exactly one Si. For example, if the vertices of the graph are {A,B,C,D,E}, one 3-partition is to split the vertices into the sets Π = {{A, B}, {C}, {D, E}}.

Define an edge (u,v) to be crossing a j-partition Π = {S1,S2 …Sj} if the set in Π containing u and the set in Π containing v are different sets. For example, for the 3-partition Π = {{A, B}, {C}, {D, E}}, an edge from A to C would cross Π.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
&nbsp;Show that for any j-partition Π of a graph G, if j &gt; k then the lightest edge crossing Π

must be in the minimum spanning k-forest of G.

(b) Give an efficient algorithm for finding the minimum spanning k-forest. Please give a 3-part solution.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
