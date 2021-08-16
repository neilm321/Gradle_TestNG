package Geometry;

import java.util.Scanner;

import org.testng.Assert;
import org.testng.annotations.Test;


public class GeometryTest {
	
	int choice1;
	static int choice2;
	int choice3;
	private static float A2;
	private static float B2;
	private static float A1;
	private static float B1;
	private static float C2;
	private static int choice22;
	
	@Test()
	public void testUI() {
		
		Scanner in = new Scanner(System.in);
		System.out.println("Press 1 to calculate for rectangle/nPress 2 to calculate for a a sphere");
		int choice1 = in.nextInt();
		
		
		if (choice1 == 1) {
			System.out.println("Press 1 to calculate the area/nPress 2 to calculate the perimeter");
			choice22 = in.nextInt();
		}
		if (choice1 == 2) {
			System.out.println("Press 1 to calculate the volume/nPress 2 to calculate the surface area");
			choice22 = in.nextInt();
		}
		
		System.out.println("This test ran from testUI");
		Assert.assertEquals(false, false);
		
		if (choice2 == 1) {

			System.out.println("Enter Width:");
			setA2(in.nextFloat());
			System.out.println("Enter Height:");
			setB2(in.nextFloat());
			testAreaRect();
			System.out.println(Geometry.areaRect(A2, B2));
		}
		
		Assert.assertEquals(false, false);
		
		if (choice2 == 1) {

			System.out.println("Enter Width:");
			setA1(in.nextFloat());
			System.out.println("Enter Height:");
			setB1(in.nextFloat());
			testPerimeterRect();
			System.out.println(Geometry.perimeterRect(A1, B1));
		}
	
		Assert.assertEquals(false, false);
		
		if (choice22 == 1) {

			System.out.println("Enter Radius:");
			setC2(in.nextFloat());
			testVolumeSphere();
			System.out.println(Geometry.volumeSphere(C2));
		}
		
		Assert.assertEquals(false, false);
		
		if (choice22 == 2) {

			System.out.println("Enter Radius:");
			setC2(in.nextFloat());
			testSurfaceAreaSphere();
			System.out.println(Geometry.surfaceAreaSphere(C2));
			in.close();
		}
		
		Assert.assertEquals(false, false);
		
	}
	@Test()
	public float testAreaRect() {
		System.out.println("This test ran from within testAreaRect");
		float D2 = A2 * B2;
		
		Assert.assertNotNull(D2);
		
		return D2;
		
	}
	@Test()
	public float testPerimeterRect() {
		System.out.println("This test ran from within testPerimeterRect");
		
		float E2 = A1 + A1 + B1 + B1;
		
		Assert.assertNotNull(E2);
		
		return E2;
	}
	@Test()
	public float testVolumeSphere() {
		System.out.println("This test ran from within testVolumeSphere");
		
		float F2 = (4/3) * (22/7) * (C2 * C2 * C2);
		
		Assert.assertNotNull(F2);
		
		return F2;
	}
	@Test()
	public float testSurfaceAreaSphere() {
		System.out.println("This test ran from within testSurfaceAreaSphere");
		
		float G2 = 4 * (22/7) * (C2 * C2);
		
		Assert.assertNotNull(G2);
		
		return G2;
	}
	public static float getA2() {
		Assert.assertNull(A2);
		return A2;
		
	}



	public static void setA2(float a2) {
		GeometryTest.A2 = a2;
		Assert.assertNull(a2);
	}


	public static float getB2() {
		Assert.assertNull(B2);
		return B2;
	}



	public static void setB2(float b2) {
		GeometryTest.B2 = b2;
		Assert.assertNull(b2);
	}



	public static float getA1() {
		Assert.assertNull(A1);
		return A1;
	}



	public static void setA1(float a1) {
		GeometryTest.A1 = a1;
		Assert.assertNull(a1);
	}



	public static float getB1() {
		Assert.assertNull(B1);
		return B1;
	}


	public static void setB1(float b1) {
		GeometryTest.B1 = b1;
		Assert.assertNull(b1);
	}



	public static float getC2() {
		Assert.assertNull(C2);
		return C2;
	}



	public static void setC2(float c2) {
		GeometryTest.C2 = c2;
		Assert.assertNull(c2);
	}
}
