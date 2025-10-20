#include<algorithm>

void reverseArray(vector<int> &arr , int m) {
    int n =arr.size();
//two pointer approach 
        int r=n-1;
    int l=m+1;

    while(l<r)
    {
        swap(arr[l],arr[r]);
        l++;
        r--;
    }     
    // by using stl 
    		
    reverse(arr.begin()+m+1 , arr.end());   
}
