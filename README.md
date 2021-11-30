

#include <iostream>
using namespace std;

int main() { int A[3][2]={{1,2},{3,4},{5,6}}; 
int B[3][2]={{7,8},{9,10},{11,12}};
int C[3][2];
int i,j;

cout<<"Matrik A = \n"; 
for(i=0; i<3 ; i++){ for(j=0; j<2 ; j++) 
cout<<A[i][j]<<" "; 
cout<<endl; } cout<<"Matrik B = \n";
for(i=0; i<3 ; i++)
{ for(j=0; j<2 ; j++)
cout<<B[i][j]<<" "; 
cout<<endl; }
//penjumlahan matrix for(i=0; i<3 ; i++) for(j=0; j<2 ; j++) C[i][j]=A[i][j] + B[i][j];

cout<<"Matrik C = \n"; 
for(i=0; i<3 ; i++){ for(j=0; j<2 ; j++) 
cout<<C[i][j]<<" ";
cout<<endl; }

return 0;

}
