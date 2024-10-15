#include <iostream>
#include <string>
using namespace std;
class Car
{
private:
	int yearModel;
	string make;
	int speed;
public:
	Car(int ymodel, string mak)
	{
		yearModel = ymodel;
		make = mak;
		speed = 0;
	}
	void setYearModel(int ymodel)
	{
		yearModel = ymodel;
	}
	void setMake(string mak)
	{
		make = mak;
	}
	void setSpeed(int speedd)
	{
		speed = speedd;
	}
	int getYearModel()
	{
		return yearModel;
	}
	string getMake()
	{
		return make;
	}
	int getSpeed()
	{
		return speed;
	}
	
};
int main()
{
	Car* car = new Car(2017, "Cultus");
	cout << "Initial Speed: " << car->getSpeed() << endl;
	for (int i = 0; i < 5; i++)
	{
		car->accelerate();
		cout << "Final Speed after accelerate: " << car->getSpeed ()<< endl;
	}
	for (int i = 0; i < 5; i++)
	{
		car->brake();
		cout << "Final Speed after brake: " << car->getSpeed() << endl;
	}
	delete car;
	return 0;
}