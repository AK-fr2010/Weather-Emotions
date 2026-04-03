# Weather-Emotions

    import java.util.Scanner;
     public class Main {
      public static void main(String[] args){
        Scanner scanner = new Scanner(System.in);

        double temp ;
        boolean isSunny ;
        boolean isRaining ;

        System.out.print("What Is The Temperature 🌡️ :");
        temp = scanner.nextDouble();

        System.out.print("Is the weather Sunny ☀️? :");
        isSunny = scanner.nextBoolean();

        System.out.print("Is it raining :");
        isRaining = scanner.nextBoolean();

        if (temp >= 10 && temp <= 30){
            System.out.println("The Weather is Great 😊 ");
             if (!isSunny || !isRaining) {
                System.out.println("The Weather is Pure Bliss 😇 ");
            }
             else {
                 System.out.println("The Weather is Cool And Sunny 🌤️");
             }

        }
        else {
            System.out.println("The Weather is Bad 😒♨️");
        }



        scanner.close();
    }
}
