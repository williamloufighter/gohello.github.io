# 2020cce homework.github.io
code
```c
#include <stdio.h>
int main()
{
	int a,b,c,n;
	scanf("%d",&n);
	printf("%d=50*%d+5*%d+1*%d\n",n,n/50,(n%50)/5,(n%5)/1);
}
```

```c
#include <stdio.h>
int main()
{
	int n;
	scanf("%d",&n);
	int ans=0;
	for(int i=1; i<=n; i++){
		if(n%i==0) ans+=1;
	}
	printf("%d\n",ans);
}
```

```c
#include <stdio.h>
int main()
{
	int a[20],ans=0;
	for(int i=1; i<=10; i++){
		scanf("%d",&a[i]);
			if(a[i]%3==0){
			ans+=1;
		}
	}
	printf("%d\n",ans);
}
```

```c
#include <stdio.h>
int main()
{
	int n;
	scanf("%d",&n);
	if(n>=90) printf("A\n");
	else if(n<90&&n>=80) printf("B\n");
	else if(n<80&&n>=60) printf("C\n");
	else printf("F\n");
}
```

```c
#include <stdio.h>
int main()
{
	int a,b,c;
	scanf("%d%d",&a,&b);
	for(int i=1; i<=10000; i++){
		if(a%i==0&&b%i==0)
		c=i;
	}
	printf("%d %d\n",a/c,b/c);
}
```
