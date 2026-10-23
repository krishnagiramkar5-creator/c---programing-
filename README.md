#
using name space std;
int main()
{
float cp, sp;
cout<<"enter cost price";
cin>>cp;
cout<<"enter selling price";
cin>>sp;
if(sp>cp)
cout<<"profit="<<sp-cp;
else if (cp>sp)
cout<<"loss="<<cp-sp;
else
cout<<"no profit no loss"";
return 0;
}
