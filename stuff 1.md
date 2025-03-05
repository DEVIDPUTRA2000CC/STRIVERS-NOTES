---
title: Untitled

---

#include <iostream>
using namespace std;
void pairs(){
    pair<int, int> p = {1,3}; // p is the pair name
    cout<< p.first<<" "<< p.second;
   // nested pair 
    pair<int, pair<int, int>> p1 = {2, {1,3}};
    cout<< p1.first<<""<< p1.second.first <<""<< p1.second.second;
   // pairs for diffrent data types like arrey 
    pair<int, int> arr[] ={{1,2}, {1,3}, {3,4}};
    cout<<arr[1].second;
    
    }
