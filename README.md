# -succotash
#include<iostream>
using namespace std;

int main() {
	/* 三目运算符
	表达式1？表达式2:表达式3
	*/

	//创建三个变量 abc
	int a = 11;
	int b = 12;
	long long c = 0;
	cin >> a ;
	cin >> b;

	

	//将ab进行比较，将大值赋给变量c
	a > b ? c = a : c = b; //c = (a > b ? a : b);
	cout << "c=" << c << endl;
	system("pause");
		return 0;





}
