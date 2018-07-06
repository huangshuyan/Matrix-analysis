# Vector

#### Basics

+ vectors are writen in column format usually.

#### Vector space

+ A ***vector space***  <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/c91091e68f0e0113ff161179172813ac.svg?invert_in_darkmode" align=middle width=10.285440000000003pt height=14.155350000000013pt/> is obtained by equipping vectors with the operations of + and <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/bdbf342b57819773421273d508dba586.svg?invert_in_darkmode" align=middle width=12.785520000000004pt height=19.178279999999994pt/>  by scalar.

#### Subspaces and span

+ A nonempty subset  <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/b49211c7e49541e500c32b4d56d354dc.svg?invert_in_darkmode" align=middle width=9.166740000000003pt height=14.155350000000013pt/> of a vector space <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/c91091e68f0e0113ff161179172813ac.svg?invert_in_darkmode" align=middle width=10.285440000000003pt height=14.155350000000013pt/> is called a ***subspace*** of <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/c91091e68f0e0113ff161179172813ac.svg?invert_in_darkmode" align=middle width=10.285440000000003pt height=14.155350000000013pt/>, if for any scalars <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/d7093223b4d827e8c29d4ed84b7ae088.svg?invert_in_darkmode" align=middle width=28.048020000000005pt height=22.831379999999992pt/>,  x, y <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/f8964a7ba923ddf19d88f09e2a01a983.svg?invert_in_darkmode" align=middle width=154.83599999999998pt height=22.831379999999992pt/>.  
+ span(S) is the set of all possible linear combinations of the vectors in S = {<img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/8e960e51abb999eb0c0557dfe3bdf613.svg?invert_in_darkmode" align=middle width=72.989235pt height=29.19113999999999pt/>} forms a subspace.

#### Bases and dimensions

+ *Linearly independent* if no vectors in the collection can be expressed as a linear combination of the others. 
+ A ***basis*** of <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode" align=middle width=11.027445000000004pt height=22.46574pt/> is a set of <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode" align=middle width=13.293555000000003pt height=22.46574pt/> of vectors of minimal cadinality, such that <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/ba6b5c087ac709bc87785ac09cc4dea9.svg?invert_in_darkmode" align=middle width=93.55599pt height=24.65759999999998pt/>. The **cardinality** of a basis is called *the dimension of <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode" align=middle width=11.027445000000004pt height=22.46574pt/>*.   

#### Affine sets

+ <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/ed19d82a1ca5c53a66ea7b9cb7b55711.svg?invert_in_darkmode" align=middle width=236.28115499999996pt height=29.19113999999999pt/> where <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/f588ecf6bbd7412ba39cae19051d2bd0.svg?invert_in_darkmode" align=middle width=26.221635000000003pt height=29.19113999999999pt/> is a given point and <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/b49211c7e49541e500c32b4d56d354dc.svg?invert_in_darkmode" align=middle width=9.166740000000003pt height=14.155350000000013pt/> is a given subspace of <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/c91091e68f0e0113ff161179172813ac.svg?invert_in_darkmode" align=middle width=10.285440000000003pt height=14.155350000000013pt/>. (一个过点<img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/f588ecf6bbd7412ba39cae19051d2bd0.svg?invert_in_darkmode" align=middle width=26.221635000000003pt height=29.19113999999999pt/>的平面)
+ A *line* is a one-dimensional affine set. The line through <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/e714a3139958da04b41e3e607a544455.svg?invert_in_darkmode" align=middle width=15.947580000000002pt height=14.155350000000013pt/> along direction <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/6dbb78540bd76da3f1625782d42d6d16.svg?invert_in_darkmode" align=middle width=9.410280000000004pt height=14.155350000000013pt/> is the set <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/44986546489ed08e4188f437af8b028b.svg?invert_in_darkmode" align=middle width=272.427705pt height=24.65759999999998pt/>, where in this case span(u) = {<img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/5ee08d8e80df8fadefed766ad8633273.svg?invert_in_darkmode" align=middle width=74.250165pt height=22.831379999999992pt/>}. 

#### Euclidean length

<p align="center"><img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/8b19cfc89dd25f4f4b209c75f558721d.svg?invert_in_darkmode" align=middle width=169.0392pt height=29.589285pt/></p>

直线长度

####  Norms and <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/247ca9d8cf371e16f3db4442254b82af.svg?invert_in_darkmode" align=middle width=11.681340000000004pt height=22.831379999999992pt/> norms

<p align="center"><img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/13b2bc39fab5297ed9ed4fe46b791e56.svg?invert_in_darkmode" align=middle width=207.46935pt height=45.274184999999996pt/></p>

+ p = 2 is the standard Euclidean length
+ p = 1 is the sum-of-absolute-values length
+ p = <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/f7a0f24dc1f54ce82fecccbbf48fca93.svg?invert_in_darkmode" align=middle width=16.438455000000005pt height=14.155350000000013pt/> defines the <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/44c7bc81737b655015b112940a6f4023.svg?invert_in_darkmode" align=middle width=156.56256000000002pt height=24.65759999999998pt/>
+ <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/1d3f36f63b284963559aa85e9c785269.svg?invert_in_darkmode" align=middle width=32.38603500000001pt height=24.65759999999998pt/> is the cardinality of a vector x. <img src="https://rawgit.com/huangshuyan/Matrix-analysis (fetch/None/svgs/0726b59a0f83a46e5353412ea550d6ad.svg?invert_in_darkmode" align=middle width=11.457435000000004pt height=22.831379999999992pt/> (pseudo) norm.

#### Inner product



















