```java
import java.util.Scanner;
public class main {
    public static void main(String[] args) {

        double birinciKenar, ikinciKenar, ucuncuKenar;

        Scanner input = new Scanner(System.in);

        System.out.print("1. Kenarı Girin: ");
        birinciKenar = input.nextDouble();

        System.out.print("2. Kenarı Girin: ");
        ikinciKenar = input.nextDouble();

        System.out.print("3. Kenarı Girin: ");
        ucuncuKenar = input.nextDouble();

        double u = (birinciKenar + ikinciKenar + ucuncuKenar) / 2;

        double alanxalan = u * (u - birinciKenar) * (u - ikinciKenar) * (u - ucuncuKenar);

        double alan = Math.sqrt(alanxalan);

        System.out.print("Üçgenin Alanı: " + alan);


    }
}

```

