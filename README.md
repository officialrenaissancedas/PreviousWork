# PreviousWork
basicjavaandcppprograms
please open the program 

import java.util.Arrays;
public class arrToString {
    public static void main(String[] args) {
        int[] arr = {100, 20, 3000, 400};
            System.out.println(Arrays.toString(arr));
            int[] newarr = new int[10];
            newarr = Arrays.copyOf(arr, 5);
            for(int ele : newarr) {
                System.out.println(ele);
            }
            newarr = Arrays.copyOfRange(arr,1,4);
            for(int ele: newarr){
                System.out.println(ele);
            }
        System.out.println();
            boolean res = Arrays.equals(arr, newarr);
        System.out.println(res);
        Arrays.fill(newarr,0);
        for(int ele: newarr){
            System.out.println(ele);
        }
        Arrays.sort(arr);
        for(int a : arr) {
            System.out.println(a);
        }
        int index = Arrays.binarySearch(arr,3000);
        System.out.println(index);
        Arrays.asList(arr);
        for(int a:arr){
            System.out.println(a);
        }
        }
    }
