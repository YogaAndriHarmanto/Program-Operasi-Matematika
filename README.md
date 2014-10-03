Program-Operasi-Matematika
==========================

#include &lt;stdio.h> #include &lt;conio.h>  main() {  	int pilihan,pilihan2;    float a,b,hasil;    do    {    printf("
 Nama: YOGA ANDRI HARMANTO");    printf("
 NIM: 3143111051");    printf("


");    printf("PROGRAM OPERASI MATEMATIKA 
");    printf("
1. PERKALIAN");    printf("
2. PENGURANGAN");    printf("
3. PENJUMLAHAN");    printf("
4. PEMBAGIAN");    printf("
Masukkan angka pilihan yang ingin dioperasikan : ");    scanf("%d",&amp;pilihan);    if	(pilihan==1)    	{        printf("
PERKALIAN");        printf("
=================");        printf("
Masukkan angka pertama ");        scanf("%f",&amp;a);        printf("Masukkan angka kedua ");        scanf("%f",&amp;b);        hasil=a*b;        printf("
Hasil perkalian %4.2f * %4.2f = %4.2f",a,b,hasil);       }    else if(pilihan==2)    	{        printf("
PENGURANGAN");        printf("
=================");        printf("
Masukkan angka pertama ");        scanf("%f",&amp;a);        printf("Masukkan angka kedua ");        scanf("%f",&amp;b);        hasil=a-b;        printf("
Hasil Pengurangan %4.2f - %4.2f = %4.2f",a,b,hasil);       }    else if(pilihan==3)    	{        printf("
PENJUMLAHAN");        printf("
=================");        printf("
Masukkan angka pertama ");        scanf("%f",&amp;a);        printf("Masukkan angka kedua ");        scanf("%f",&amp;b);        hasil=a+b;        printf("
Hasil Penjumlahan %4.2f + %4.2f = %4.2f",a,b,hasil);       }    else if(pilihan==4)    	{        printf("
PEMBAGIAN");        printf("
=================");        printf("
Masukkan angka pertama ");        scanf("%f",&amp;a);        printf("Masukkan angka kedua ");        scanf("%f",&amp;b);        	if(b==0)          	printf("
Tidak bisa di bagi dengan nol");             else {        		hasil=a/b;        printf("
Hasil Pembagian %4.2f / %4.2f = %4.2f",a,b,hasil);        		}       }    else    	{       printf("PILIHANMU SALAH BRO.. !, COBA LAGI ? ");       printf("
1. YES");       printf("
2. NO
");       scanf("%d",&amp;pilihan2);       }    printf("

COBA LAGI ? ");    printf("
1. YES");    printf("
2. NO
");    scanf("%d",&amp;pilihan2);    getch();     }    while(pilihan2==1);  } 
