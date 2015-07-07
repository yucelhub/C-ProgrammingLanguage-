#include<stdio.h>//standart giris-cikis kütüphanesi
int main()
{
	int girilen_sayi;//degisken tanilama(tam sayi)
	printf("Lutfen bir tam sayi giriniz> ");
	scanf("%d",&girilen_sayi);//klavyeden girilen sayiyi degiskene atama
	if( girilen_sayi > 100 )//kontrol
		printf("Girilen sayi 100'den buyuktur\n");
	else
		printf("Girilen sayi 100'den kucuktur\n");
	return 0;
}
