#include <stdio.h>
int main() {
    int n, target, arr[100];
    printf("Enter the number of elements in the array: ");
    scanf("%d", &n);
    printf("Enter %d integers: ", n);
    for (int i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }
    printf("Enter the number you want to search: ");
    scanf("%d", &target);
    for (int i = 0; i < n; i++) {
        if (arr[i] == target) {
            printf("%d found at index %d.\n", target, i);
            return 0;
        }
    }
    printf("%d not found in the array.\n", target);
    return 0;
}
