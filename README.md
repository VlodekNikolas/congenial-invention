# congenial-invention


Раскомментируй одну строчку, чтобы программа вывела на экран числа 12 и 2 (сначала 12, а затем 2).

Требования:
Программа должна выводить на экран числа 12 и 2.
Нельзя изменять строки с объявлением переменных.
Программа должна содержать только две переменные типа int.
Нельзя изменять строки, отвечающие за вывод в консоль.
Нужно раскомментировать одну строку и не менять остальные.

package com.javarush.task.jdk13.task01.task0107;

public class Solution {
    public static void main(String[] args) {
        int x = 2;
        int y = 12;

        // y = x * y;
        // y = x + y;

        
        x = y - x;
        y = y - x;

        System.out.println(x);
        System.out.println(y);
    }
}



package com.javarush.task.jdk13.task01.task0107;

public class Solution {
    public static void main(String[] args) {
        int x = 2;
        int y = 12;

        // y = x * y;
        // y = x + y;

        
        y = x + y; //y=2+12=14
        x = y - x; //х=14-2=12
        y = y - x; //y=14-12=2

        System.out.println(x);
        System.out.println(y);
    }
}
