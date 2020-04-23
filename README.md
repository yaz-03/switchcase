#include <stdio.h>

int main()
{
    printf("Food Items: \n 1.French Fries, Rs.239 \n 2.Burger, Rs.123 \n 3.Sandwich, Rs.126 \n 4.Pizza, Rs.100 \n 5.Pasta, Rs.150 \n");
    int choice;
    printf("Please enter your choice");
    scanf("%d",&choice);
    switch(choice)
    {
        case 1:
            printf("\nFood item-French Fries \nPrice-Rs.239");
            break;
        case 2:
            printf("\nFood item-Burger \nPrice-Rs.123");
            break;
        case 3:
            printf("\nFood item-Sandwich \nPrice-Rs.126");
            break;
        case 4:
            printf("\nFood item-Pizza \nPrice-Rs.100");
            break;
        case 5:
            printf("\nFood item-Pasta \nPrice-Rs.150");
            break;
        default: printf("Choice not in the list");

    }
}
