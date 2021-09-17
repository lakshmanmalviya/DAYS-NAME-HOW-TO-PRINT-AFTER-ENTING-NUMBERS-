<!-- # DAYS-NAME-HOW-TO-PRINT-AFTER-ENTING-NUMBERS-
HOW TO COME DAY'S NAME  AFTER ENTERING THEM DAYWISE NUMBER -->
 
#include <iostream>

using namespace std;

int main()
{
     int day;
     cout<<" Enter the number of day which you want to know ";
     cin>>day;
      if(day ==1)
      cout<<"monday "<<endl;
      else if(day ==2)
      cout<<"tuesday "<<endl; 
      else if(day ==3)
      cout<<"wednusday "<<endl; 
      else if(day ==4)
      cout<<" thursday  "<<endl; 
      else if(day ==5)
      cout<<"friday "<<endl; 
      else if(day ==6)
      
      cout<<"saturday "<<endl;
      else if ( day ==7)
      cout<<"sunday "<<endl;
      else if (day>7)
      cout<<"you have entered the incorrect no ";
      else
      cout<<" you typed wrong number of the day ";
    
      

    return 0;
}

