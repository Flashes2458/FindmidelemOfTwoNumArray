#include <iostream>
using namespace std;

int findmid(int A[],int B[],int n){
	int i=0,j=0,count=1;
	while(count<n){
		(A[i]<=B[j])?++i:++j;
		count++;
	}
	
		if(A[i]<=B[j])
			return A[i];
		else
			return B[j];
}
	
int main()
{
	int L1[5]={1,3,5,7,9};
	int L2[5]={2,4,6,8,10};
	
   cout << findmid(L1,L2,5);
   return 0;
}
