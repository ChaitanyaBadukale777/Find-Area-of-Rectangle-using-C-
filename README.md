# Find-Area-of-Rectangle-using-C-

#include<iostream>
using namespace std;
class Rectangle{
    public:
    int length,breadth;
    int area(){
        return length*breadth;
    }
};
int main(){
    Rectangle rect1;
    rect1.length = 10;
    rect1.breadth = 20;
    cout << "Area is:" << rect1.area();
    return 0;
}
