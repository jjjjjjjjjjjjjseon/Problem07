# Problem07
package pr5;

import java.util.Scanner;
public class Problem07 {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String answer;

        System.out.println("========================");
        System.out.println("  [숫자맞추기게임 시작]");
        System.out.println("========================");

        int com = (int)(Math.random()*100) + 1;
        int use;

        while (true) {
            System.out.print(">>");
            use = scanner.nextInt();

            if(use > com){
                System.out.println("더 낮게");
        } else if (use < com) {
            System.out.println("더 높게");
        } else {
            System.out.println("맞았습니다.");
         break;
        }
    }
        System.out.print("게임을 종료하시겠습니다?(y/n) >>");
        answer = scanner.next();
    if (answer.equalsIgnoreCase("n"));

        System.out.println("========================");
        System.out.println("  [숫자맞추기게임 종료]");
        System.out.println("========================");
        }
 }
