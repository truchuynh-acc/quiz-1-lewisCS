[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name: Lewis Figueroa
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer:

#include <iostream>
#include <string>

class Car {
public:
    private: std::string model;
    private: int year;
    private: std::string color;

    void displayDetails() {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }

    void setYear(int year){
        this->year = yearl;
    }
    void setModel(std::string model){
        this->model = model;
    }
    void setColor(std::string color)
    {
        this->color = color;
    }
    std::string getColor(){
        return color;
    }
    std::string getModel(){
        return model;
    }
    int getYear(){
        return year;
    }
};

int main() {
    Car myCar;


    myCar.displayDetails();

    return 0;
}

```
