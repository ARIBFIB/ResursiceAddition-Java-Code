# ResursiceAddition-Java-Code

Youtube Link: 
![image](https://github.com/ARIBFIB/ResursiceAddition-Java-Code/assets/125716994/e42aa328-07ab-4672-a5c1-334eb8755f21)

public class RecursiveAddition{
    public static int Add(int n){
        if(n == 0){
            return 0;
        }else{
            return (n + Add(n - 1));
        }
    }
    public static void main(String[] args){
        System.out.println("The add all the numbers from 0 up to 10 are: "+ Add(10));
    }
}

# Output
![image](https://github.com/ARIBFIB/ResursiceAddition-Java-Code/assets/125716994/3e61a9e7-f0a9-4a79-a650-c403e1b1c7a4)
