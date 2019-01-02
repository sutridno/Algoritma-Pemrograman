=========================
 Algoritma & Pemrograman
=========================


/*
*
* Program Luas Persegi Panjang
*
*/
#include<iostream>
using namespace std;
int main () {
	int p, l, luas;
	
	cout<<"masukan panjang:";
	cin>>p;
	cout<<"masukan lebar:";
	cin>>l;
	luas=p*l;
	cout<<"luas persegi panjang adalah"<<luas;
	return 0;
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Menghitung upah gaji perjam
*
*/
	#include <iostream>
	using namespace std;
	
	int main ()
	{
		int gaji,j;
		cout <<"Masukan Berapa Jam anda Kerja : ";
		cin >>j;
		
		//Rumus
		gaji = 5000 * j;
		cout<<"Gaji yang Anda Dapatkan adalah = " <<gaji;
		
		return 0;
	}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* konversi dollar ke rupiah
*
*/
	#include <iostream>
	using namespace std;
	
	int main ()
	{
		int Rp,Dollar;
		cout <<"Masukan Nilai Dollar ayng ingin di konvers ke Rupiah : ";
		cin >>Dollar;
		
		Rp = 15149 * Dollar;
		cout <<"Hasil konvers Dollar ke Rupiah adalah = " <<Rp;
		
		return 0;
	}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* menghitung detik, jam, menit
*
*/

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Menghitung suhu
*
*/
#include <stdio.h>
#include <conio.h>

int main()
{
	float c, r, f,k;
	printf("		PROGRAM KONVERSI SUHU DARI CELCIUS KE :		\n");
	printf("			FAHRENHEIT | REAMUR		   	\n");
	printf("                  BY DONI IRAWAN 311810530 STT 18 B2");
	printf("				    	 		INSTITUT PELITA BANGSA\n\n");
	printf("masukan besar suhu dalam celcius : ");
	scanf("%f", &c);
	f=(c*1.8)+32;
	printf("suhu dalam fahrenheit : %.2f Fahrenheit\n", f);
	r=(c*0.8);
	printf("suhu dalam Reamur: %2f Reamur\n", r);
	getch();
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Penghitung rumus E=MC
*
*/
#include<iostream>
using namespace std;
int main() {
	int C,M, E;

	cout<<"masukan C:";
	cin>>C;
	cout<<"masukan M:";
	cin>>M;
	E=(C * M)*(C * M);
	cout<<"hasil kuadrat CMadalah"<<E;
	return 0;
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Menghitung luas lingkaran
*
*/
#include <stdio.h>
const float phi = 3.14;
const char nama[] = "Sutrisno";

int main () {
	printf("%f\n",phi);
	float luas = 7 * 7 * phi;
	printf("%f\n",luas);
	printf("%s\n",nama);
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Menghitung luas persegi panjang
*
*/
#include<iostream>
using namespace std;
int main () {
	int p, l, luas;

	cout<<"masukan panjang:";
	cin>>p;
	cout<<"masukan lebar:";
	cin>>l;
	luas=p*l;
	cout<<"luas persegi panjang adalah"<<luas;
	return 0;
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Menampilkan Tulisan Algoritma Dan Pemrograman dengan n 30 kali
*
*/
#include<stdio.h>
#include<conio.h>

int ulang (int n);

int main ( void)
{
	int n;
	printf("masukkan nilai (n) :");
	scanf("%d", &n);
	ulang (n);
	getch ();
	
}

int ulang (int n)
{
	int i;
	for(i=1;i<=n;i++)
	printf("Algoritma Dan Pemrograman\n");
	return (i);
	
}
/* end code */
--------------------------------------------------------------------------------------------



/*
*
*Menentukan Bilangan Terkecil Dari 3 Buah Bilangan
*
*/
#include<iostream>

using namespace std;
int main()
{
	int bil1, bil2, bil3, terkecil;
	cout<<"Masukkan Bilangan 1 : ";
	cin>>bil1;
	cout<<"Masukkan Bilangan 2 : ";
	cin>>bil2;
	cout<<"Masukkan Bilangan 3 : ";
	cin>>bil3;
	
	{
		if(bil1 < bil2)
		terkecil = bil1;
		
		else
		terkecil = bil2;
		
		if(bil3 < terkecil)
		terkecil = bil3;
		
		cout<<endl;
		cout<<"Nilai Terkecil = "<<terkecil;cout<<endl;
	}
	return 0;
}
/* end code */
-------------------------------------------------------------------------------------------


/*
*
* Menentukan Bilangan Terkecil Dari 3 Buah Bilangan
*
*/
#include <stdio.h>

int main(){
	int x,y;
	printf(" Program Funsi Untuk Mengetahui Kuadran Suatu Koordinat\n\n");
	printf(" Masukkan Koordinat x : ");
	scanf("%i",&x);
	printf(" Masukkan Koordinat y : ");
	scanf("%i",&y);
	
	if(x>0&&y>0)
		printf("Kuadran I");
	if(x>0&&y<0)
		printf("Kuadran II");
	if(x<0&&y<0)
		printf("Kuadran III");
	if(x==0&&y==0)
		printf("Titik Pusat");
	return 0;
}
/* end code */
-------------------------------------------------------------------------------------------


/*
*
* Mengetahui Kuadran Suatu Koordinat
*
*/
#include <iostream>
#include <conio.h>

using namespace std;

int main(){
	int a=0, b, c, jumlah=0, i, n;
	
	cout<<"Masukkan Jumlah Deret Bilangan\n";
	cout<<"Masukkan Bilangan Awal : ";
	cin>>a;
	cout<<"Masukkan Beda : ";
	cin>>b;
	cout<<"Masukkan Jumlah Sampai Deret Ke-n : ";
	cin>>n;
	
	cout<<"Deret Ke - "<<n<<" : ";
	cout<<a<<",";
	jumlah=jumlah+a;
	for(i=0; i<n-1; i++){
			c=a+b;
			a=c;
			cout<<c<<",";
			jumlah=jumlah+c;
	}
	
	cout<<"\n Jumlah Deret Ke - "<<n<<" : ";
	cout<<jumlah;
	
	getch();
	return 0;
}
/* end code */
-----------------------------------------------------------------------------------------



/*
*
* Menghitung Jumlah Deret
*
*/
#include <iostream>
#include <conio.h>

using namespace std;

int main(){
	int a=0, b, c, jumlah=0, i, n;
	
	cout<<"Masukkan Jumlah Deret Bilangan\n";
	cout<<"Masukkan Bilangan Awal : ";
	cin>>a;
	cout<<"Masukkan Beda : ";
	cin>>b;
	cout<<"Masukkan Jumlah Sampai Deret Ke-n : ";
	cin>>n;
	
	cout<<"Deret Ke - "<<n<<" : ";
	cout<<a<<",";
	jumlah=jumlah+a;
	for(i=0; i<n-1; i++){
			c=a+b;
			a=c;
			cout<<c<<",";
			jumlah=jumlah+c;
	}
	
	cout<<"\n Jumlah Deret Ke - "<<n<<" : ";
	cout<<jumlah;
	
	getch();
	return 0;
}
/* end code */
--------------------------------------------------------------------------------------------



/*
*
* Mengubah Bilangan Pecahan Ke Bilangan Bulat
*
*/
#include<iostream>
using namespace std;
typedef struct pecahan{
	int pb;
	int py;
};
int main(int argc, char *argv[])
{
	pecahan p1,p2;
	cout<<"Masukkan Pembilang = ";
	cin>>p1.pb;
	cout<<"Masukkan Penyebut = ";
	cin>>p1.py;
	cout<<"\t      "<<p1.pb<<endl;
	cout<<"\tp1 =      -"<<endl;
	cout<<"\t      "<<p1.py<<endl;
	if ("/")
	{
		cout<<" Hasilnya = "<<(p1.pb)/(p1.py)<<endl;
	}
	return 0;
}
/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Penjumlahan Pengurangan Perkalian Pembagian 2 Bilangan
*
*/
#include<iostream>
using namespace std;

int penjumlahan(){
	int a,b;
	cout<<"\n Penjumlahan";
	cout<<"\n Masukkan Nilai Bilangan a = ";
	cin>>a;
	cout<<"\n Masukkan Nilai Bilangan b = ";
	cin>>b;
	cout<<"\n Hasil Penjumlahan = "<<a+b;
}

int pengurangan(){
	int a,b;
	cout<<"\n Pengurangan";
	cout<<"\n Masukkan Nilai Bilangan a = ";
	cin>>a;
	cout<<"\n Masukkan Nilai Bilangan b = ";
	cin>>b;
	cout<<"\n Hasil Pengurangan = "<<a-b;
}

int perkalian(){
	int a,b;
	cout<<"\n Perkalian";
	cout<<"\n Masukkan Nilai Bilangan a = ";
	cin>>a;
	cout<<"\n Masukkan Nilai Bilangan b = ";
	cin>>b;
	cout<<"\n Hasil Perkalian = "<<a*b;
}

int pembagian(){
	int a,b;
	cout<<"\n Pembagian";
	cout<<"\n Masukkan Nilai Bilangan a = ";
	cin>>a;
	cout<<"\n Masukkan Nilai Bilangan b = ";
	cin>>b;
	cout<<"\n Hasil Pembagian = "<<a/b;
}

int main(){
	cout<<endl;
	penjumlahan();
	pengurangan();
	perkalian();
	pembagian();
	cout<<endl;


}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Program Menyederhanakan Bilangan Pecahan
*
*/
#include <stdio.h>

int pecahan();
int main()
{
	pecahan();
}
int pecahan()
{
	int a,b,l,t;
	printf("Program Menyederhanakan Bilangan Pecahan\n\n");
	printf("Masukkan Pembilang :");
	scanf("%d",&a);
	printf("Masukkan Penyebut :");
	scanf("%d",&b);
	t=a/b;
	l=a%b;
	if(a%b==0)
		printf("Bilangan(%d/%d)\nDisederhanakan Menjadi %d",a,b,t);
	else if (a%b !=0)
		printf("Bilangan(%d/%d)\nDisederhanakan Menjadi (%d %d-%d)",a,b,t,l,b);
		
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* bilangan ganjil & genap
*
*/
#include <stdio.h>

main()
{
	int x;
	printf("masukan bilangan :");
	scanf("%d",&x);
	if(x%2==0)
	{
		printf("%d adalah bilangan genap\n\n",x);
		
	}
	else
	{
		printf("%d adalah bilangan ganjil\n\n",x);
	}
	printf ("PAUSE");
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* bilangan positif & negatif
*
*/
#include <stdio.h>

main()
{
	int x ;
	printf("masukan bilangan :");
	scanf("%d,&x");
	if(x>=0)
	{
		printf("%d adalah bilangan positif\n\n",x);

	}
	else
	{
		printf("%d adalah bilangan negatif\n\n",x);
	}
	printf("PAUSE");
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* memvalidasi umur 1-100
*
*/
#include <iostream>
using namespace std;

int main()
{
	int umur;
	cout<<"masukan umurmu";
	cin>>umur;
	
	if (umur>=100)
	cout<<"pie kabarmu mbah wes mangan durung?"<<endl;
	cout<<"jadi umurmu"<<umur<<"tahun";
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* mencari bilang terbesar dari 3 bilangan
*
*/
#include <stdio.h>
#include<conio.h>

int main()
{
	int n1,n2,n3,max=0;
	printf("masukan nilai1 :");
	scanf("%d",&n1);
	printf("masukan nilai2 :");
	scanf("%d",&n2);
	printf("masukan nilai3 :");
	scanf("%d",&n3);
	max=n1;
	if(max<n2)
	max=n2;
	if(max<n3)
	max=n3;
	printf("bilangan terbesar :%d",max);
	getch();
	return 0;
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* mengecek segitiga sama sisi atau tidak
*
*/
#include <iostream>
using namespace std;

int main()
{
	cout <<"-------------------------\n";
	cout<<"PROGRAM UNTUK MENGECEK BENTUK SEGITIGA SAMA SISI ATAU BUKAN\n";
	cout<<"tugas semester 1 (fuad kumarudin))\n";
	cout<<"--------------------\n\n";
	    float sudut,jawab;
	    menu :
	cout<<"masukan besarnya sudut segitiga :";
	cin>>sudut;
	if(sudut==60)
	
	cout<<"\njenis segitiga adalah sama sisi\n\n"<<"----------------------\n\n";
	else
	cout<<"\njenis segitiga bukan sama sisi\n\n"<<"------------------\n\n";
	cout<<"ingin coba lagi?\n";
	cout<<"1.ya\n";
	if (jawab==1)
	goto menu;    	
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* mengetahui bentuk bendak beku atau tidak
*
*/
#include <iostream>
using namespace std;

int main()
{
	int air;
	cout<<"masukan derajat suhu=";
	cin>>air;
	if (air<0)
	cout<<"air apabila terkena"<<"suhu"<<"air"<<"derajat adalah zat beku";
	else if(air>0)
	cout<<"air apabila terkena"<<"suhu"<<air<<"derajat adalah tidak zat beku";
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* mengetahui kuadran x dan y
*
*/
#include <iostream>
#include<stdio.h>>
using namespace std;

main ()
{
	int x,y;
	printf("mengetahui kuadran dari inputan koordinat x dan y\n");
	printf("------------------\n");
	printf("masukan nilai x :");
	scanf("%i",&x);
	printf("masukan nilai y :");
	scanf("%i",&y);

	if(x>0 && y>0)
	printf("kuadran 1");
	if(x>0&&y<0)
	printf("kuadraan 2");
	if(x<0 && y<0)
	printf("kuadran 3");
	if(x<0 && y>0)
	printf("kuadran 4");
	if(x==0 &&y==0)
	printf ("titik pusat");


}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* periksa 2 bilangan terbesar atau terkecil
*
*/
#include <iostream>
using namespace std;

int main()

{   int a,b;
cout<<"masukan nilai A :";
cin>>a;
cout<<"masukan nilai B :";
cin>>b;
if(a<b)
{cout<<"B terbesar\n";

}
else if(a>b)
{
	cout<<"A terbesar\n";
}
else
cout<<"error";
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* periksa pemasukan lebih besar atau terkecil
*
*/
#include<iostream>
using namespace std;

int main()
{
	int pemasukan,pengeluaran;
	cout<<"masukan pemasjukan =";
	cin>>pemasukan;
	cout<<"masukan pengeluaran =";
	cin>>pengeluaran;
	
	if (pemasukan<pengeluaran)
	{
		cout<<"pemasukan lebih kecil dari pengeluaran\n";
		
	}
	else if(pemasukan>pengeluaran)
	{
		cout<<"pemasukan lebih besar dari pengeluaran\n";
		
	}
	else
	cout<<"error";
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* menampilkan tulisan algoritma sesuai nilai n
*
*/
#include<stdio.h>
#include<conio.h>

int ulang (int n);

int main (void)
{
    int n;
    printf("Masukin Nilai n = ");
    scanf("%d",&n);
    ulang(n);
    getch();
}
int ulang(int n)
{
    int i;
    for(i=1;i<=n;i++)
        printf("Algoritma Dan Pemograman\n");
        return(i);
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Mencari nilai Terbesar dan terkecil
*
*/
#include<stdio.h>
#include<conio.h>

int main()
{
    int n1, n2, n3, max=0;
    printf("Masukan Nilai 1 = ");
    scanf("%d",&n1);
    printf("Masukan Nilai 2 = ");
    scanf("%d",&n2);
    printf("Masukan Nilai 3 = ");
    scanf("%d",&n3);
    max=n1;
    if(max<n2)
        max=n2;
    if(max<n3)
        max=n3;
    printf("Bilangan Terbesar :%d",max);
    getch();
    return 0;
}

/* end code */
----------------------------------------------------------------------------------------------


/*
*
* Mengetahui Kuadran Suatu Koordinat
*
*/
#include<stdio.h>

int main(){
            int x,y;
            printf("Program Fungsi Untuk Mengetahui Kuadran Suatu Koordinat\n\n");
            printf("Masukan Nilai Koordinat X = ");
            scanf("%i", &x);
            printf("Masukan Nilai Koordinat Y = ");
            scanf("%i", &y);

            if(x>0&&y>0)
                printf("Kuadran I ");
            if(x>0&&y<0)
                printf("Kuadran II ");
            if(x<0&&y<0)
                printf("Kuadran III ");
            if(x==0&&y==0)
                printf("Kuadran Pusat ");
                return 0;

}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Menentukan Bilangan Terkecil Dari 3 Buah Bilangan
*
*/
#include<iostream>

using namespace std;
int main()

{
    int bil1, bil2, bil3, terkecil;
    cout<<"Masukan Bilangan 1 = ";
    cin>>bil1;
    cout<<"Masukan Bilangan 2 = ";
    cin>>bil2;
    cout<<"Masukan Bilangan 3 = ";
    cin>>bil3;
    {
        if(bil1 < bil2)
            terkecil = bil1;
        else
            terkecil = bil2;

        if(bil3 < terkecil)
           terkecil = bil3;

            cout<<endl;
        cout<<"Nilai Terkecil Adalah = "<<terkecil;cout<<endl;

    }
    return 0;
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Menghitung jumlah deret
*
*/
#include <iostream>
#include <conio.h>

using namespace std;

int main(){
int a=0, b, c, jumlah=0, i, n;

cout<<"Masukan Jumlah Deret Bilangan\n";
cout<<"Masukan Bilangan Awal = ";
cin>>a;
cout<<"Masukan Beda = ";
cin>>b;
cout<<"Masukan Jumlah Sampai Deret Ke-n = ";
cin>>n;

cout<<"Deret ke - "<<n<<" : ";
cout<<a<<",";
jumlah=jumlah+a;
for(i=0; i<n-1; i++){
    c=a+b;
    a=c;
    cout<<c<<",";
    jumlah=jumlah+c;

}

cout <<"\n Jumlah Deret Ke - "<<n<<" = ";
cout <<jumlah;

getch();
return 0;
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Mengubah Bilangan pecahan
*
*/
#include<iostream>
using namespace std;
typedef struct pecahan{
        int pb;
        int py;
};
int main(int argc, char *argv[])
{
    pecahan p1, p2;
    cout<<"Masukan Pembilang = ";
    cin>>p1.pb;
    cout<<"Masukan Penyebut = ";
    cin>>p1.py;
    cout<<"\t       "<<p1.pb<<endl;
    cout<<"\tp1=    -"<<endl;
    cout<<"\t       "<<p1.py<<endl;
    if ("/")
    {
        cout<<"Hasilnya = "<<(p1.pb)/(p1.py)<<endl;
    }
    return 0;
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Mengubah Nilai Ke Huruf
*
*/
#include<stdio.h>
#include<conio.h>

int tukar (int nilai);

int main(void)
{
    int nilai;
    printf("Masukan Niali Antara 1 sampai 4 = ");
    scanf("%d", &nilai);
    tukar (nilai);
    getch();
}

int tukar (int nilai)
{
    switch(nilai)
    {
        case4:
            printf("Nilai Huruf : A "); break;
        case3:
            printf("Nilai Huruf : B "); break;
        case2:
            printf("Nilai Huurf : C "); break;
        case1:
            printf("Nilai Huruf : D "); break;
    default:
        printf("Kesalahan Dalam Memasukan Angka");
    }
    return(nilai);
}

/* end code */
----------------------------------------------------------------------------------------------



/*
*
* Menghasilkan 0 atau 1
*
*/

#include<iostream>
#include<stdio.h>
using namespace std;

int main ()
{
    printf("%d", 5>9);
    printf("\n");
    printf("%d", 10>2);
}

/* end code */
----------------------------------------------------------------------------------------------


