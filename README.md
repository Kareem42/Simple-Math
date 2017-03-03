# Simple-Math
// This project is to solve simple math problems, with constructors,
// using addition, subtraction, multiplication, division, and remainder.
// There is nothing complex nor complicated about this project. It just shows 
// part of the my skill set for simple every day math.

package Practice;

public class SimpleMath {
	int x;
	int y;
	int z;
		
	// This is the only constructor I will use with the arguments for global variables x, y, z.
	SimpleMath(int x, int y, int z){
		this.x = x;
		this.y = y;
		this.z = z;
	}
	
	// Addition Method
	int getAdd(){return x + y + z;}
	
	// Subtraction Method
	int getSubtract(){return x - y - z;}
	
	// Multiplication Method
	int getMultiply(){return x * y * z;}
	
	// Division Method
	int getDivide(){return x / y / z;}
	
	// Remainder Method
	int getRemainder(){return x % y % z;}
	
	// Main Method with 5 different objects created with arguments to match the constructor
	public static void main(String[] args) {
		SimpleMath p1 = new SimpleMath(4, 5, 6);
		SimpleMath p2 = new SimpleMath(20, 5, 8);
		SimpleMath p3 = new SimpleMath(3, 5, 9);
		SimpleMath p4 = new SimpleMath(100, 5, 2);
		SimpleMath p5 = new SimpleMath(47, 3, 1);
		
		// Print the results of each object with getters		
		System.out.println(p1.getAdd() + "\n" + p2.getSubtract() 
		+ "\n" + p3.getMultiply() + "\n" + p4.getDivide() + "\n" + p5.getRemainder() + "\n");

	}

}
