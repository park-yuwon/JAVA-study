# JAVA-study
### Lecutre
- 자바의 정석 기초편 https://youtube.com/playlist?list=PLW2UjW795-f6xWA2_MUhEVgPauhGl3xIp
### Textbook
- 남궁성, <자바의 정석>
- 남궁성, <자바의 정석 기초편>
- 우종정, <쉽게 배우는 자바 프로그래밍 2판>
## Learning History
### Winter vacation (Self learning)
#### 22.01.15 (Sat)
- Ch. 2-1 ~ 2-8
  - Variables, Constant, Literal (Types, Suffix)
  - Shortcuts for Eclipse IDE

#### 22.01.16 (Sun)
- Ch. 2-9 ~ 2-10, 2-14
  - Variables (Basic Type)
  - Interchange two varaibles' values 
  - Scanner Class
  
#### 22.01.17 (Mon)
- Ch. 2-11 ~ 2-17, 3-1\~2, 4-1\~11, 4-13\~24, 5-1
- \[Ch.2 Complete]
  - Types and Range of Variables (Basic Type)
  - printf and format specifier(형식 지정자)
  - Type casting
  - Overflow
- Ch.3
  - Operators
- \[Ch.4 Complete]
  - if, switch, Loops
  - (4-12: Random number generator)
    - Math.random(); // generate random numbers between 0 to 1
- Ch.5
  - Declaration of an Array
 
#### 22.01.18 (Tue)
- Ch. 6-1
  - History of Object-oriented Programming(OOP) languages
    - Stengths: Easy to maintenace(유지보수 용이), High reusability(높은 재사용성), De-duplicatable(중복제거)
  - Class and Object of Java
  - 4 Properties of OOP
    - **Polymorphism(다형성)**
    - Inheritance(상속)
    - Encapsulation(캡슐화)
    - Abstraction(추상화)

#### 22.01.19 (Wed)
- Ch. 6-2 ~ 6-7
  - Relationships between Class and Instance
  - Object and Instance, a kind of object which is made by class
  - Make Class and Instance
  - Use Instance; variables(fields) and methods
  - Reference variable of instance


#### 22.01.20 (Thu)
- Ch. 5-1 ~ 5-5
  - Array
  - Declaration of reference variables and Creating arrays
    - DATA_TYPE\[] ARR_NAME;  // Declare a reference variable of array
    - ARR_NAME = new DATA_TYPE\[ARR_SIZE];  // Create an array
    - DATA_TYPE\[] ARR_NAME = new DATA_TYPE\[ARR_SIZE]; // Combining of declaration and creating in once
    - DATA_TYPE ARR_NAME\[] = new DATA_TYPE\[ARR_SIZE]; // C style (Legal but not recommended)
  - Initialization of arrays
    - Java Array is basically initialized automatically to 0, NULL, false (기본형)...
    - ARR_NAME\[] = { LIST_OF_VALUES };   // Initialize entirely (INDEX is omitable)
    - ARR_NAME\[INDEX] = NEW_VALUE;   // Initialize separately
    - 
``` JAVA
public class array {
    public static void main(String[] args) {
        int[] arr1 = new int[10];
    }
}

```

#### 22.01.21 (Fri)
- Ch. 6-8 ~ 6-35 (Briefly)
  - Print out Arrays 
  - Object array
  - Variables declared inside of a class
    - iv: Instance variable / in class area / can use after creating object(instance)
    - cv: Class variable / static(values can be change) / in class area / can use right after declaration of class
    - lv: Local variable / in methods area / exist only in methods
  - Call Stack wtih primitive vs. reference variable
  - Instance methods vs. Static methods
  - Overloading of methods
  - Constructor of methods


#### 22.01.22 (Sat)
- Ch. 6-23 ~ 6-25 (review)
  - Parameters
    - primitive parameters
    - reference parameters

#### 22.01.23 (Sun)
- Ch. 6-26 \~ 29 (review), 6-36 \~ 37
  - Instance methods vs. Static methods
    - instance methods: can use iv(instance variables), needed to initialize the iv and to make an instance before calling instance methods
    - class methods(static ―): cannot use iv, available without declarization of instance
  - "this"
    - reference variable "this"
    - constructor "this()"

#### 22.01.24 (Mon)
- Ch. 5-8 ~ 5-11
  - Application of arrays
    - Length of an array: array.length
    - Exact average of array values: sumOfArray / (float)array.length

#### 22.01.25 (Tue)
- Ch. 7-1 \~ 4
  - Inheritance

#### 22.01.26 (Wed)
- Ch. 7-3 \~ 4 (review)
  - Inheritance


#### 22.01.28 (Fri)
- Ch. 7-5 \~ 9
  - Single Inheritance
  - class Object
  - Overriding of methods
    - Overloading vs. Overriding

#### 22.01.29 (Sat)
- Ch. 1-1 \~ 7
  - Concept and History of Java
  - Java API Documents

#### 22.01.30 (Sun)
- Ch. 6-38 \~ 41
  - Initialization of variables and members

#### 22.01.31 (Mon)
- Ch. 6-38 \~ 41(supplementary), 7-10 \~ - 11
- \[Ch.6 Complete]
  - Initialization of variables and members
  - super vs. super()

#### 22.02.01 (Tue)
- Ch. 7 - 12 ~ 21
  - Package, classpath
  - import and static import
  - Access Modifiers

#### 22.02.03 (Thu)
- Ch. 7-
  - Polymorphism
  - Type Casting of referencial variable
  - instanceof Operator
  
#### 22.02.05 (Sat)
- Ch. 7-
  - Polymorphism of reference variable
  - Abstract Class

#### 22.02.06 (Sun)
- Ch. 7-
  - Excercise of abstract classes
  - Interface

#### 22.02.07 (Mon)
- Ch. 7-
  - Excercise and Strengths of Interface

- Static method of Interface

- Introduction of Inner Class

#### 22.02.12 (Sat)
- Ch. 7-
  - Excercise and Strength of Inner class 

#### 22.02.13 (Sun)
- Ch. 7-
  - Kinds of Inner Class
    - Instance inner class
    - \[static] Class inner class
    - Local inner class
    - Annonymous inner class
  -  
> Q. How to creat an instance of inner class?
> Q. "static 메서드에서 내부클래스가 사용된다" 뜻

#### 22.02.15 (Tue)
- Ch. 7-
- \[Ch.7 Complete]
  - Inner class(내부 클래스)
  - Annonymous class(익명 클래스)
- Ch. 8
  - Program error
    1. compile-time error
    2. runtime error
      - Error
      - Exception 
        - Exception class and their children: fault by user, checked exception(it means if not check the exception, it would provoke a compile error)
        - RuntimeException class and their children: fault by programmer, unchecked exception
    3. logical error
  - Processing Exception
    - try-catch block
    - Declare exception to method: return_type method() throws Exception { ...
    - Hide (은폐, empty catch block)
   


#### 22.02.16 (Wed)
- Ch. 8-11~14
  - "throws" (Declare exceptions to method)
  - create file
  - File IO
  - finally block

#### 22.02.17 (Thu)
- Ch. 8-
- \[Ch.8 Complete]
  - User-defined exception
  - Exception re-throwing
  - chained exception


#### 22.02.18 (Fri)
- Ch. 9-
  - Object class

### 2022-1 Semester (OOP Class)
#### 22.03.02 (Wed)
- 자바의 유래: 제임스 고슬링이 Sun Microsystems에서 가전제품을 위한 프로그래밍 언어를 만들었다가 Web과 Netscape(현 Firefox의 전신)에서 활발히 사용되었다.
- Object Oriented Language
- High-level Language
- Compiler vs. Interpreter: 자바 프로그램을 컴파일러로 컴파일한 후 얻어지는 것은 "Java Byte code".
- WORA 정신\[JVM, 자바 가상 머신] -\> Byte code를 실행할 수 있는 이진코드(Binary code)로 바꾸어주는 Interpreter. =\> 자바는 Platform 독립적(Portability):OS에 구애받지 않는다.
- Binary code의 OS 종속성이란?: OS마다 실행되는 binary code가 다르다.

![image](https://user-images.githubusercontent.com/77564623/159188554-c49bc901-a8ec-4bd2-b065-f3609fc2bd9d.png)
