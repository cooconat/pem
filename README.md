# pem
import java.util.*;
 
public class StringFormat {
    public static void main(String[] args){
        double e = Math.E;
        System.out.format("%f%n", e);
        System.out.format(Locale.CHINA  , "%-10.4f%n%n", e);  //指定本地为中国（CHINA）
    }
}
