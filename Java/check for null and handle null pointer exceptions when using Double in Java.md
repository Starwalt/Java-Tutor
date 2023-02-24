
```

Double d1 = null;
Double d2 = 5.0;

// Checking for null
if (d1 != null) {
    // Do something with d1
    double result = d1 + d2;
    System.out.println("Result: " + result);
} else {
    System.out.println("d1 is null");
}

// Handling null pointer exception
try {
    // Do something with d1
    double result = d1 + d2;
    System.out.println("Result: " + result);
} catch (NullPointerException e) {
    System.out.println("Caught NullPointerException: " + e.getMessage());
}


```

