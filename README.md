import.java.util.Scanner;
public class Main
{
piblic static void main(String[]args){
Scanner scan = New scanner(System.in);
System.out.println("Введите число меньше 100");
int number = scan.nextInt();
if(number<100){
System.out.println("Вы ввели" + number);
}
else {
System.out.println("Введите верное число");
}
}
}
