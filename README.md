#include <stdio.h>
int main()
{
 int a,qty,rate,total;
 printf("\nMENU CARD \nSelect Your Food Item \n1.Pizza, Rs239 \n2.Burger, Rs129 \n3.Pasta, Rs179 \n4.French Fries, RS99 \n5.Sandwich , Rs149\n");
 scanf("%d",&a);
 switch(a)
 {
  case 1:
    printf("\nYou have selected Pizza.\n Enter the quantity :");
    scanf("%d",&qty);
    rate=239;
    total=qty*rate;
    printf("\nTotal amount :%d",total);
    break;
  case 2:
    printf("\nYou have selected Burger.\n Enter the quantity :");
    scanf("%d",&qty);
    rate=129;
    total=qty*rate;
    printf("\nTotal amount :%d",total);
    break;
  case 3:
    printf("\nYou have selected Pasta.\n Enter the quantity :");
    scanf("%d",&qty);
    rate=179;
    total=qty*rate;
    printf("\nTotal amount :%d",total);
    break;
  case 4:
    printf("\nYou have selected French Fries.\n Enter the quantity :");
    scanf("%d",&qty);
    rate=99;
    total=qty*rate;
    printf("\nTotal amount :%d",total);
    break;
  case 5:
    printf("\nYou have selected Sandwich.\n Enter the quantity :");
    scanf("%d",&qty);
    rate=149;
    total=qty*rate;
    printf("\nTotal amount :%d",total);
    break;
  default:
    printf("\nSorry Unavailable...%ds",a);
    break;
 }
return 0;
}
