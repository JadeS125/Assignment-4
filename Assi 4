public class Main {
    public static void main(String[] args) {

        
        int[] myArray = {10, 3, 295, 38, 20, 3, 4, 267, 2445, 10, 5566, 87, 93, 17, 10, 2, 87, 267, 3176, 3, 82};

        // This new array helps me remember which numbers were already checked
        boolean[] alreadyChecked = new boolean[myArray.length];

        //for the results
        System.out.println("Duplicate numbers and how many times they appear:");
        System.out.println("");

        //this Goes through the array one number at a time
        for (int i = 0; i < myArray.length; i++) {

            // If already checked this number, it will skip it
            if (alreadyChecked[i]) {
                continue;
            }

            int currentNumber = myArray[i]; // the number we’re checking
            int count = 1; // thjis start count at 1 because we already saw it 

            // I then compare it with every number that comes after it
            for (int j = i + 1; j < myArray.length; j++) {
                if (myArray[j] == currentNumber) {
                    count++; // add 1 if we find another match
                    alreadyChecked[j] = true; // this mark it so we don’t count it again :)
                }
            }

            // If the number is found more than once, it will print it
            if (count > 1) {
                System.out.println("Number " + currentNumber + " appears " + count + " times.");
            }
        }

        // What I learned:
        // I learned how to use loops to check each number in an array
        // Also how ro find which ones are duplicates, and count how many times they appear.
    }
}
