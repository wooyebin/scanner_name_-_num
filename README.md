import java.util.Scanner;
public class scannerInput{
	public static void main(String args[]){
		Scanner sc = new Scanner(System.in);
		String[] name = new String[3];
		int[] num = new int[3];
		for(int i=0; i<3; i++){
			System.out.print("NAME : ");
			name[i] = sc.next();
			System.out.print("NUM  : ");
			//num[i] = Integer.parseInt(sc.nextLine());
			num[i] = sc.nextInt();
			//sc.nextLine();
		}
		for(int i=0; i<3; i++){
			System.out.println(name[i]+" "+num[i]);
		}
	}
}
