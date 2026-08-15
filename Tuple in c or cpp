#include<bits/stdc++.h>
using namespace std;
int main()
{   
   vector<tuple<int, int, int>>v;
   v.push_back({2, 1, 4});
   v.push_back({1, 5, 3});
   v.push_back({2, 1, 3});
   for(int i=0; i<v.size(); i++){
      cout << get<0>(v[i]) << " " << get<1>(v[i]) << " " << get<2>(v[i]) << endl;
      if(i==0) get<2>(v[i]) = 1008;// can change element using get
   }
   sort(v.begin(), v.end());
   for(auto[a,b,c] : v){
      cout << a << " " << b << " " << c << endl; // can't change element while using auto
   }
   return 0;
}
