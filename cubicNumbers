import java.util.Scanner;

public class CubicNumbersInRange {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter the lower bound of the range: ");
        int lowerBound = scanner.nextInt();

        System.out.print("Enter the upper bound of the range: ");
        int upperBound = scanner.nextInt();

        System.out.println("Cubic numbers in the range [" + lowerBound + ", " + upperBound + "]:");
        for (int number = lowerBound; number <= upperBound; number++) {
            if (isCubicNumber(number)) {
                System.out.println(number);
            }
        }

        scanner.close();
    }

    // Function to check if a number is a cubic number
    public static boolean isCubicNumber(int num) {
        int cubeRoot = (int) Math.round(Math.pow(num, 1.0 / 3.0));
        int cubic = cubeRoot * cubeRoot * cubeRoot;
        return cubic == num;
    }
}
