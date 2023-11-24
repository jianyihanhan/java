import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner scanner=new Scanner(System.in);
        int m= scanner.nextInt();
        int n= scanner.nextInt();
        //int nm=(n-1)*(m-1);
        int nm=m*n;
        int []arr1=new int [nm];
        int [][]arr=new int [m][n];
        int i,j,s=0;
        for(i=0;i<m;i++){
            for(j=0;j<n;j++){
                arr[i][j]=scanner.nextInt();
            }
        }
        for(i=0;i<m;i++){
            for(j=0;j<n;j++){
                arr1[s]=arr[i][j];
                s++;
               
            }
        }

        Arrays.sort(arr1);
            System.out.print(arr1[nm-1]-arr1[0]);



    }
}
