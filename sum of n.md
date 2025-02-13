#Sum of N element
```` java[]
    public class Main{
        public static int sum(int n){
            if(n<=1){   // base case 
                return n;
            }
            return n + sum(n-1);// recursive 
        }
        public static void main(String[] args){
            int n = 6;
            //for(int i=0;i<n;i++){
            System.out.println("sum of 6:" + sum(n));
            
        }
    }
````
