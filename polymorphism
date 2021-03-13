#include <iostream>
#include <string>
using namespace std;

class Vehicle 
{
  public:
  	virtual void StartEngine() 
    {
      cout << "Vehicle engine started\n" ;
    }
};

class Car : public Vehicle 
{
  public:
    void StartEngine() 
    {
      cout << "Car engine started\n" ;
    }
};

class Ship : public Vehicle 
{
  public:
    void StartEngine() 
    {
      cout << "Ship engine started\n" ;
    }
};

class Motorcycle : public Vehicle 
{
  public:
    void StartEngine() 
    {
      cout << "Motorcycle engine started\n" ;
    }
};

int main() 
{
  Vehicle *vehicle;
  Car car;
  Ship ship;
  Motorcycle motorcycle;

  vehicle = &car;
  vehicle->StartEngine();     //Car engine started
  
  vehicle = &ship;
  vehicle->StartEngine();     //Ship engine started
  
  vehicle = &motorcycle;
  vehicle->StartEngine();     //Motorcycle engine started
  
  return 0;
}
