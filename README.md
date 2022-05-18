import java.util.Scanner;
class Test {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        System.out.println("введите размер массива");
        int[] arr = new int[in.nextInt()];
        for(int i = 0; i<arr.length; i++ ) {
            System.out.println("введите " + i + " элемент массива  = ");
            arr[i] = in.nextInt();
        }
        for(int j = 0; j < arr.length; j++){
            if(j%2 == 0) {
                System.out.print(arr[j]);
            }
        }
    }
}
