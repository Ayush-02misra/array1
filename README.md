# array1
/* to find average number of array */
import java.util.*;
class a
{
    public static void main(String args [])
    
    {
        int i,l;
        double arr[]={20,18.5,21.6,100};
        double total=0;
        l=arr.length();
        for(i=0;i<l;i++)
        {
            total=total+arr[i];
        }
        double average=total/l;
        System.out.print("the average is"+average);
    }
}
