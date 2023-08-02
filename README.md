# REVERSEarrayNumber
In this repository, We were exploring java programs and projects.

import java.util.*;
public class ARRAYreverseNUMBER{
    public static void REVERSE(int number[]){
        
        int first =0;
        int last = number.length-1;
        
        while(first<last){
            int temp =number[last];
            number[last]=number[first];
             number[first] =temp;
        first++;
        last--;
        
        }
    }
public static void main(String[] args) {
    int number[] ={1,2,3,4,5};
    REVERSE(number);
    for(int i=0;i<number.length;i++){
        System.out.print(number[i]+" ");
    }
System.out.println();


}
}
