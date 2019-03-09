# arduino-lab-2-team-1
arduino-lab-2-team-1 created by GitHub Classroom

QUESTIONS:
1.   What is happening with the dimmer code pattern in part D step 3? 
        The logic analyzer illustrated the PWM behavior of the dimmer code. The on and off time varied depending on the positioning of the slide pot.

2.   What does the decoded message say in part D step 4? 
        You can see the bit encoding that was being sent to the ESP32866. The decoded message prints a series of numbers that were sent to the serial port.

3.   How long does ESP8266_to_Mega() take in part D step 5? 
        Around 257us.

4.   How long does  ReadSensors() take in part D step 5?
        Around 13.16ms.

5.   How long does ESP8266_to_Mega() take in part D step 6? 
        Around 250us.

6.   How long does  ReadSensors() take in part D step 6?
        Around 8.665ms.

7.   Compare serial monitor debugging with logic analyzer debugging. What are the pros and cons of each?
        Serial Monitor:
          Pros: More readable and understandable
          Cons: More intrusive  
        Logic Analyzer:
          Pros: Less intrusive
          Cons: Harder to understand

8.   Why do we need to connect the logic analyzer to the same ground as the Arduino?
         Same reference point.

