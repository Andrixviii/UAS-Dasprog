# Ujian Akhir Semester 
<br>Mata Kuliah 	: DASAR PEMROGRMAN
<br>Nama :MUHAMAD NOPID ANDRIANSYAH
<br>NIM		:	1227050091
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum

## Source Code
```
#include <iostream>
using namespace std;

int main()
{
 int arr[2][2], transpose[2][2], baris, kolom;
 
 cout << "baris: "; cin >> baris;
 cout << "kolom: "; cin >> kolom;
 
 cout << "\n";
 for(int i=0; i<baris; i++){
  for(int j=0; j<kolom; j++){
   cout << "["<<i<<j<<"]: ";
   	cin >> arr[i][j];
  }
 }
 
 cout << "\n";
 
 for(int i=0; i<baris; i++){
  for(int j=0; j<kolom; j++){
   cout << arr[i][j] << " ";
   if(j == kolom - 1);
  }
  cout << "\n";
 }
 
 cout << "\n";
 
 for(int i=0; i<baris; i++){
  for(int j=0; j<kolom; j++){
   transpose[j][i] = arr[i][j];
  }
 }
 
 for(int i=0; i<kolom; i++){
  for(int j=0; j<baris; j++){
   cout << transpose[i][j] << " ";
   if(j == baris - 1);
  }
  cout << "\n";
 }
  return 0;
}
```
## Output

<img src="output1.1.png">
