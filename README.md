# prime-number
public class Main {
    public static void main(String[] args) {
        
        int num = 55;
        boolean flag = false;
        for(int i = 2;i<=num/2;i++){
            if(num%i==0){
                flag = true;
                break;
            }
            if(!flag){
                System.out.println("it is prime");
            }else{
                System.out.println("not a primt");
            }
        }
    }
}
