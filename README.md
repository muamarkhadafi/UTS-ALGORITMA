# UTS_Algoritma
**Muamar khadafi**
**TI.18.A.2**
**311810656**

**Soal1.cpp**

**Alur Program**

1. Deklarasi variable A,B,X,Y,sebagai variable input
2. Menbaca input key board cin >> A >> B >> X >> Y >>.
3. Membandingkan Variable **X** dengan **Y** jika sama.
4. karna statement **false** tidak akan terjadi ```{X!=Y}```.
5. dan jika statement **True** maka akan terjadi **X<Y** .
6. jika statment ini **True** maka hasinya  X = X + A
7. dan jika statment **False** maka hasilnya  Y = Y + B.
8. Disini terjadi pengulangan untuk mencari niai X .
9. Terakhir cetak X.

**Code Program**

```c++

#include<iosteam>

using namespace std;

int main(){
    int A,B,X,Y;
    cout << "Masukan Variable X =";cin >>A;
    cout <<" Masukan Variable y =";cin >>B;

    X = A;
    Y = B;
    if (X!=Y){
       if(X < Y)
         (X = X + A);
       else
	 (Y = Y + B);

    }
  
    cout << X;

}

```
*Soal2.cpp**

1. deklarasi varaible input N,X,T, Batas;
sebagai inputnya
2. memasukan nilai N yaitu 2 angka terakhir saya, maka N adalah 78
dan batasnya adalah 210 dari hasil jumlah N + 140,.
3. masukan variable X, dan T, X nya adalah 20 dan kemudian T adalah 78(dari N).
4. dimana T kurang dari sama dengan batas, berarti tidak boleh melebihi batas 
5. kemudian menghitung ```X = X + 10;
```,dan hasinya 30 kemudian menghitung ```
T = T + X;```,
hasilnya adalah 108.
6. kemudian cetak variable T 

**Code Program**

```c++

#include<iostream>
#include <math.h>
using namespace std;

int main()
{
    int N,X,T,Batas;
    cout << "masukan nilai N dengan dua NIM terakhir : " ; cin >> N ;
    Batas = N + 100;
    X = 20;
    T = N;
    while( T <= Batas)
{ T = T + X;
X = X + 10;
}
cout <<"hasilnya adalah :" << T <<endl;
}
 
```
**Terima Kasih** # UTS-ALGORITMA
