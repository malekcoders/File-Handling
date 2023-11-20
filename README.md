## File Handling Project

#### Objectives
Understand how Java handles files. 

#### Concepts
These concepts are the main used concepts in the project solution, kindly read the provided resources if any is new to you.

| Concepts                                          | Resources                                                                                                             |
|---------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| File Handling in Java                             | [Edureka Java handling file ](https://www.youtube.com/watch?v=SslMi6ptwH8&t=364s)                                     |
| Understand File, FileReader,and  FileWriter class | [Artical File class in Java](https://www.codecademy.com/resources/docs/java/files)                                    |
| Write into a file                                 | [DigitalOcean Artical - Java File Handling](https://www.digitalocean.com/community/tutorials/java-filewriter-example) |



#### Problem
Write a program that create a text file, then write into that text file. 


#### Implementation
Do the implementation of the `createFile` method:
1. Create a file object of FileWriter class with the name that given in the method argument.
2. Write into the file using the `write` method of the FileWriter class.
3. Close the file stream `close` method of the FileWriter class.
4. Call it in the main method.

```
public static void createFile(String fileName) throws IOException {
    /* Your code here */
}
```
