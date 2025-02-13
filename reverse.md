# Reverse number 
```` java[]
    
    public class Main{
        static int sum=0;
        public static int reverse(int n){
            if(n==0){   // base case 
                return 0;
            }
            int temp=n%10;
            sum=sum*10+temp;
            reverse(n/10);
            return sum;// recursive 
        }
        
        public static void main(String[] args){
            int n = 12345;
            
            System.out.println("reverse " + reverse(n));
            
        }
    }
````
