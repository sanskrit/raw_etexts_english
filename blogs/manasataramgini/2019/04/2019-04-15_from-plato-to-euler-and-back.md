+++
title = "From Plato to Euler and back"

+++
This is primarily meant as an educational handout on some very basic
theorems of geometry that one might have studied in school. Some
educated adults whom we asked about these had either forgotten them or
claimed to have never studied them. Hence, we provide these here for
those who might be interested. In the below discussion all angles are in
radians unless explicitly specified otherwise.

**There are only 5 Platonic solids  
**The first question is at least as old as the times of Plato: Why are
they only 5 Platonic solids? Platonic solids are regular polyhedra, i.e.
they have all their faces as the same regular polygon. The simplest
regular polygon is an equilateral triangle. Its angle is
![\\tfrac{\\pi}{3}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Cpi%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\pi}{3}"). In order to fold a solid the sum of the angles of
the polygonal faces must be less than ![2
\\pi](https://s0.wp.com/latex.php?latex=2+%5Cpi&bg=ffffff&fg=333333&s=0
"2 \\pi") radians because ![2
\\pi](https://s0.wp.com/latex.php?latex=2+%5Cpi&bg=ffffff&fg=333333&s=0
"2 \\pi") is the sum of the angles about a point on a plane in Euclidean
space. Further, to make a solid we need at least 3 polygonal faces meet
at a vertex. Hence, with an equilateral triangle we can make solids with
3 or 4 or 5 faces meeting at a vertex, ![3 \\times \\tfrac{\\pi}{3}; 4
\\times \\tfrac{\\pi}{3}; 5\\times
\\tfrac{\\pi}{3}\<2\\pi](https://s0.wp.com/latex.php?latex=3+%5Ctimes+%5Ctfrac%7B%5Cpi%7D%7B3%7D%3B+4+%5Ctimes+%5Ctfrac%7B%5Cpi%7D%7B3%7D%3B+5%5Ctimes+%5Ctfrac%7B%5Cpi%7D%7B3%7D%3C2%5Cpi&bg=ffffff&fg=333333&s=0
"3 \\times \\tfrac{\\pi}{3}; 4 \\times \\tfrac{\\pi}{3}; 5\\times \\tfrac{\\pi}{3}\<2\\pi").
These respectively yield the tetrahedron, the octahedron and the
icosahedron (Figure 1). With the next regular polygon, a square, we can
get 3 squares to meet at a vertex, i.e. ![3 \\times
\\tfrac{\\pi}{2}](https://s0.wp.com/latex.php?latex=3+%5Ctimes+%5Ctfrac%7B%5Cpi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"3 \\times \\tfrac{\\pi}{2}"). This yields us a cube. Next, with a
regular pentagon we can get three pentagonal faces at vertex, i.e. ![3
\\times
\\tfrac{3\\pi}{5}](https://s0.wp.com/latex.php?latex=3+%5Ctimes+%5Ctfrac%7B3%5Cpi%7D%7B5%7D&bg=ffffff&fg=333333&s=0
"3 \\times \\tfrac{3\\pi}{5}"). This gives us the dodecahedron. Thus, we
can have only 5 Platonic solids in 3-dimensional space
![\_\\blacksquare](https://s0.wp.com/latex.php?latex=_%5Cblacksquare&bg=ffffff&fg=333333&s=0
"_\\blacksquare").

In principle, one can join the centers of adjacent faces of regular
polyhedron to get another regular polyhedron due to their inherent
symmetry (Figure 1). Performing this operation one can also see that the
Platonic solids have a duality with another Platonic solid:
(cube-octahedron) – (tetrahedron-tetrahedron) –
(dodecahedron-icosahedron). In each dual pair there is one of the three
formed by equilateral triangle faces. Given that the duality operation
on the tetrahedron yields a congruent tetrahedron, you again will have
only 5 Platonic solids. It made a such a profound impression on me when
I first discovered this for myself as a kid that I could entirely
appreciate the profound impact the discovery of these solids
(apocryphally by Pythagoras and Theaetetus) had on Plato of yore. It
tells you some very basic thing about Euclidean space.

[![Platonic\_solids](https://manasataramgini.files.wordpress.com/2019/04/platonic_solids.png?w=640)](https://manasataramgini.files.wordpress.com/2019/04/platonic_solids.png)**Figure
1. The 5 Platonic solids and their duals.**

**The sum of the angles of a convex polygon**  
A polygon is a closed path with
![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0 "B")
vertices where adjacent vertices are connected by a single edge. Hence,
it follows that the polygon has
![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0 "B")
edges or sides as well (Figure 2). This gives our next question: what is
the sum of the angles of a polygon? The simplest polygon, the triangle,
has angles summing to
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") radians in Euclidean space. Every other planar convex polygon of
![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0 "B")
vertices can be constructed from
![B-2](https://s0.wp.com/latex.php?latex=B-2&bg=ffffff&fg=333333&s=0
"B-2") triangles all of which share a common vertex (Figure 2). From
Figure 2 it is apparent that the sum of angles of the polygon is equal
to the sum of the angles of the constituent triangles. Thus, the sum of
the angles of a convex polygon is
![(B-2)\\pi](https://s0.wp.com/latex.php?latex=%28B-2%29%5Cpi&bg=ffffff&fg=333333&s=0
"(B-2)\\pi") radians. This result was first derived by
[Proclus](https://manasataramgini.wordpress.com/2013/02/10/the-end-of-the-heathens/).

**[![polygon\_triangulation](https://manasataramgini.files.wordpress.com/2019/04/polygon_triangulation.png?w=640)](https://manasataramgini.files.wordpress.com/2019/04/polygon_triangulation.png)Figure
2. The sum of the angles of a convex polygon.**

**The triangulation theorem**  
Let a convex polygon have
![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0 "B")
vertices and
![I](https://s0.wp.com/latex.php?latex=I&bg=ffffff&fg=333333&s=0 "I")
internal points (Figure 3). We triangulate it by connecting the internal
points to the vertices of the bounding polygon or each other without any
edge crossing over such that the whole polygon is dissected into
![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0 "F")
triangles (Figure 3). We then ask: Is there are relationship between
![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0 "B"),
![I](https://s0.wp.com/latex.php?latex=I&bg=ffffff&fg=333333&s=0 "I"),
![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0 "F").
The answer is the triangulation theorem, which states that
![F=2I+B-2](https://s0.wp.com/latex.php?latex=F%3D2I%2BB-2&bg=ffffff&fg=333333&s=0
"F=2I+B-2").

**[![triangulation\_theorem](https://manasataramgini.files.wordpress.com/2019/04/triangulation_theorem.png?w=640)](https://manasataramgini.files.wordpress.com/2019/04/triangulation_theorem.png)Figure
3. Triangulation of a polygon.**

*Proof:*  
1\) The sum of the angles of the bounding polygon (as shown above) is
![(B-2)\\pi](https://s0.wp.com/latex.php?latex=%28B-2%29%5Cpi&bg=ffffff&fg=333333&s=0
"(B-2)\\pi").  
2\) The sum of all the angles on a plane sharing common vertex is
![2\\pi](https://s0.wp.com/latex.php?latex=2%5Cpi&bg=ffffff&fg=333333&s=0
"2\\pi") radians. Hence, the sum of the angles at all internal points is
![2I\\pi](https://s0.wp.com/latex.php?latex=2I%5Cpi&bg=ffffff&fg=333333&s=0
"2I\\pi").  
3\) Since the sum of the angles of a triangle is
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi"), the sum of the angles of all the
![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0 "F")
constituent triangles of the triangulation of the polygon is
![F\\pi](https://s0.wp.com/latex.php?latex=F%5Cpi&bg=ffffff&fg=333333&s=0
"F\\pi"). From Figure 3 it can also be seen that it is
![(B-2)\\pi+2I\\pi](https://s0.wp.com/latex.php?latex=%28B-2%29%5Cpi%2B2I%5Cpi&bg=ffffff&fg=333333&s=0
"(B-2)\\pi+2I\\pi").  
4\) ![F\\pi=(B-2)\\pi+2I\\pi; \\; \\therefore F=2I+B-2\\;\\;
\_\\blacksquare](https://s0.wp.com/latex.php?latex=F%5Cpi%3D%28B-2%29%5Cpi%2B2I%5Cpi%3B+%5C%3B+%5Ctherefore+F%3D2I%2BB-2%5C%3B%5C%3B+_%5Cblacksquare&bg=ffffff&fg=333333&s=0
"F\\pi=(B-2)\\pi+2I\\pi; \\; \\therefore F=2I+B-2\\;\\; _\\blacksquare")

**Euler’s theorem**

**[![polygon\_Euler](https://manasataramgini.files.wordpress.com/2019/04/polygon_euler.png?w=640)](https://manasataramgini.files.wordpress.com/2019/04/polygon_euler.png)Figure
4. Two polyhedra and the polygonal tilings derived from them.**

The above result regarding the triangulation of polygons in 2D space
Euclidean space and Plato’s discovery that only 5 regular polyhedra
exist in 3D space are both related to the sum of all the angles on plane
about a vertex being
![2\\pi](https://s0.wp.com/latex.php?latex=2%5Cpi&bg=ffffff&fg=333333&s=0
"2\\pi"). This in turn leads to the celebrated theorem of Euler
regarding polyhedra, which while deceptively simple had to wait for 2
millennia since Plato’s days. Consider the two polyhedra in Figure 4.
The first is a pentagonal pyramid while the second is a hexagonal prism.
Let ![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0
"F") be the number of faces,
![V](https://s0.wp.com/latex.php?latex=V&bg=ffffff&fg=333333&s=0 "V")
the number of vertices and
![E](https://s0.wp.com/latex.php?latex=E&bg=ffffff&fg=333333&s=0 "E")
the number of edges of the polyhedron. For the pyramid in question we
have ![F=6; V=6;
E=10](https://s0.wp.com/latex.php?latex=F%3D6%3B+V%3D6%3B+E%3D10&bg=ffffff&fg=333333&s=0
"F=6; V=6; E=10"). Thus,
![6+6=10+2](https://s0.wp.com/latex.php?latex=6%2B6%3D10%2B2&bg=ffffff&fg=333333&s=0
"6+6=10+2"). For the prism in question we have ![F=8; V=12; E=18\\;
\\therefore
8+12=18+2](https://s0.wp.com/latex.php?latex=F%3D8%3B+V%3D12%3B+E%3D18%5C%3B+%5Ctherefore+8%2B12%3D18%2B2&bg=ffffff&fg=333333&s=0
"F=8; V=12; E=18\\; \\therefore 8+12=18+2"). You can try this out for
other polyhedra like those in Figure 1. We can as the question: Is there
a general relationship here? We observe that always:
![F+V=E+2](https://s0.wp.com/latex.php?latex=F%2BV%3DE%2B2&bg=ffffff&fg=333333&s=0
"F+V=E+2"). This is Euler’s theorem and and we prove it below.

*Proof:*  
1\) We first reduce the 3D polyhedron to a 2D graph (Figure 4). The way
we do this is by choosing one face of the polyhedron as the bounding
polygon. We then flatten all other faces inside that bounding polygon
while still maintaining the topology of the face. This means that a
triangular face remains a triangle , a quadrilateral remains a
quadrilateral, and a
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0
"n")-gon remains a
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0
"n")-gon in the flattened 2D graph. Thus, the 2D graph is a polygonal
tiling of the selected face polygon of the starting polyhedron. This is
easy to conceive for pyramids and prisms (Figure 4). It is more
complicated for some of the Platonic polyhedra (Figure 5).

**[![polygon\_Euler\_reduction](https://manasataramgini.files.wordpress.com/2019/04/polygon_euler_reduction.png?w=640)](https://manasataramgini.files.wordpress.com/2019/04/polygon_euler_reduction.png)Figure
5. The polygonal tilings derived from the Platonic polyhedra.**

Thus, we observe that the 2D graph retains all edges and vertices of the
starting polyhedron. However, since it is constructed by flattening all
other faces onto one face we lose that face and the resulting number of
tiling polygons is 1 less than the number of polyhedral faces. Thus, the
3D equation
![F+V=E+2](https://s0.wp.com/latex.php?latex=F%2BV%3DE%2B2&bg=ffffff&fg=333333&s=0
"F+V=E+2") becomes
![F+V=E+1](https://s0.wp.com/latex.php?latex=F%2BV%3DE%2B1&bg=ffffff&fg=333333&s=0
"F+V=E+1") for a 2D polygonal tilings. Proving the latter in 2D
effectively results in proving the former.

2\) We define the number
![P=F+V-E](https://s0.wp.com/latex.php?latex=P%3DF%2BV-E&bg=ffffff&fg=333333&s=0
"P=F+V-E") for a given polygon tiling. Our objective is to prove that
always
![P=1](https://s0.wp.com/latex.php?latex=P%3D1&bg=ffffff&fg=333333&s=0
"P=1"). We next triangulate all non-triangular polygons in a given
polygon tiling into triangles. Let us define
![T=F\_t+V\_t-E\_t](https://s0.wp.com/latex.php?latex=T%3DF_t%2BV_t-E_t&bg=ffffff&fg=333333&s=0
"T=F_t+V_t-E_t") as the number we get from the faces, vertices and edges
after triangulation. From Figure 6 it is apparent that for each new edge
we add during triangulation we get a new face. Thus,
![P=T](https://s0.wp.com/latex.php?latex=P%3DT&bg=ffffff&fg=333333&s=0
"P=T"). Hence, proving
![T=1](https://s0.wp.com/latex.php?latex=T%3D1&bg=ffffff&fg=333333&s=0
"T=1") will prove
![P=1](https://s0.wp.com/latex.php?latex=P%3D1&bg=ffffff&fg=333333&s=0
"P=1").

**[![triangulation\_conservation](https://manasataramgini.files.wordpress.com/2019/04/triangulation_conservation.png?w=640)](https://manasataramgini.files.wordpress.com/2019/04/triangulation_conservation.png)Figure
6. Conservation of
![F+V-E](https://s0.wp.com/latex.php?latex=F%2BV-E&bg=ffffff&fg=333333&s=0
"F+V-E") upon polygon triangulation.**

3\) Now that we have triangulated the polygonal tiling, we can apply the
triangulation theorem on the resulting graph to show
![T=1](https://s0.wp.com/latex.php?latex=T%3D1&bg=ffffff&fg=333333&s=0
"T=1"). The faces
![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0 "F") in
the triangulation theorem is the same as the
![F\_t](https://s0.wp.com/latex.php?latex=F_t&bg=ffffff&fg=333333&s=0
"F_t") in our triangulated graph; hence we can write
![F\_t=2I+B-2](https://s0.wp.com/latex.php?latex=F_t%3D2I%2BB-2&bg=ffffff&fg=333333&s=0
"F_t=2I+B-2"). Further, the number of vertices
![V\_t](https://s0.wp.com/latex.php?latex=V_t&bg=ffffff&fg=333333&s=0
"V_t") of the triangulated graph is the sum of the number of boundary
vertices of the bounding polygon and the internal points. Thus, we get
![V\_t=I+B](https://s0.wp.com/latex.php?latex=V_t%3DI%2BB&bg=ffffff&fg=333333&s=0
"V_t=I+B"). Let
![s](https://s0.wp.com/latex.php?latex=s&bg=ffffff&fg=333333&s=0 "s") be
the sum of the number of sides of all triangles in the triangulation
redundantly counting all shared edges for each triangle. Since there are
![F\_t](https://s0.wp.com/latex.php?latex=F_t&bg=ffffff&fg=333333&s=0
"F_t") triangles we have
![s=3F\_t](https://s0.wp.com/latex.php?latex=s%3D3F_t&bg=ffffff&fg=333333&s=0
"s=3F_t"). Now
![s](https://s0.wp.com/latex.php?latex=s&bg=ffffff&fg=333333&s=0 "s")
can be expressed in another way.
![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0 "B")
will be the number of all the sides of triangles making up the boundary
polygon. The
![E\_t-B](https://s0.wp.com/latex.php?latex=E_t-B&bg=ffffff&fg=333333&s=0
"E_t-B") will be the remaining edges. Now they will fall on the side of
2 triangles each (e.g. see Figure 6) so to make up
![s](https://s0.wp.com/latex.php?latex=s&bg=ffffff&fg=333333&s=0 "s") we
have count them twice. Thus, we can write
![s=B+2(E\_t-B)](https://s0.wp.com/latex.php?latex=s%3DB%2B2%28E_t-B%29&bg=ffffff&fg=333333&s=0
"s=B+2(E_t-B)").

Thus, we get:  
![B+2(E\_t-B)=3F\_t; \\; \\therefore
B=2E\_t-3F\_t](https://s0.wp.com/latex.php?latex=B%2B2%28E_t-B%29%3D3F_t%3B+%5C%3B+%5Ctherefore+B%3D2E_t-3F_t&bg=ffffff&fg=333333&s=0
"B+2(E_t-B)=3F_t; \\; \\therefore B=2E_t-3F_t")  
From the triangulation theorem and
![I=V\_t-B](https://s0.wp.com/latex.php?latex=I%3DV_t-B&bg=ffffff&fg=333333&s=0
"I=V_t-B") we can write: ![F\_t=2V\_t-2B+B-2; \\therefore
F\_t=2V\_t-B-2](https://s0.wp.com/latex.php?latex=F_t%3D2V_t-2B%2BB-2%3B+%5Ctherefore+F_t%3D2V_t-B-2&bg=ffffff&fg=333333&s=0
"F_t=2V_t-2B+B-2; \\therefore F_t=2V_t-B-2")  
Plugging the above value of
![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0 "B")
into this we get: ![F\_t=2V\_t-2E\_t+3F\_t-2; \\; \\therefore
F\_t+V\_t-E\_t=T=1](https://s0.wp.com/latex.php?latex=F_t%3D2V_t-2E_t%2B3F_t-2%3B+%5C%3B+%5Ctherefore+F_t%2BV_t-E_t%3DT%3D1&bg=ffffff&fg=333333&s=0
"F_t=2V_t-2E_t+3F_t-2; \\; \\therefore F_t+V_t-E_t=T=1")  
Since
![P=T](https://s0.wp.com/latex.php?latex=P%3DT&bg=ffffff&fg=333333&s=0
"P=T"), it follows that
![F+V=E+1](https://s0.wp.com/latex.php?latex=F%2BV%3DE%2B1&bg=ffffff&fg=333333&s=0
"F+V=E+1") for a polygonal tiling. From this it follows that:  
![F+V=E+2 \\;\\;
\_\\blacksquare](https://s0.wp.com/latex.php?latex=F%2BV%3DE%2B2+%5C%3B%5C%3B+_%5Cblacksquare&bg=ffffff&fg=333333&s=0
"F+V=E+2 \\;\\; _\\blacksquare")

**Back to the Platonic solids**  
We may next ask: Given Euler’s theorem can we prove that there are only
5 Platonic solids? To answer this we need to prove two further
relationships first. For this we take into account that a Platonic
polyhedron has regular polygons as its faces and that each vertex must
necessarily belong to the same number of polygonal faces. Let
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") be
the number of edges of the regular polygonal face of a Platonic solid.
Let ![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0
"m") be the number of edges of meeting at any given vertex of a Platonic
solid. Let
![s](https://s0.wp.com/latex.php?latex=s&bg=ffffff&fg=333333&s=0 "s") be
the sum of the number of sides of all polygonal faces of a Platonic
solid counting redundantly. Given that we have
![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0 "F")
faces in the solid, we get
![s=nF](https://s0.wp.com/latex.php?latex=s%3DnF&bg=ffffff&fg=333333&s=0
"s=nF"). Given that we have
![V](https://s0.wp.com/latex.php?latex=V&bg=ffffff&fg=333333&s=0 "V")
vertices with
![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0 "m")
edges meeting at each of them we get
![s=mV](https://s0.wp.com/latex.php?latex=s%3DmV&bg=ffffff&fg=333333&s=0
"s=mV"). Finally, we note that each edge of the polyhedron
simultaneously belongs to 2 of its polygonal faces; hence, we get
![s=2E](https://s0.wp.com/latex.php?latex=s%3D2E&bg=ffffff&fg=333333&s=0
"s=2E"). From this we get the relationship for any Platonic solid:
![2E=nF=mV](https://s0.wp.com/latex.php?latex=2E%3DnF%3DmV&bg=ffffff&fg=333333&s=0
"2E=nF=mV"). For example, in an octahedron we have ![E=12, n=3,
m=4](https://s0.wp.com/latex.php?latex=E%3D12%2C+n%3D3%2C+m%3D4&bg=ffffff&fg=333333&s=0
"E=12, n=3, m=4"); thus, ![2\\times 12=3 \\times 8 = 4 \\times
6=24](https://s0.wp.com/latex.php?latex=2%5Ctimes+12%3D3+%5Ctimes+8+%3D+4+%5Ctimes+6%3D24&bg=ffffff&fg=333333&s=0
"2\\times 12=3 \\times 8 = 4 \\times 6=24").

From the above we have for a Platonic solid: ![F=\\tfrac{2E}{n},
V=\\tfrac{2E}{m}](https://s0.wp.com/latex.php?latex=F%3D%5Ctfrac%7B2E%7D%7Bn%7D%2C+V%3D%5Ctfrac%7B2E%7D%7Bm%7D&bg=ffffff&fg=333333&s=0
"F=\\tfrac{2E}{n}, V=\\tfrac{2E}{m}")

Next, we plug the above into Euler’s formula
![F+V=E+2](https://s0.wp.com/latex.php?latex=F%2BV%3DE%2B2&bg=ffffff&fg=333333&s=0
"F+V=E+2") to get:  
![\\tfrac{2E}{n}+\\tfrac{2E}{m}-E=2\\\\\[7pt\]
\\tfrac{2}{n}+\\tfrac{2}{m}-1=\\tfrac{2}{E}\\\\\[7pt\] \\therefore
\\tfrac{2}{n}+\\tfrac{2}{m}-1\>0\\\\\[7pt\] \\therefore
\\tfrac{2}{n}+\\tfrac{2}{m}\>1](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B2E%7D%7Bn%7D%2B%5Ctfrac%7B2E%7D%7Bm%7D-E%3D2%5C%5C%5B7pt%5D+%5Ctfrac%7B2%7D%7Bn%7D%2B%5Ctfrac%7B2%7D%7Bm%7D-1%3D%5Ctfrac%7B2%7D%7BE%7D%5C%5C%5B7pt%5D+%5Ctherefore+%5Ctfrac%7B2%7D%7Bn%7D%2B%5Ctfrac%7B2%7D%7Bm%7D-1%3E0%5C%5C%5B7pt%5D+%5Ctherefore+%5Ctfrac%7B2%7D%7Bn%7D%2B%5Ctfrac%7B2%7D%7Bm%7D%3E1&bg=ffffff&fg=333333&s=0
"\\tfrac{2E}{n}+\\tfrac{2E}{m}-E=2\\\\[7pt] \\tfrac{2}{n}+\\tfrac{2}{m}-1=\\tfrac{2}{E}\\\\[7pt] \\therefore \\tfrac{2}{n}+\\tfrac{2}{m}-1\>0\\\\[7pt] \\therefore \\tfrac{2}{n}+\\tfrac{2}{m}\>1")

By multiplying both sides by
![nm](https://s0.wp.com/latex.php?latex=nm&bg=ffffff&fg=333333&s=0 "nm")
we get the Eulerian inequality for a Platonic solid:
![2m+2n\>nm](https://s0.wp.com/latex.php?latex=2m%2B2n%3Enm&bg=ffffff&fg=333333&s=0
"2m+2n\>nm")

We can now use this to prove that there can be only 5 Platonic solids.
For this we should first keep in mind that to have a solid at least 3
faces should meet at a vertex; hence, minimally
![m=3](https://s0.wp.com/latex.php?latex=m%3D3&bg=ffffff&fg=333333&s=0
"m=3"). We then begin with a triangular face
![n=3](https://s0.wp.com/latex.php?latex=n%3D3&bg=ffffff&fg=333333&s=0
"n=3") and plug it into the Eulerian inequality:

![2m+6\>3m;\\; \\therefore
m\<6](https://s0.wp.com/latex.php?latex=2m%2B6%3E3m%3B%5C%3B+%5Ctherefore+m%3C6&bg=ffffff&fg=333333&s=0
"2m+6\>3m;\\; \\therefore m\<6")  
Thus, for a triangle, ![m=3, 4,
5](https://s0.wp.com/latex.php?latex=m%3D3%2C+4%2C+5&bg=ffffff&fg=333333&s=0
"m=3, 4, 5"): these yield the tetrahedron, octahedron and icosahedron.

Next we take a square face
![n=4](https://s0.wp.com/latex.php?latex=n%3D4&bg=ffffff&fg=333333&s=0
"n=4")  
![2m+8\>4m;\\; \\therefore
m\<4](https://s0.wp.com/latex.php?latex=2m%2B8%3E4m%3B%5C%3B+%5Ctherefore+m%3C4&bg=ffffff&fg=333333&s=0
"2m+8\>4m;\\; \\therefore m\<4")  
Thus, we can only have
![m=3](https://s0.wp.com/latex.php?latex=m%3D3&bg=ffffff&fg=333333&s=0
"m=3") for a square face and we get the cube.

Next we take a pentagonal face
![n=5](https://s0.wp.com/latex.php?latex=n%3D5&bg=ffffff&fg=333333&s=0
"n=5")  
![2m+10\>5m;\\; \\therefore
m\<\\tfrac{10}{3}](https://s0.wp.com/latex.php?latex=2m%2B10%3E5m%3B%5C%3B+%5Ctherefore+m%3C%5Ctfrac%7B10%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"2m+10\>5m;\\; \\therefore m\<\\tfrac{10}{3}")  
Thus, we can only have
![m=3](https://s0.wp.com/latex.php?latex=m%3D3&bg=ffffff&fg=333333&s=0
"m=3") for a pentagonal face and we get the dodecahedron.

Next we take a hexagonal face
![n=6](https://s0.wp.com/latex.php?latex=n%3D6&bg=ffffff&fg=333333&s=0
"n=6")  
![2m+12\>6m;\\; \\therefore
m\<3](https://s0.wp.com/latex.php?latex=2m%2B12%3E6m%3B%5C%3B+%5Ctherefore+m%3C3&bg=ffffff&fg=333333&s=0
"2m+12\>6m;\\; \\therefore m\<3")  
Thus, we cannot get any polyhedron because
![m\<3](https://s0.wp.com/latex.php?latex=m%3C3&bg=ffffff&fg=333333&s=0
"m\<3"). The same applies for any
![n\>6](https://s0.wp.com/latex.php?latex=n%3E6&bg=ffffff&fg=333333&s=0
"n\>6"). Thus there can only be 5 Platonic solids
![\_\\blacksquare](https://s0.wp.com/latex.php?latex=_%5Cblacksquare&bg=ffffff&fg=333333&s=0
"_\\blacksquare")

**Tailpiece**  
While we can have infinite regular polygons, only the first 3 of them
yield a total of just 5 Platonic solids. This is a strong constraint in
3D space; thus, one would expect these Platonic ideals to occur as
reflections throughout nature. Indeed, that is the case and we may note
the following:  
1\) The 4 bonds formed by the
![sp^3](https://s0.wp.com/latex.php?latex=sp%5E3&bg=ffffff&fg=333333&s=0
"sp^3") hybridized orbitals of carbon define a tetrahedron. Similarly,
phosphates
![PO\_4^{3-}](https://s0.wp.com/latex.php?latex=PO_4%5E%7B3-%7D&bg=ffffff&fg=333333&s=0
"PO_4^{3-}"), such as those forming the backbone of DNA and RNA also
assume a tetrahedral geometry.
![Fe\_3O\_4](https://s0.wp.com/latex.php?latex=Fe_3O_4&bg=ffffff&fg=333333&s=0
"Fe_3O_4") assumes tetrahedral crystals. Thus, the tetrahedron is a
fundamental structure of nature and life.  
2\) The cube is a ubiquitous habit of crystals:
![NaCl](https://s0.wp.com/latex.php?latex=NaCl&bg=ffffff&fg=333333&s=0
"NaCl") is a good example of such.  
3\) The octahedron is the habit of diamond and alum ![KAl(SO\_4)\_2
\\cdot
12H\_2O](https://s0.wp.com/latex.php?latex=KAl%28SO_4%29_2+%5Ccdot+12H_2O&bg=ffffff&fg=333333&s=0
"KAl(SO_4)_2 \\cdot 12H_2O").  
4\) The dodecahedron is the habit of the quasi-crystal of the
holmium–magnesium–zinc alloy. The RNA of certain nodaviruses is packed
in a dodecahedral form within their capsids.  
5\) The icosahedron is famously the form of the capsids of numerous
viruses. It is also seen in some non-viral protein assemblies like those
which form the propanediol utilizing and ethanolamine utilizing
bacterial microcompartments.

In the human world, a deliberately made cube used as a gaming die and a
fixed weight was seen among the Harappan people of bronze age India.
Harappans also made regular tetrahedral weights, such as those found in
Mohenjo daro. Some believe that the occurrence of pyrites which are
found in certain places in Italy and naturally assume the forms of
cubes, dodecahedra and icosahedra might have inspired the yavana-s to
think about these solids. Among the yavana-s, we are informed by Proclus
that Pythagoras was the first to discover the Platonic solids. However,
there is no evidence that he actually knew all 5 of them and that there
were only 5. Plato mentions them in his Timaeus and by then it was known
that there are 5 of them. It is believed that Plato obtained that
knowledge from Theaetetus, his mathematical interlocutor, who is
believed to have first recognized all 5 of them. However, the evidence
for this comes from an apocryphal commentary on Euclid. Plato thought
that the tetrahedron, octahedron, cube and icosahedron corresponded to
the 4 “elements” of Greek tradition: fire, air, earth and water. He then
added that a god used the dodecahedron “for embroidering the
constellations on the whole heaven.” This is perhaps an allusion to the
12 Zodiacal constellations of the Greeks. It is also held that
Theaetetus’ explorations inspired the *Elements*, where Euclid
presumably following his successors gives these 5 Platonic polyhedra and
indicates that there are only 5 of them. Material evidence for their
recognition in the Classical world comes from the discovery of the
icosahedral dice from Ptolemaic Egypt. Further, the Romans made metal
dodecahedra and icosahedra (mostly the former), whose function remains
unknown to date as far as we know.

In Indian mathematics we are unaware of a specific mention of Platonic
solids as a group. However, we have evidence for a “ghost-lineage” of
Hindu mathematical knowledge regarding Platonic solids in the form of
beads shaped as those solids from at least the Gupta age. There is a
persistent belief among white indologists and their imitators that Hindu
mathematical tradition is a poor derivative of the Mesopotamian and
Greek traditions. However, there is absolutely no evidence for
transmission of Greek texts with knowledge of Platonic solids to Hindus
prior to the 1700s of the common era. Thus, there is no evidence that
the Indian production of Platonic solids was inspired by the Greek
textual tradition. One may point out that their emergence in Indian art
is approximately contemporaneous with their emergence in material
depictions in the Classical world. However, the Indian versions are not
used as dice as in Ptolemaic Egypt or as made like or of the large size
of their Roman counterparts. They are part of a distinctly Indian use in
jewelry. Indeed, in this regard one may point out that already in the
Sāmaññaphala-sutta-84 the tāthāgata mentions such a well-polished
octahedral bead. One may also note that some tāthāgata atomic theories
in India saw substances as being formed from their constituent molecules
by an octahedral packing. It is also notable that this style of
polyhedral beads was transmitted to Myanmar, Thailand and Vietnam along
with early gold-working traditions and at least dodecahedral and
octahedral beads have been found in those regions.
