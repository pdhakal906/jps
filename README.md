# jps

``` #include <stdio.h>

int Increment(int* expr){
    // unsigned long *recoveredPointer = (void *) expr;
    // *recoveredPointer = *recoveredPointer + 1;
    (*expr)++;
}

int main() {

    int a;
    a = 10;
    Increment(&a);
    printf("a=%d\n",a);
}
```
