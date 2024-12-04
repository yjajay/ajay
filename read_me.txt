#include<stdio.h>
#include<string.h>
//char s[]="project";
//void main()
//{ 
//	int i,d;
//	
//	int l=strlen(s);
//	
//	for (i=0;i<l/2;i++)
//	{
//		d=s[i];
//		s[i]=s[l-1-i];aaserZ	zazzA
//		s[l-1-i]=d;
//	}
//	printf("%s",s);
// 

void main()
{
	int i=0,r=0;
	char s[]="helao";
	char t[]="hell";
	int l=strlen(s);
	int l1=strlen(t);
	for(i=0;s[i]!=l&&t[i]!=l1;i++)
	{
		if (s[i]!=t[i])
		{
			r=s[i]-t[i];
		}
		
	}
	if(r<0)
	{
		printf("-1");
	}
	else if(r=0)
	{
		printf("0");
	}
	else if(r>0)
	{
		printf("1");
	}
}
