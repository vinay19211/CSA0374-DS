#include <stdio.h>
int main() {
    int n, target, arr[100], first, last, middle;
    printf("Enter the number of elements in the array: ");
    scanf("%d", &n);
    printf("Enter %d integers in ascending order: ", n);
    for (int i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }
    printf("Enter the number you want to search: ");
    scanf("%d", &target);
    first = 0;
    last = n - 1;
    middle = (first + last) / 2;
    while (first <= last) {
        if (arr[middle] == target) {
            printf("%d found at index %d.\n", target, middle);
            return 0;
        } else if (arr[middle] < target) {
            first = middle + 1;
        } else {
            last = middle - 1;
        }
        middle = (first + last) / 2;
    }
    printf("%d not found in the array.\n", target);
    return 0;
}
