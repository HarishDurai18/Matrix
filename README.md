public class DisplayMatrix {

  public static void main(String[] args) {
    // declare and initialize a 3x3 matrix
    int matrix[][] = 
      { { 5, 9, 0 }, { 8, 3, 1 }, { 7, 6, 5 } };
    
    // display 2D array using for-each loop
    for(int[] i : matrix) {
      for(int j : i) {
        System.out.print(j + " ");
      }
      System.out.println(); // new line
    }
  }

}
