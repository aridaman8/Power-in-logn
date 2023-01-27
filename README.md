# Power-in-logn



int powr(int num,int n){

int res=1;
while(n>0){
if(n%2==1){res=res*num;
res%=mod;

}
n=n>>1;

num=(num*num)%mod;



}
return res;


}
