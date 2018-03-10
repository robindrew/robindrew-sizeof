# robindrew-sizeof
Sizeof library for Java

This library is very simple to use:

    // The object you want to measure the memory of
    Object object = ....
    
    // Calculate!
    MemoryCalculator calculator = new MemoryCalculator();
    long bytes = calculator.sizeOf(object);