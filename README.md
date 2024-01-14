# DSA-practice-
455topics
Day-1(User I/P and O/P)
import java.util.Scanner;
public class Solution {
    
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String s = sc.next();
        char ch = s.charAt(0);
        if(ch >= 'A' && ch <= 'Z'){
            System.out.println("1");
        }
        else if(ch >= 'a' && ch <= 'z'){
            System.out.println("0");
        }
        else{
            System.out.println("-1");

        }
        // Write your code here

    }
}

#DataTypes:
import java.util.Scanner;
public class Solution {
    public static int dataTypes(String type) {
        
        if(type.equals("Integer")){
            return 4;
        }
        else if(type.equals("Long")){
            return 8;
        }
        else if(type.equals("Float")){
            return 4;
        }
        else if(type.equals("Double")){
            return 8;
        }
        else if(type.equals("Character")){
            return 1;
        }
        return 0;
        
        // Write your code here
    }
               
}

#If - else Statements:
import java.util.Scanner;
public class Solution {
    public static int dataTypes(String type) {
        
        if(type.equals("Integer")){
            return 4;
        }
        else if(type.equals("Long")){
            return 8;
        }
        else if(type.equals("Float")){
            return 4;
        }
        else if(type.equals("Double")){
            return 8;
        }
        else if(type.equals("Character")){
            return 1;
        }
        return 0;
        
        // Write your code here
    }
               
}

#For Loop:
import java.util.Scanner;
public class Solution {


	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int n = sc.nextInt();
		int arr[] = new int[100];
		arr[0] =1;
		arr[1] =1;
		for(int i=2;i<n;i++){
			arr[i] = arr[i - 1] +arr[i - 2];
		}
		System.out.println(arr[n - 1]);

	}
			
}


