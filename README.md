# DrakeDev
package MyPackage;
public class MyClass {
	static boolean gioitinh;
	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.print("Hello World\n");
//<Hello World>
String name;
float height;
int age;
String school;
String lop;

System.out.println("*Thông tin cá nhân của tác giả");
//Thông tin cá nhân của tác giả
name ="Khoa";
height = 1.7f;
age = 14;
school = "Trường Thcs Le Loi";
lop = "7a15";
/*
 *Tên
 *Tuổi
 *Chiều cao
 */

/**
 * Đây là javadoc
 * @since 2020-03-23
 */
System.out.print("Tên: ");
System.out.println(name);
System.out.print("Chiều cao: ");
System.out.println(height);
System.out.print("Tuổi: ");
System.out.println(age);
System.out.print("Trường: ");
System.out.println(school);
System.out.print("Lớp: ");
System.out.println(lop);   
	 
	 /*final double PI = 3.14;
	 *int r = 3;
	 *System.out.println(2*r*PI);
	 *
	 *float a= 434.3f;
	 *long b=(int) a;
	 *System.out.println( a*b);
	 *System.out.println(b);
	 */
 if (gioitinh == false) {
	 System.out.println("Nam");
 }else
	 System.out.println("Nữ");
	 
	 System.out.println("Bạn bao nhiêu tuổi ?");
	 int age1 = 14;
	 System.out.println(age1);
	 if (age1 >= 16) {
		 System.out.println("Bạn đủ tuổi");
	 }
		 else {
			 System.out.println("Bạn không đủ tuổi");
			 
			 System.out.println("Bạn là học sinh hay sinh viên?");

	 String job = "S";
	 
	 if (job == "Học sinh") {
		 System.out.println("Bạn vẫn còn là học sinh chưa đủ tuổi tham gia");
	 }else if  (job == "Sinh viên") {
		 System.out.println("Bạn là sinh viên đủ tuổi để tham gia");
	 }else 
		 System.out.println("System của chúng tôi không thể nhận dạng bạn");
		 
	 }
			 
	 }
}




