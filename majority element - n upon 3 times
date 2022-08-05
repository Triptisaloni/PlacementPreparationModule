import java.util.*;
public class Main {
  static ArrayList < Integer > majorityElement(int arr[], int n) {
    ArrayList < Integer > ans = new ArrayList < > ();
    for (int i = 0; i < n; i++) {
      int cnt = 1;
      for (int j = i + 1; j < n; j++) {
        if (arr[j] == arr[i])
          cnt++;
      }

      if (cnt > (n / 3))
        ans.add(arr[i]);
    }

    return ans;
  }
  public static void main(String args[]) {
    int arr[] = {1, 2, 2, 3, 2};
    ArrayList < Integer > majority = majorityElement(arr, 5);
    System.out.print("The majority element is: ");
    HashSet < Integer > s = new HashSet < > (majority);
    for (int it: s) {
      System.out.print(it + " ");
    }
    System.out.println();
  }
}
