# robindrew-sizeof
Sizeof library for Java

This library is very simple to use:

    // The object you want to measure the memory of
    Object object = ....
    
    // Calculate!
    MemoryCalculator calculator = new MemoryCalculator();
    long bytes = calculator.sizeOf(object);
    
For full details on memory calculations and how to use the library, visit the [Wiki](https://github.com/robindrew/robindrew-sizeof/wiki)
