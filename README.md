> ***Çin Zodyağı nedir?***
>
> *4000 bin yıldır kullanılan bir astroloji çeşididir Çin astrolojisi ve insanları 12 değişik burç ve sembollerle tanımlar. Çin Zodyağı bu 12 burcun eşit aralıklarla(10 derece genişliğinde) sıralandığı bir hayvan halkasıdır ve yıldızlarla pek bir ilgisi yoktur.*
>
> ***Çin Zodyağı nasıl hesaplanır?***
>
> *Çin zodyağı hesaplanırken kişinin doğum yılının 12 ile bölümünden kalana göre bulunur.*
>
> *Kalan = 0 ➜ Maymun*
>
> *Kalan = 1 ➜ Horoz*
>
> *Kalan = 2 ➜ Köpek*
>
> *Kalan = 3 ➜ Domuz*
>
> *Kalan = 4 ➜ Fare*
>
> *Kalan = 5 ➜ Öküz*
>
> *Kalan = 6 ➜ Kaplan*
>
> *Kalan = 7 ➜ Tavşan*
>
> *Kalan = 8 ➜ Ejderha*
>
> *Kalan = 9 ➜ Yılan*
>
> *Kalan = 10 ➜ At*
>
> *Kalan = 11 ➜ Koyun*

```java
import java.util.Scanner;

public class castro {
    public static void main(String[] args) {
        int yil;

        Scanner input = new Scanner(System.in);
        System.out.print("Doğum yılınızı giriniz :");
        yil = input.nextInt();

        yil %= 12;
        switch (yil) {
            case 0:
                System.out.print("Maymun");
                break;
            case 1:
                System.out.print("Horoz");
                break;
            case 2:
                System.out.print("Köpek");
                break;
            case 3:
                System.out.print("Domuz");
                break;
            case 4:
                System.out.print("Fare");
                break;
            case 5:
                System.out.print("Öküz");
                break;
            case 6:
                System.out.print("Kaplan");
                break;
            case 7:
                System.out.print("Tavşan");
                break;
            case 8:
                System.out.print("Ejderha");
                break;
            case 9:
                System.out.print("Yılan");
                break;
            case 10:
                System.out.print("At");
                break;
            case 11:
                System.out.print("Koyun");
                break;
        }

    }

}

```

