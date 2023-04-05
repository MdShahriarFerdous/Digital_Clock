# Digital_Clock


1. First I have taken a function called digitalClockTime() which has the variables for 
the divs selection by DOM.

2. Then  I have declared the new Date() object and define the hrs, mins and sec variables.
here I said  if hour is above 12 (like 13,14) then (-) 12 from it or the regular getHours() method
and assign it to the hrs variables. I have used ternary operator here.

3. I have write the ternary operator for mins also where i said 
if minutes are less than 10 (like 9,8) then concatenate 0 infront of it. (like 09/08/07 mins.)

4. Same I have done with seconds.

5. Then I have taken a variable for AM or PM by saying if hour is less than 12 noon 
then it is AM except from that it is PM.

6. After that I have again filtered the hours for the concatination with 0 
and if the hour is 00 or 0 then it means the 12 AM.
this ternary operator is like if and else if. 
if hour is less than 10 then add a 0 infront of it
else if hour is equal to 0 then it is 12 AM
else the regular hour from top.
			
7. Then selected the innerHTML for all the hours, minutes, seconds and AM/PM divs. 
				

8. After that I have also declared a function for the regular date where I have 
declared a array of all the days in a week which starts from sunday at index 0.

9. Then days[date.getDay()] says that days means an array of week list and date.getDay() will
give a week number from 0-6...like days[0] or days[1] or days[2] and so on. By this I have
found the current day of the week. After that I have  return the current Day and current Date.
And called the function digitalClockDate() and set into the date div innerHTML.

10. At last I have called the setInterval(digitalClockTime, 1000) for update the clock every second. 


		
