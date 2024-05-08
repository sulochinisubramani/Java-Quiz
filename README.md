# Java-Quiz
#Difference in using Relational Operator(==) and Assignment Operator(=) in if condition.
public class Main{
    public static void main(String args[]){
        boolean myval=true;
        System.out.println(myval);
        if(myval=true)
        for(int i=0;i<2;i++)
        System.out.println(i);
        else
        System.out.println("else");
    }
}
output: 0 
1
