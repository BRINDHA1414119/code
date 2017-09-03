package codekata.pac;

import java.util.ArrayList;
import java.util.HashSet;
import java.util.Scanner;
import java.util.Set;

public class Repeat {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		int a[]=new int[n];
		Set<Integer> al=new HashSet<Integer>();
		for(int i=0;i<n;i++)
		{
			a[i]=sc.nextInt();
		}
		for(int i=0;i<n;i++)
		{
			for(int j=i+1;j<n;j++)
			{
				if(a[i]==a[j])
				{
					al.add(a[i]);
				}
			}
		}
		if(al.isEmpty())
		{
		 System.out.println("No repeat numbers");
		}
		else
		{
		 System.out.print(al);
		}
        sc.close();
	}

}
