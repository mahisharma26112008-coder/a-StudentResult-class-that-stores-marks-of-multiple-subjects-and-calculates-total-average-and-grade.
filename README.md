# a-StudentResult-class-that-stores-marks-of-multiple-subjects-and-calculates-total-average-and-grade.

#include<iostream>
  using namespace std;

class student {
   public:
    int roll_number;
    string name;
    int marks_of_hindi;
    int marks_of_english;
    int marks_of_math;
    int marks_of_science;
    int marks_of_social_science;

    void total(){

        cout<<name<<"\n";
        cout<<roll_number<<"\n";
        
   int total_marks= marks_of_hindi+marks_of_english+ marks_of_math+ marks_of_science+ marks_of_social_science;
        
        int average=total_marks/5;

        cout<<"total marks"<<total_marks<<"\n";
        cout<<"average marks"<<average<<"\n";

        if(average>=300){
            cout<<"result : pass";
        }
        else{
            cout<<"result : fail";
        }
    }
};
int main(){
    student s1;
    cout<<"enter your name"<<"\n";
    cin>>s1.name;

    cout<<"enter your roll number"<<"\n";
    cin>>s1.roll_number;

    cout<<"enter marks of hindi"<<"\n";
    cin>>s1.marks_of_hindi;

    cout<<"enter marks of english"<<"\n";
    cin>>s1.marks_of_english;

    cout<<"enter marks of math"<<"\n";
    cin>>s1.marks_of_math;

    cout<<"enter marks of science"<<"\n";
    cin>>s1.marks_of_science;

    cout<<"enter marks of social science"<<"\n";
    cin>>s1.marks_of_social_science;

    s1.total();

    return 0;

}


    

































































        

    
