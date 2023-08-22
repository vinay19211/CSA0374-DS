#include <stdio.h>
#define MAX_SIZE 100
int main()
{
    int arr[MAX_SIZE];
    int i, n, pos, value;
    printf("Enter size of array: ");
    scanf("%d", &n);
    printf("Enter elements in array:\n");
    for(i=0; i<n; i++)
    {
        scanf("%d", &arr[i]);
    }
    printf("Enter element position to insert: ");
    scanf("%d", &pos);
    printf("Enter element to insert: ");
    scanf("%d", &value);
    for(i=n; i>=pos; i--)
        arr[i] = arr[i-1];
    arr[pos-1] = value;
    n++;
    printf("Array after insertion: ");
    for(i=0; i<n; i++)
        printf("%d ", arr[i]);
    printf("\nEnter the element position to delete: ");
    scanf("%d", &pos);
    for(i=pos-1; i<n-1; i++)
        arr[i] = arr[i+1];
    n--;
    printf("Array after deletion: ");
    for(i=0; i<n; i++)
        printf("%d ", arr[i]);
   return 0;
}
