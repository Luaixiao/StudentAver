# StudentAver
Ask the average age of all the students in the class
#include <stdio.h>

int main()
{
int i,a[100],ave=0;
int n;
printf("请输入本班学生人数：\n");
scanf_s("%d",&n);
printf("输入每名学生的年龄：\n");
for(i=0;i<n;i++)
{
scanf_s("%d",&a[i]);
ave=ave+a[i];
}
printf("本班学生的平均年龄:%.2f\n",(float)ave/n);
system("pause");
return 0;
}
