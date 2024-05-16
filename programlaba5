import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
	// write your code here
        Scanner input = new Scanner(System.in);
        System.out.println("Введите а: ");
        int a = input.nextInt();
        System.out.println("Введите b: ");
        int b = input.nextInt();
        System.out.println("Введите x: ");
        int x = input.nextInt();
        calculator calc_obj1 = new calculator(a, b, x);
        calculator calc_obj2 = new calculator(a, b, x);
        calculator calc_obj3 = new calculator(a, b, x);
        calc_obj1.method1();
        calc_obj2.method2();
        calc_obj3.method3();
    }

}
class calculator{
    double a;
    double b;
    double x;
    double y;
    public calculator(double a, double b, double x) {
        this.a = a;
        this.b = b;
        this.x = x;
    }
    public void method1(){
        y = (3 * x) + 5;
        System.out.println("Результат первого вычисления равен: " + y);
    }
    public void method2() {
        if (a - b != 0) {
            y = (a + b) / (a - b);
            System.out.println("Результат второго вычисления равен: " + y);
        }
        else {
            System.out.println("Деления на 0 не возможно, введите числа не равные нулю и не равные друг другу");
        }
    }
    public void method3(){
        if (b != 0){
            y = a*x/b;
            System.out.println("Результат третьего вычисления равен: " + factorial(y));
        }
        else {
            System.out.println("не возможно деление на 0 введите b отличное от 0");
        }
    }
    public int factorial(double j){
        int f = 1;
        for(int i = 1; i <= j; i++){
            f *= i;
        }
        return f;
    }
}
