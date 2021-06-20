# First Assignment 

package com.Uchbeat.fizzbuzz;

public class FizzBuzzTest {
    public static void main(String[] args) {
        for(int i=0;i<=100;i++) {
            if(i%3==0 && i%5==0) System.out.println("FizzBuzz");
            else
            if(i%5==0) System.out.println("Buzz");
            else
            if(i%3==0) System.out.println("Fizz");
            else
                System.out.println(i);
        }
    }
}


# Second Assignment 
fun main() {

    println("Enter string:")
    val str = readLine()

    var result: String = ""
    var lastIndex = str!!.lastIndex

    while (lastIndex >= 0) {
        result += str[lastIndex]
        lastIndex--
    }

    println("Reversed: $result")
}
