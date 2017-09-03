package codekata.pac;

import java.util.ArrayList;
import java.util.Arrays;
import java.util.Collections;
import java.util.List;
import java.util.Scanner;

public class Subarray {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		int n1=sc.nextInt();
		int a1[]=new int[n];
		int a2[]=new int[n1];
		int count=0;
		for(int i=0;i<n;i++)
		{
			a1[i]=sc.nextInt();
		}
		for(int i=0;i<n1;i++)
		{
			a2[i]=sc.nextInt();
		}
		List<Integer> al=new ArrayList<Integer>();
		List<Integer> al1=new ArrayList<Integer>();
		for(int i=0;i<n;i++)
		{
			al.add(a1[i]);
		}
		for(int i=0;i<n1;i++)
		{
			al1.add(a2[i]);
		}
		for(int i=0;i<al.size();i++)
		{
		 if(al1.contains(al.get(i)))
		 {
			
			count++;
		 }
		}
		if(count==n)
		{
			System.out.println("Subset");
		}
		else
		{
			System.out.println("Not a subset");
		}
		

	}

}
