# Homework 2 : Recursion
A program assignment that practice using recursion

## Answer for #4


```
public static long fibonacci(int n) {
 // the base case
 if (n < 2) return 1;
 // the recursive step
 return fibonacci(n-1) + fibonacci(n-2);
}
```

4.1 : This method recurses too many times.  Every call will call two calling method and when n is large it will take lot of time.



