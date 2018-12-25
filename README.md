# bilangan-prima-atau-bukan

    #include <iostream>

    using namespace std;
    int main()
    {
    int x,i,count=0;
    cout<< "masukan sebuah angka :";
    cin>>x;
    for (i=2;i<=x/2;i++)
    {
        if (x%i==0)
            count++;

    }
    if (count>0||x<2)
        cout<<x<< "bukan bilangan prima\n";
    else
        cout<<x<< "\n bilangan prima\n";
    }
    
    
    
    
hasil

![img](https://github.com/hamdanyuapi/bilangan-prima-atau-bukan/blob/master/hasil%20bilangan%20prima.png?raw=true)
