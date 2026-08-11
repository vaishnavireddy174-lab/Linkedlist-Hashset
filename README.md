import java.util. LinkedHashSet;
public class sairam {
    




public static void main(String[] args)
{
    int [] a= {10,20,20,30,10,20,40};
    System.out.println(remove(a));



private static LinkedHashSet <Integer>remove(int[] a)
{
    


LinkedHashSet <Integer>Hashset= new LinkedHashSet<Integer>();

for(int i:a) {

hashset.add(i);
    
}

return hashset;
}
}
