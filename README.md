# homiesday2
day2
import java.util.Arrays;

public class homies_day2 {
    public static void main(String[] args) {
        int[] arr = {1, 1, 2, 2, 2, 2, 3};
        int target = 2;

        int count = findTargetCount(arr, target);

        System.out.println("Array: " + Arrays.toString(arr));
        System.out.println("Target: " + target);
        System.out.println("Total Target: " + count);

        System.out.println("Submission by: Nehal");
    }

    public static int findTargetCount(int[] arr, int target) {
        int count = 0;
        for (int num : arr) {
            if (num == target) {
                count++;
            }
        }
        return count;
    }
}
