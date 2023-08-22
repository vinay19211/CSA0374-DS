#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#define MAX 100
int top = -1;
char stack[MAX];
void push(char data) {
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
      printf("Popped element: %c\n", stack[top]);
      top--;
   }
}
int main() {
   char notation[MAX];
   int i;
   printf("Enter the notation: ");
   scanf("%s", notation);
   for(i=0; i<strlen(notation); i++) {
      if(notation[i] == '(' || notation[i] == '[' || notation[i] == '{') {
         push(notation[i]);
      } else if(notation[i] == ')' || notation[i] == ']' || notation[i] == '}') {
         pop();
      }
   }
   if(top == -1) {
      printf("Notation is balanced!\n");
   } else {
      printf("Notation is not balanced!\n");
   }
   return 0;
}
