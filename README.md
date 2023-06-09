# 3rd
#include<iostream>
using namespace std;
// Third class of conditional Statements


// If Statement
// int main(){
//     int num;
//     cout<<"Enter the marks you have got : ";
//     cin>>num;
//     if(num<33){
//         cout<<"You have failed the exam."<<endl;
//     }else{
//         cout<<"You have passed the exam."<<endl;
//     }
//     return 0;
// }


// If-else-IF statement
// int main(){
//     int num;
//     cout<<"Enter the marks you have got : ";
//     cin>>num;
//     if(num<33){
//         cout<<"You have failed the exam."<<endl;
//     }else if(num>90){
//         cout<<"You have passed the exam with great marks."<<endl;
//     }else{
//         cout<<"You have passed the exam only."<<endl;
//     }
//     return 0;
// }


//Q1. Write a program to divide people into 3 groups depending on the following criteria

// int main(){
//     int age;
//     cout<<"Enter your Age : ";
//     cin>>age;
//     if(age<12){
//         cout<<"Child";
//     }else if(age>=12 && age<=18){
//         cout<<"Teenager";
//     }else{
//         cout<<"Adult";
//     }
//     return 0;
// }



// Solving the same problem with ternery operator

// int main(){
//     int marks;
//     cout<<"Enter the marks you have got : ";
//     cin>>marks;
//     marks>33 ? cout<<"Passed":cout<<"Failed";
//     return 0;
// }


// Switch Statement 

// int main(){
//     int days;
//     cin>>days;
//     switch(days){
//         case 1:
//         cout<<"Monday"<<endl;
//         break;
//         case 2:
//         cout<<"Tuesday"<<endl;
//         break;
//         case 3:
//         cout<<"Wednesday"<<endl;
//         break;
//         case 4:
//         cout<<"Thursday"<<endl;
//         break;
//         case 5:
//         cout<<"Friday"<<endl;
//         break;
//         case 6:
//         cout<<"Saturday"<<endl;
//         break;
//         case 7:
//         cout<<"Sunday"<<endl;
//         break;
//     }
//     return 0;
// }


// To Check the character to be vowel or a consonant
int main(){
    char Character;
    cout<<"Enter The Character you want to check in small letters : ";
    cin>>Character;
    switch(Character){
        case 'a':  
        cout<<"Vowel"<<endl;
        break;
        case 'e':  
        cout<<"Vowel"<<endl;
        break;
        case 'i':  
        cout<<"Vowel"<<endl;
        break;
        case 'o':  
        cout<<"Vowel"<<endl;
        break;
        case 'u':  
        cout<<"Vowel"<<endl;
        break;
        default:
        cout<<"Consonents"<<endl;
        break;
    }
    return 0;
}
