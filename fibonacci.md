#fibanacci number
```` java[]
    
    public class Main{
        public static int fibanacci(int n){
            if(n<=1){   // base case 
                return n;
            }
            return fibanacci(n-1) + fibanacci(n-2); // recursive 
        }
        
        public static void main(String[] args){
            int n = 6;
            for(int i=0;i<n;i++){
            System.out.println("Fibanacci of 10:" + fibanacci(i));
            }
        }
        }
````
