# GradingSystem
This system tells you your Grade
#include <iostream>
#include <string>
using namespace std;

int main() {
	char grade;
	double score;
	cout << "Please enter your score \n";
	cin >> score;
	if (score >= 70) {
		grade = 'A';
	} 
	else if(score >= 60) {
		grade = 'B';
	}
	 else if (score >= 50){
		grade = 'C';
	} 
	else if (score >= 45){
		grade = 'D';
	}
	 else if (score >= 40){
		 grade = 'E';
	 } else
	 	grade = 'F';
	 cout << "Your Grade is: " << grade << "\n";


return 0;
}
