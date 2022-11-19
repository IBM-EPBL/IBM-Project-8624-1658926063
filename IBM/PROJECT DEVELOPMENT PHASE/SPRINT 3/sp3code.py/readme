#include <TinyGPS++.h> 
#include <SoftwareSerial.h> 
TinyGPSPlus gps; 
SoftwareSerial ss (3,4); char 
n; 
int a; 
void setup() { 
Serial.begin(9600); 
ss.begin(9600); pinMode (2, 
INPUT): pinMode (6, 
OUTPUT); pinMode(11, 
OUTPUT); pinMode(10, 
OUTPUT); pinMode (9, 
OUTPUT); pinMode (12, 
OUTPUT); //apr 
digitalWrite(11,HIGH); 
digitalWrite(6,HIGH); 
attachInterrupt (digitalPinToInterrupt (2), piezo,CHANGE); 
} 
void loop() { nSerial.read(); // 
Serial.println(" "); 
delay (200); 
if (n=='3') { 
digitalWrite(6,HIGH); 
digitalWrite(11,HIGH); 
digitalWrite(12,HIGH); 
delay(200); 
digitalWrite(12,LOW); } 
else if (n=='2') 
digitalWrite(6,LOW); 
digitalWrite(11,LOW); 
digitalWrite(10,LOW); 
digitalWrite(9,LOW); 
digitalWrite(12,HIGH); 
delay(200); 
digitalWrite(12,LOW); } 
else if (n=='1') 
analogWrite(11,100); 
analogWrite(6,100); 
digitalWrite(12,HIGH); 
delay(200); 
digitalWrite(12,LOW); 
} 
} 
// while (ss.available() > 0) 
// if (gps.encode(ss.read())) 
// displayInfo(); void 
displayInfo() 
{ 
// Serial.print (F("Location: ")); if 
(gps.location.isValid()) 
Serial.print(gps.location.lat(), 6); 
Serial.print (F(",")); 
Serial.print(gps.location. Ing(), 6); } else 
// Serial.print (F ("INVALID")); 
Serial.print("10.305125"); 
Serial.print(','); 
Serial.print("76.389582"); 
} 
/* Serial.print(F(" Date/Time: ")); 
if (gps.date.isValid()) 
{ 
Serial.print(gps.date.month()); 
Serial.print (F("/")); 
Serial.print(gps.date.day()); 
Serial.print (F("/")); 
Serial.print(gps.date.year()); 
} 
else 
{ 
Serial.print(F("INVALID")); 
} 
Serial.print (F(" ")); 
if (gps.time.isValid()) 
{ 
if (gps.time.hour() < 10) Serial.print (F("0")); 
Serial.print(gps.time.hour()); Serial.print 
(F(":")); 
if (gps.time.minute() < 10) Serial.print(F("0")); 
Serial.print (gps.time.minute()); Serial.print 
(F(":")); 
if (gps.time.second() < 10) Serial.print(F("0")); 
Serial.print(gps.time.second()); Serial.print 
(F(".")); 
if (gps.time.centisecond() < 10) Serial.print(F("0")); 
Serial.print(gps.time.centisecond()); 
} 
else 
{ 
// Serial.print (F("INVALID")); 
}*/ 
Serial.println(); 
}
