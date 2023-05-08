Download Link: https://assignmentchef.com/product/solved-solved-fundamentals-of-linear-algebra-and-optimization-homework-2
<br>
Problem B5 (120 pts). (Haar extravaganza) Consider the matrixW3,3 =Problem B1 (10 pts). Given any m × n matrix A and any n × p matrix B, if we denote the columns of A by A1, . . . , An and the rows of B by B1, . . . , Bn, prove thatAB = A1B1 + · · · + AnBn.Problem B2 (10 pts). Let f : E → F be a linear map which is also a bijection (it isinjective and surjective). Prove that the inverse function f−1: F → E is linear.Problem B3 (10 pts). Given two vectors spaces E and F, let (ui)i∈I be any basis of E and let (vi)i∈I be any family of vectors in F. Prove that the unique linear map f : E → Fsuch that f(ui) = vifor all i ∈ I is surjective iff (vi)i∈I spans F.Problem B4 (10 pts). Let f : E → F be a linear map with dim(E) = n and dim(F) = m.Prove that f has rank 1 iff f is represented by an m × n matrix of the formA = uvwith u a nonzero column vector of dimension m and v a nonzero column vector of dimensionn.1 0 0 0 1 0 0 01 0 0 0 −1 0 0 00 1 0 0 0 1 0 00 1 0 0 0 −1 0 00 0 1 0 0 0 1 00 0 1 0 0 0 −1 00 0 0 1 0 0 0 10 0 0 1 0 0 0 −1(1) Show that given any vector c = (c1, c2, c3, c4, c5, c6, c7, c8), the result W3,3c of applyingW3,3 to c isW3,3c = (c1 + c5, c1 − c5, c2 + c6, c2 − c6, c3 + c7, c3 − c7, c4 + c8, c4 − c8),1the last step in reconstructing a vector from its Haar coefficients.(2) Prove that the inverse of W3,3 is (1/2)W3,3. Prove that the columns and the rows ofW3,3 are orthogonal.(3) Let W3,2 and W3,1 be the following matrices:W3,2 =1 0 1 0 0 0 0 01 0 −1 0 0 0 0 00 1 0 1 0 0 0 00 1 0 −1 0 0 0 00 0 0 0 1 0 0 00 0 0 0 0 1 0 00 0 0 0 0 0 1 00 0 0 0 0 0 0 1, W3,1 =1 1 0 0 0 0 0 01 −1 0 0 0 0 0 00 0 1 0 0 0 0 00 0 0 1 0 0 0 00 0 0 0 1 0 0 00 0 0 0 0 1 0 00 0 0 0 0 0 1 00 0 0 0 0 0 0 1.Show that given any vector c = (c1, c2, c3, c4, c5, c6, c7, c8), the result W3,2c of applying W3,2to c isW3,2c = (c1 + c3, c1 − c3, c2 + c4, c2 − c4, c5, c6, c7, c8),the second step in reconstructing a vector from its Haar coefficients, and the result W3,1c ofapplying W3,1 to c isW3,1c = (c1 + c2, c1 − c2, c3, c4, c5, c6, c7, c8),the first step in reconstructing a vector from its Haar coefficients.Conclude thatW3,3W3,2W3,1 = W3,the Haar matrixW3 =1 1 1 0 1 0 0 01 1 1 0 −1 0 0 01 1 −1 0 0 1 0 01 1 −1 0 0 −1 0 01 −1 0 1 0 0 1 01 −1 0 1 0 0 −1 01 −1 0 −1 0 0 0 11 −1 0 −1 0 0 0 −1.Hint. First, check thatW3,2W3,1 =

W2 04,404,4 I4

,whereW2 =1 1 1 01 1 −1 01 −1 0 11 −1 0 −1 .2(4) Prove that the columns and the rows of W3,2 and W3,1 are orthogonal. Deduce fromthis that the columns of W3 are orthogonal, and the rows of W−13are orthogonal. Are therows of W3 orthogonal? Are the columns of W−13orthogonal? Find the inverse of W3,2 andthe inverse of W3,1.(5) For any n ≥ 2, the 2n × 2n matrix Wn,n is obtained form the two rows1, 0, . . . , 0| {z }2n−1, 1, 0, . . . , 0| {z }2n−11, 0, . . . , 0| {z }2n−1, −1, 0, . . . , 0| {z }2n−1by shifting them 2n−1 − 1 times over to the right by inserting a zero on the left each time.Given any vector c = (c1, c2, . . . , c2n ), show that Wn,nc is the result of the last step in theprocess of reconstructing a vector from its Haar coefficients c. Prove that W−1n,n = (1/2)Wn,n,and that the columns and the rows of Wn,n are orthogonal.Extra credit (30 pts.)Given a m × n matrix A = (aij ) and a p × q matrix B = (bij ), the Kronecker product (ortensor product) A ⊗ B of A and B is the mp × nq matrixA ⊗ B =a11B a12B · · · a1nBa21B a22B · · · a2nB............am1B am2B · · · amnB.It can be shown (and you may use these facts without proof) that ⊗ is associative and that(A ⊗ B)(C ⊗ D) = AC ⊗ BD(A ⊗ B)= A⊗ B,whenever AC and BD are well defined.Check thatWn,n =

I2n−1 ⊗

11

I2n−1 ⊗

1−1,and thatWn =

Wn−1 ⊗

11

I2n−1 ⊗

1−1.Use the above to reprove thatWn,nWn,n = 2I2n .3LetB1 = 21 00 1=

2 00 2and for n ≥ 1,Bn+1 = 2Bn 00 I2n

.Prove thatWn Wn = Bn, for all n ≥ 1.(6) The matrix Wn,i is obtained from the matrix Wi,i (1 ≤ i ≤ n − 1) as follows:Wn,i =

Wi,i 02i,2n−2i02n−2i,2i I2n−2i

.It consists of four blocks, where 02i,2n−2i and 02n−2i,2i are matrices of zeros and I2n−2i is theidentity matrix of dimension 2n − 2i.Explain what Wn,i does to c and prove thatWn,nWn,n−1 · · · Wn,1 = Wn,where Wn is the Haar matrix of dimension 2n.Hint. Use induction on k, with the induction hypothesisWn,kWn,k−1 · · · Wn,1 =

Wk 02k,2n−2k02n−2k,2k I2n−2k

.Prove that the columns and rows of Wn,k are orthogonal, and use this to prove that thecolumns of Wn and the rows of W−1nare orthogonal. Are the rows of Wn orthogonal? Arethe columns of W−1northogonal? Prove thatW−1n,k =12Wk,k 02k,2n−2k02n−2k,2k I2n−2k

.Problem B6 (20 pts). Prove that for every vector space E, if f : E → E is an idempotentlinear map, i.e., f ◦ f = f, then we have a direct sumE = Ker f ⊕ Im f,so that f is the projection onto its image Im f.Problem B7 (20 pts). Let U1, . . . , Up be any p ≥ 2 subspaces of some vector space E andrecall that the linear mapa: U1 × · · · × Up → E4is given bya(u1, . . . , up) = u1 + · · · + up,with ui ∈ Uifor i = 1, . . . , p.(1) If we let Zi ⊆ U1 × · · · × Up be given byZi =

u1, . . . , ui−1, −Xpj=1,j6=iuj, ui+1, . . . , up

Xpj=1,j6=iuj ∈ Ui ∩Xpj=1,j6=iUj,for i = 1, . . . , p, then prove thatKer a = Z1 = · · · = Zp.In general, for any given i, the condition Ui ∩Ppj=1,j6=i Uj

= (0) does not necessarilyimply that Zi = (0). Thus, letZ =

u1, . . . , ui−1, ui, ui+1, . . . , up

ui = −Xpj=1,j6=iuj, ui ∈ Ui ∩Xpj=1,j6=iUj

, 1 ≤ i ≤ p

.Since Ker a = Z1 = · · · = Zp, we have Z = Ker a. Prove that ifUi ∩Xpj=1,j6=iUj

= (0) 1 ≤ i ≤ p,then Z = Ker a = (0).(2) Prove that U1 + · · · + Up is a direct sum iffUi ∩Xpj=1,j6=iUj

= (0) 1 ≤ i ≤ p.(3) Extra credit (40 pts). Assume that E is finite-dimensional, and let fi: E → E be anyp ≥ 2 linear maps such thatf1 + · · · + fp = idE.Prove that the following properties are equivalent:(1) f2i = fi, 1 ≤ i ≤ p.(2) fj ◦ fi = 0, for all i 6= j, 1 ≤ i, j ≤ p.TOTAL: 200 + 70 points.5