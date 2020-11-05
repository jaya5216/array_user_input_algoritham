# array_user_input_algoritham

#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;
// jaya lalwani
int main() {
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */
    int N,M;
    cin >> N;
    int arr[N];
    for (int i = 0; i < N; i++) {
        cin >> arr[i];
    }
    for (int j = 0; j <N; j++) {
        cout << arr[j] << " ";
    }
    cout<<endl;
        cin >> M;
     for (int i = 0; i < M; i++) {
        cin >> arr[i];
    }
    for (int j = 0; j <M; j++) {
        cout << arr[j] << " ";
    }
    return 0;
}
