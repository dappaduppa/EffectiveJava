

# Advantages:

1. Name of method ( compared to constructors)
2. Not required to create New object (Flyweight pattern)
3. == operator instead of the equals(Object) method, which may
   result in improved performance
4. return an object of any subtype (unlike constructors).

ex 1: Collections.static methods
ex 2: EnumSet
64 or fewer ( RegularEnumSet)
65 or more (JumboEnumSet)
reduce verbosity ( by type inference
