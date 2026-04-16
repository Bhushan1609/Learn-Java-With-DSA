# 🚀 Learn Java with DSA
1) Packages
2) Input/Output via text files<br>
   2.1) Reading Input from Text File<br> 
   2.2) Writing Output to Text File<br>
3) Creates a dynamic ArrayList initialized with given values using Arrays.asList().
4) Swap built function work in the case list only
5) Get and set values of list
6) Array length int[] arr
7) Declaration int minimum and maximum
8) Declaration of Array
9) Declaration of List
10) Map in Java


## 1. Java Packages Info
import java.io.*; tells the compiler import all the input/output packages e,g File,FileInputStream,PrintWriter,BufferedReader,BufferedWriter
import java.util.*; tells the compiler import all the utility packages e.g Scanner,ArrayList,List,Arrays,Collections
```java
import java.io.*;
import java.util.*;
```
## 2. Input / Output

### 2.1 Reading Input from Text File
```java
Scanner in = new Scanner(new File("input.txt"));
```
### 2.2  Writing Output to Text File
```java
PrintWriter out = new PrintWriter("output.txt");
```
## 3. Creates a dynamic ArrayList initialized with given values using Arrays.asList().
```java
List<Integer>arr=new ArrayList<>(Arrays.asList(13,46,24,52,20,9));
```
## 4. Swap built function work in the case list only
```java
List<Integer>arr
Collections.swap(arr, i, minIndex);
```
## 5. Get and set values of list
```java
int temp=arr.get(i);
arr.set(i,arr.get(j));
arr.set(j,temp);
```

## 6. Array length int[] arr 
```java
int[] arr
int n=arr.length;
```
## 7. Declaration int minimum and maximum 
```java
int min = Integer.MIN_VALUE;
long min = Long.MIN_VALUE;

int max = Integer.MAX_VALUE;
long max = Long.MAX_VALUE;

```

## 8. Declaration of Array 
```java
int[] dp = new int[n];

int[][] dp = new int[n][m];

int[][][] dp = new int[n][m][k];

```


## 9. Declaration of Array 
```java
1D
List<Integer> position = new ArrayList<>();

List<Integer> position = new ArrayList<>(n); with size n

2D
List<List<Integer>>dp=new ArrayList<>();
  for(int i=0;i<n;i++){
      List<Integer>row=new ArrayList<>(Collections.nCopies(position.size(),-1));
      dp.add(row);
  }
// for longggggggg
List<List<Long>>dp=new ArrayList<>();
  for(int i=0;i<n;i++){
      List<Long>row=new ArrayList<>(Collections.nCopies(position.size(),-1L));
      dp.add(row);
  }
//access dp.get(i).get(j);
// set dp.get(i).set(i, value)

```
## 10. Declaration of Array 
```
 HashMap<Integer, ArrayList<Integer>>mapp=new HashMap<>();
        for(int i=0;i<nums.length;i++){
            mapp.computeIfAbsent(nums[i],k->new ArrayList<>()).add(i);
        }
ArrayList<Integer>indexes=mapp.get(ele);
```
## 11. Binary Search 
```
int indexofele=Collections.binarySearch(indexes,index); // equivalent to lower_bound

```
