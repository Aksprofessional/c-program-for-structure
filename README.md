# c-program-for-structure
//c++ program for structure
#include <iostream>

struct emp{
    char name[10];
    int age,salary;
    void get(){
    std::cout<<"enter name age and salary"<<"\n";
    std::cin>>name>>age>>salary;
}
void show(){
    std::cout<<name<<"\n"<<age<<"\n"<<salary<<"\n";
}
};
int main() {
    emp e,h;
    e.get();
    e.show();
    h.get();
    h.show();
    h.name;
    return 0;
}
