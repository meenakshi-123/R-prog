## Put comments here that give an overall description of what your
## functions do

## Write a short comment describing this function

## free variable
x<-matrix (c(1,1,4,0,3,1,4,4,0),3,3) ## Can  change the value as per require.

makeCacheMatrix <- function(x = matrix()) { 

  if(det(x)!= 0) ## Inverse Matrixs are possible if only Determinent 
                 # of matrix is not equel to 0 
      {
    catchsolve<- solve(x)  # catching the  inverse matrix
    print(catchsolve)      # printing it  
  }
  else { P<-"No invers of this matrix as determinent =0"
        print(P)
   }
  }
    
####
# pass th value of matrix in function makeCacheMatrix()
