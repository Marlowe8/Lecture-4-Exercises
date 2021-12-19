# Lecture-4-Exercises

//USB SHOPPER
        #include <iostream>
        using namespace std;


        int main() {
          int UsbSticks, Price =6,Change;
          cout << "A girl wants to buy as many usb sticks she can. She only has 50 AED." << endl
            << " USB sticks cost 6 AED Each. Calculate How many USB She can buy. And how many fils she will have left." << endl;
          cout << "Press Enter to Continue..."<<endl;
          cin.ignore();
          UsbSticks = 50 / Price;
          Change = 50 % Price;
          cout << "She can buy [" << UsbSticks << "] USB sticks. And her change is: " << Change << " AED " << endl;
          return 0;
        }
  
//Declaration and Initialisation  
          #include <iostream>
        using namespace std;


        int main() {
          int value1 = 8;
          int value2 = 10;
          int result = value1 + value2;
          cout << "8 + 10" << " = " << result;
          return 0;
        }
