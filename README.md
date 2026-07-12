# WEATHER-APP-PROJECT
This is an API based project that uses wttr.in API in order to get the information about the weather.
On running the program, it will show you the MAIN MENU containing four options  
1. CURRENT WEATHER REPORT
2. SEARCH HISTORY
3. DELETE SEARCH HISTORY
4. EXIT

<img width="1036" height="276" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/c957fd02-5ffb-425c-b49d-762f32a545c4" />

You can see a number is present before each option. The user has to enter the number present before the option in order to use it.

Now let's understand the functionalities of the four options of the MAIN MENU.

##CURRENT WEATHER REPORT
Enter the integer 1 in order to use this option. Then you have to enter the name of the city whose current weather conditions you want to know. The temperature (°C), humidity(%), weather description and wind speed(in kilometer per hour) will be displayed
<img width="1063" height="350" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/8e5d7bbc-2451-4cbc-b393-cc12ddc9f895" />

A message will appaer  at the bottom. Here if you Enter 'y' or 'Y', the weather forecast of the present day and upcoming two days will be displayed
<img width="1061" height="851" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/275bf491-f143-4a1d-a1ab-d410384e8856" />
 Note that in the output, date is in YYYY-MM-DD format.

 You can see at the bottom, the MAIN MENU appears, this is because the program is running in an infinite loop. In order to close the program you have to use the EXIT option by entering the integer 4. This will make the program to break the infinite loop and to exit from the program. Let's see the current weather repot of two more cities but here we are not interested to know thew forecast.
 <img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/4b71dbdf-cb3c-487c-98aa-6060c0301b08" />

##SEARCH HISTORY

Enter the integer 2 in order to use the SEARCH HISTORY of the MAIN MENU. You will get the entire search historhy containing the searched locations in newest to oldest order i.e. the city which you have searched at first will appear at the bottom and the city which you have searched at last will appear in the top.
<img width="1920" height="1080" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/c90143be-9068-47f7-8699-342e5f7164c1" />

The names of the cities in the searchrd history are stored in a binary file so that can be stored in the computer memory permanently and the data will not lost if the computer is switched off.
You can see integers before the searched cities. You can enter 
 
 
  

