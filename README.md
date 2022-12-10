# Sorting
    import java.util.Scanner;
    public class Main {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int a,b,c;

        System.out.print(" A sayısını giriniz: ");
        a = input.nextInt();
        System.out.print(" B sayısını giriniz: ");
        b = input.nextInt();
        System.out.print(" C sayısını giriniz: ");
        c = input.nextInt();
        if((a>b) && (a>c)){
            if(b>c){
            System.out.print("A>B>C");
        }
            else{
                System.out.print("A>C>B");
            }
        }
        if((b>a) && (b>c)){
            if(a>c){
            System.out.print("B>A>C");
        }
            else{
                System.out.print("B>C>A");
            }
        }
        if((c>a) && (c>b)){
            if(b>a) {
                System.out.print("C>B>A");
            }
            else{
                System.out.print("C>A>B");
            }
        }
    }
}
