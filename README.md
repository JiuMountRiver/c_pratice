# c_pratice
NEWER PRATICE
大小写字母转换
    // char zimu;
    //   scanf("%c",&zimu);
    //  int letter =(int) zimu ;
    //   if (letter >= 97 && letter <= 122) {//小写字母
    //       printf("%c",letter - 32);
    //   }
    //   else if (letter >= 65 && letter <= 90) {
    //       printf("%c",letter + 32);
    //   }
    //   else
    //       printf("Error");


    // //输入n个奇数
    // int n ;
    // scanf("%d",&n);
    // int num = n*2,odd = 0;
    // while (odd <num) {
    //     odd+=1;
    //     if (odd % 2 == 1)
    //         printf("%d\n",odd);
    // }

    ///FOR
        //正向反向输出数据
    // for (int num =5;num>=1;num--)
    //     printf("%d\n",num);
        //累加
    // int sum = 0;
    // for (int num = 1; num <=5; num++)
    //     sum += num;
    // printf("%d",sum);
        //  输出非2.3.5倍数
    // int n = 0;
    // scanf("%d",&n);
    // for (int num = 1;num <= n;num++) {
    //     if (num % 2 !=  0 && num % 3 != 0 && num % 5 != 0) {
    //         printf("%d ",num);
    //     }
    // }
        //前n个和
    // int n ,sum = 0;
    // scanf("%d",&n);
    // for (int i = 1;i <= n;i++)
    //     sum += i;
    // printf("%d\n",sum);

        //阶乘
    int n;
    long long int  total = 1;
    scanf("%d",&n);
    for(int i=1;i <= n;i++) {
        total *= i;

    }
    printf("%lld\n",total);
}
