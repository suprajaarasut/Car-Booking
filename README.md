Call Taxi Booking
•	FEATURES:
1.This is a passenger booking app where you can travel conveniently availing taxi service within 5 minutes of requesting a ride.
2.Figures out equal ride opportunity for each driver of respective cabs considering the taxi which earned least during the day.
3.There are different commands that adds essence to it 

•	COMMANDS:

      SYNTAX	                          DESCRIPTION
Struct customer details        	Lists out the details of the customer such as customer ID, starting point ,end point ,time 
Struct taxi details	            Lists out the details of the taxi such as current location of the taxi,time,pick up from,to drop location,amount charged 
int total price ()            	Amount estimated for a drive based on the distance travelled 
int calculate price ()        	Its allocated based on the cabs that’s availed nearest to the customer and also by considering the drivers Income earned in a day 
int customer call ()          	Sharing all the booking essentials to the rider to pick and drop the customer.
Void taxi entry details	()      It will denotes the current taxi number that will tend to give the ride with stating the customer details that was given during the booking period
int main ( )	                  It is the actual design of how the process will be preceeded over.The loop continues to run for each second and gives out the actual info as per
                                the details we enter.For instance ,if we give option 1 then it will be asked for certain details as listed below 

*******SAMPLE OUTPUT:*******
Enter
1.To Book a call taxi
2.To display taxi details
3.To exit
1
Enter customer id
Enter Starting point
Enter Ending point
1
a
c
Enter time  hr:min format  12:00
Enter
1.To Book a call taxi
2.To display taxi details
3.To exit
2
Taxi_1 details:
    customer 1:
      1:customer_ID  1
      2:from position a to c
      3:picked up at 12:0, dropped at 12:30
      4:Amount earned Rs.300
Total price earned by taxi_1 is Rs.300
Enter
1.To Book a call taxi
2.To display taxi details
3.To exit
3

