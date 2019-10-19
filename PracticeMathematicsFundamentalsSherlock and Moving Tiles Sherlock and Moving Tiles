#include<bits/stdc++.h>
#define assn(n,a,b) assert(n<=b && n>=a)
using namespace std;
#define pb push_back
#define mp make_pair
#define clr(x) x.clear()
#define sz(x) ((int)(x).size())
#define F first
#define S second
#define REP(i,a,b) for(i=a;i<b;i++)
#define rep(i,b) for(i=0;i<b;i++)
#define rep1(i,b) for(i=1;i<=b;i++)
#define pdn(n) printf("%d\n",n)
#define sl(n) scanf("%lld",&n)
#define sd(n) scanf("%d",&n)
#define pn printf("\n")
typedef pair<int,int> PII;
typedef vector<PII> VPII;
typedef vector<int> VI;
typedef vector<VI> VVI;
typedef long long LL;
#define MOD 1000000007
LL mpow(LL a, LL n) 
{LL ret=1;LL b=a;while(n) {if(n&1) 
    ret=(ret*b)%MOD;b=(b*b)%MOD;n>>=1;}
return (LL)ret;}
int main()
{
    LL z,s1,s2,q;
    double a,b,c;
    cin >> z >> s1 >> s2 >> q;
    assn(z,1,1000000000);
    assn(s1,1,1000000000);
    assn(s2,1,1000000000);
    if(s1<s2)swap(s1,s2);
    while(q--){
        LL ki;
        cin >> ki;
        assn(ki,1,z*z);
        double p=sqrt(ki);
        printf("%.4lf\n",((double)z-p)*sqrt(2)/(double)(s1-s2));
    }
    return 0;
}
