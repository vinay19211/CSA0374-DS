#include <stdio.h>
#include <stdlib.h>
#define MAX 5
int top = -1;
int stack[MAX];
void push(int data) {
   if(top == MAX-1) {
      printf("Stack is full!\n");
   } else {
      top++;
      stack[top] = data;
   }
}
void pop() {
   if(top == -1) {
      printf("Stack is empty!\n");
   } else {
      printf("Popped element: %d\n", stack[top]);
      top--;
   }
}
void peek() {
   if(top == -1) {
      printf("Stack is empty!\n");
   } else {
      printf("Top element: %d\n", stack[top]);
   }
}
int main() {
   int choice, data;
   while(1) {
      printf("\n\nStack Operations:\n");
      printf("1. Push\n2. Pop\n3. Peek\n4. Exit\n");
      printf("Enter your choice: ");
      scanf("%d", &choice);
      switch(choice) {
         case 1:
            printf("Enter data to push: ");
            scanf("%d", &data);
            push(data);
            break;
         case 2:
            pop();
            break;
         case 3:
            peek();
            break;
         case 4:
            exit(0);
         default:
            printf("Invalid choice!\n");
      }
   }
   return 0;
}
