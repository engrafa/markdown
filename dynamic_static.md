# Static Languages Vs Dynamic Languages 

## **Static Languages** 

Static languages are mostly **compiler-based** languages. You need to tell the compiler that this variable is an integer, etc. We cannot change the variable type in static languages. In static languages, you have to tell the compiler that this function returns an integer, string, etc. Here is an example of how we define a variable in a static language (java):

```java
class HelloWorld {
    public static void main(String[] args) {
	    int a = 10;
	    String string = "Hello World";
    }
}
```



You might ask why should I use static languages? They are **way faster than dynamic languages** because the compiler doesn't waste any time checking which data type the variable is. 

<br>

## **Dynamic Languages** 
Unlike static languages, dynamic languages are executed by **interpreters**, rather than compilers. They execute the **code line by line**. We don't need to specify the variable type in these types of languages. We also don't need to specify the return type in a function. Here is an example of how we define a variable in an interpreted language (python): 


```py
a = 10
a = "Hello world"
```

You might want to use dynamic languages over static languages if you are a beginner because they are way easier to understand and code in. 


<br>

## **Differences**
| Dynamic      | Static 
| :---        |    :----:   
| These use interpreters  |  These compilers
| No need to specify variable type|  Need to specify Variable type     
| Slower | Faster |
| No need to specify return type in functions | Need to specify return type in functions

<br>

Happy Programming,\
Prash | _Engrafa Team_


