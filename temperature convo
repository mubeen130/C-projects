#include <iostream>

int main() {
    double temp;
    char unit;

    std::cout<<"********** Temperature Conversion Pogramme **********\n";
    std::cout<<"F is for Fahrenhite\n";
    std::cout<<"C is for Celsius\n";
    std::cout<<"Type what unit you want to convert: ";
    std::cin>>unit;

    if (unit == 'F' || unit == 'f') {
        std::cout<<"Type the temperature in Celcius: ";
        std::cin>>temp;
        temp = (1.8* temp) + 32.0;
        std::cout<<"The temperature is: "<<temp<<" Celsius\n";
    }
    else if(unit == 'C' || unit == 'c') {
        std::cout<<"Type the temperature in Fahrenhite: ";
        std::cin>>temp;
        temp = (temp-32)/1.8;
        std::cout<<"The temperature is: "<<temp<<" Fahrenhite\n";
    }
    else {
        std::cout<<"Please type only F or C\n";
    }

    std::cout<<"*****************************************************";
    return 0;
}
