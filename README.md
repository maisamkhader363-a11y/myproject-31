#include<iostream>
using namespace std;
int main()
{
	int n;
	cout << "plz enter the side length of  square" << endl;
	cin >> n;
	for (int i = 1; i <= n; i++) {
		for (int j = 1; j <= n; j++) {
			cout << '*';
		}
		cout << "\n";
	}
 
}

