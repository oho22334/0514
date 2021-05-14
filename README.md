# 0514
## 進階題：數字個數
```C 
#include <stdio.h>
int main()
{
	int a,ans=0;
	while(scanf("%d",&a)!=EOF)
	{ans++;}
	printf("%d",ans-1);
}
```
## 進階題：判斷平方數 
```C
#include <stdio.h>
int main()
{
	int n,ans=0;
	scanf("%d",&n);
	for(int i=1;i<n;i++){
		if(i*i==n)ans=i;}
			printf("%d",ans);
}
```
## 進階題：計算質數個數
```C
#include <stdio.h>
int main ()
{
	int a,b,count=0;
	int j;
	scanf("%d%d",&a,&b);
	for(int i=a;i<=b;i++){
		for(j=2;j<i;j++){
		if(i%j==0)break;}
		if(j==i)count++;}
		printf("%d",count);
		
	
}
```
## 
