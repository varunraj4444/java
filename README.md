# java
program of set, list and map

import java.util.*;

public class Main 

{
    public static void main(String[] args) {
        
        // Set
        Set<String> fruitSet = new HashSet<>();
        fruitSet.add("Apple");
        fruitSet.add("Banana");
        fruitSet.add("Kiwi");
        fruitSet.add("Strawberry");

        System.out.println("Set Example:");
        for (String fruit : fruitSet) {
            System.out.println(fruit);
        }
        System.out.println();

        // List
        List<Integer> numberList = new ArrayList<>();
        numberList.add(100);
        numberList.add(200);
        numberList.add(300);
        numberList.add(400);

        System.out.println("List Example:");
        for (int number : numberList) {
            System.out.println(number);
        }
        System.out.println();

        // Map
        Map<String, Integer> studentScores = new HashMap<>();
        studentScores.put("Varun", 85);
        studentScores.put("Bobby", 92);
        studentScores.put("Tej", 78);
        studentScores.put("Vdns", 95);

        System.out.println("Map Example:");
        for (Map.Entry<String, Integer> entry : studentScores.entrySet()) {
            System.out.println(entry.getKey() + ": " + entry.getValue());
        }
    }
}
