#include<stdio.h>
#include<string.h>
void main()
{
	char a;
	char str[200];
	int number=0;
	int i=0;
	printf("请输入需要测定的句子");
		gets(str);
	strlwr(str);
	printf("输入需要计数的单词");
	scanf("%c",&a);
	for(i;i<200;i++)
	{
		if(a==str[i])
			number++;
	}
	printf("单词在句子里出现的次数:%d\n",number);
	
}
