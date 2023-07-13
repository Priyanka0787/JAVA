import java.util.Scanner;
public class IntegerSum{
public static void main(String[] args){
Scanner input =new Scanner(System.in);
System.out.println("Enter five integers:");
int total=0;
for(int i=0;i<5;i++){
System.out.print("Enter an integer: ");
int num=input.nextInt();
total+=num;
}
System.out.println("The sum of theintegers is: "+total);
input.close();
}
When we run this java program ,it will ask to enter five integers one by one.After we have entered all five integers .it will calculete their sum and display it on the consol.
