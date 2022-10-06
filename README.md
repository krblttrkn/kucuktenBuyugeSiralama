# ÖDEV :
## SAYILARI KÜÇÜKTEN BÜYÜĞE SIRALAMA
- Girilen 3 sayıyı 'küçükten büyüğe' sıralayan programı yazınız.

```
import java.util.Scanner;

public class kucuktenBuyugeSiralama {
    public static void main(String[] args) {
        int a,b,c;
        Scanner input = new Scanner(System.in);

        System.out.println("*****Küçükten Büyüğe Sıralama***** ");
        System.out.print("1. Sayıyı Giriniz : ");
        a = input.nextInt();
        System.out.print("2. Sayıyı Giriniz :");
        b = input.nextInt();
        System.out.print("3. Sayıyı Giriniz : ");
        c = input.nextInt();

        if ((a<b)&&(a<c)){
            if (b<c){
                System.out.print("a < b < c");
            }
            else {
                System.out.print("a < c < b");
            }
        }
        else if ((b<c)&&(b<a)){
            if (c<a){
                System.out.print("b<c<a");
            }
            else {
                System.out.print("b<a<c");
            }
        }
        else {
            if (a<b){
                System.out.print("c<a<b");
            }
            else {
                System.out.print("c<b<a");
            }
        }
    }
}
```
***
## PATİKA LİNKİM :
<a href='https://app.patika.dev/krblttrkn'>PaTiKa linkim</a>
