# string-program
if u enter a charector  more than once bt it will print only once. 
#include<stdio.h>
#include<conio.h>
int main()
{
	char s1[10],s2[10];
	int i,j,z=0,k=0;
	printf("");
	scanf("%s",s1);
	for(i=0;i<15;i++)
	{
		for(j=0;j<15;j++)
		{
			if(s1[i]==s2[j])
			{
			
			z=399;
			j=15-1;
		}
			else
			{
				z++;
			}
			}
			if(z!=399)
			{
				s2[k]=s1[i];
				k++;
				
			}
			z=0;
		}
		printf("%s",s2);
		
		
	
}
