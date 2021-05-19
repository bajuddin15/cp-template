# cp-template
This is a cp templlate in cpp language for any editor like sublime text editor 3 and vscode etc.


//---------------------------------------------- Comptetive Programming Template Created By Bajuddin Khan ----------------------------------------------//

#include<bits/stdc++.h>
#include <ext/pb_ds/assoc_container.hpp>
using namespace __gnu_pbds;
using namespace std;

#define ff              first
#define ss              second
#define int             long long
#define pb              push_back
#define mp              make_pair
#define pii             pair<int,int>
#define vi              vector<int>
#define mii             map<int,int>
#define pqb             priority_queue<int>
#define pqs             priority_queue<int,vi,greater<int> >
#define setbits(x)      __builtin_popcountll(x)
#define zrobits(x)      __builtin_ctzll(x)
#define mod             1000000007
#define inf             1e18
#define ps(x,y)         fixed<<setprecision(y)<<x
#define mk(arr,n,type)  type *arr=new type[n];
#define w(x)            int x; cin>>x; while(x--)
mt19937                 rng(chrono::steady_clock::now().time_since_epoch().count());

typedef tree<int, null_type, less<int>, rb_tree_tag, tree_order_statistics_node_update> pbds;


int gcd(int a, int b){
	while(b !=0){
		int res = a%b;
		a =b;
		b = res;
	}
	return a;
}

void solve()
{
	ios_base::sync_with_stdio(0); cin.tie(0); cout.tie(0);
#ifndef ONLINE_JUDGE
	freopen("inputcp.txt", "r", stdin);
	freopen("outputcp.txt", "w", stdout);
#endif

	int t;
	cin>>t;
	while(t--){
		int n;
		cin>>n;
  
	}

}

int32_t main(){

    solve();

	return 0;
}
