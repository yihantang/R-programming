# module 6 
#Consider A=matrix(c(2,0,1,3), ncol=2) and B=matrix(c(5,2,4,-1), ncol=2).
#a) Find A + B
#b) Find A - B

A=matrix(c(2,0,1,3), ncol=2
B=matrix(c(5,2,4,-1), ncol=2

A+B
A-B

#Using the diag() function to build a matrix of size 4 with the following values in the diagonal 4,1,2,3.
x<-c(4,1,2,3)
diag(x)

#Generate the matrix 
y<- c( 0, 3, 3, 3, 3)

A<-diag(y)
A
B<-sweep(A,1, c(1, 0, 0, 0, 0), FUN = "+")
B
C<-sweep(B,2, c(2, 0, 0, 0, 0), FUN = "+")
C
