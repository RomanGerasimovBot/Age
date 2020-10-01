# Age
import static java.lang.Integer.max;
import static java.lang.Integer.min;
public class New2Age {
    public static void main(String[] args) {
        int katyaAge = 34;
        int vasyaAge = 14;
        int mishaAge = 28;
        int min;
        int middle;
        int max;
        max = max(vasyaAge, max(katyaAge, mishaAge));
        min = min(vasyaAge, min(katyaAge, mishaAge));
        middle = vasyaAge + katyaAge + mishaAge - max - min;
        System.out.println("Minimal age: " + min);
        System.out.println("Middle age: " + middle);
        System.out.println("Maximum age: " + max);
    }
}
