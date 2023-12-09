# Important Points
### Import statement:
1. Imports are not present in the compiled code.
2. Import statement has no effect on runtime efficiency of the class.
---
### Access Modifiers:
1. public: visible to any other class
2. protected: visible to classes that are in the same package or to subclasses
3. **\<default>**: visible to only classes in the same package
4. private: visible only within the same class
5. **\<default>** means that no access modifier is explicitly set.
6. Any nonprivate parts of your class should be kept as stable as possible, because changes of such code may adversely affect any number of other classes that may be using your code.
---
### Java Program execution:
1. Since Java 11, it is also possible to run single-file source code as if it is a compiled class. JVM will interpret your code, but no compiled class file would be created: 
```shell
java /location/to/java/file.java
```
---
### Documentation:
1. Documentation comments:
    1. may contain HTML markups
    2. may contain descriptive tags prefixed with `@`
    3. These are used by the javadoc tool to generate documentation
    
```shell
javadoc -d <documentation path> -sourcepath <source code path> -subpackages <name of the root package>
```


