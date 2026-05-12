#include<iostream>
using namespace std;
class Student{
    public:
  string name;
  int rollnumber;
  float cgpa;

  Student(){

  }
  Student(string s,int r, float c){
    name=s;
    rollnumber=r;
    cgpa=c;

  }
  void print(Student s){
cout<<s.name<<s.rollnumber<<s.cgpa;
  }
};
int main(){
Student s1;
s1.name="Ali";
s1.rollnumber=123;
s1.cgpa=3.5;
Student s2("ahmad",34,3.4);
print(s1);

}