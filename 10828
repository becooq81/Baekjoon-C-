#include<vector>
#include<iostream>
using namespace std;
int main(){
    vector<int> storage;
    int N;
    string command;
    int val;
    string temp;
    cin>>N;
    for (int i = 0; i < N; i++) {
        int a; cin>>command;
        if (command=="push") {
            cin>>a;
            storage.push_back(a);
        }
        else if (command=="pop") {
            if (storage.empty()){
                cout<<-1<<"\n";
            }
            else {
                cout<<storage.back()<<"\n";
                storage.pop_back();
            }
        }
        else if (command=="size") {
            cout<<storage.size()<<"\n";
        }
        else if (command=="empty") {
            if (storage.empty()) {
                cout<<1<<"\n";
            }
            else {
                cout<<0<<"\n";
            }
        }
        else if (command=="top") {
            if (storage.empty()) {
                cout<<-1<<"\n";
            }
            else {
                cout<<storage.back()<<"\n";
            }
        }
    }
}


