# 🚀 Learn Java with DSA
1) Packages
2) Input/Output via text files<br>
   &nbsp2.1) Reading Input from Text File<br>
   &nbsp2.2) Writing Output to Text File<br>

## 1. Java Packages Info
import java.io.*; tells the compiler import all the input/output packages e,g File,FileInputStream,PrintWriter,BufferedReader,BufferedWriter
import java.util.*; tells the compiler import all the utility packages e.g Scanner,ArrayList,List,Arrays,Collections
```java
import java.io.*;
import java.util.*;
```
## 🔢 2. Input / Output

### 2.1 Reading Input from Text File
```java
Scanner in = new Scanner(new File("input.txt"));
```
### 2.2  Writing Output to Text File
```java
PrintWriter out = new PrintWriter("output.txt");
```
