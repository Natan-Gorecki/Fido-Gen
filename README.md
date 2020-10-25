# Fido-Gen


The Fido-Gen (Files Documentation Generator) will be environment for creating files and documentation based on the stored objects. The project will be developed to make it easy to extend into different languages and with different file generation and documentation schemes.


## Structure


```
+-- Output (added to .gitignore)
    +-- Any CPU
    +-- x86
    +-- x64
+-- Sources
    +-- Generator
    +-- Objects
    +-- Schemes
+-- Tests (using MSTest)
    +-- Generator.Tests
    +-- Objects.Tests
    +-- Schemes.Tests
+-- packages
+-- Fido-Gen.sln
```