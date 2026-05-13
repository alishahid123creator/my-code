#include<iostream><br>
using namespace std;<br>
class Student{<br>
    public:<br>
  string name;<br>
  int rollnumber;<br>
  float cgpa;<br>

  Student(){<br>

  }<br>
  Student(string s,int r, float c){<br>
    name=s;<br>
    rollnumber=r;<br>
    cgpa=c;<br>

  }<br>
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
