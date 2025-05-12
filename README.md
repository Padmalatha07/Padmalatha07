int NorthRedpin=2;
int NorthredYellowpin=3;
int NorthGreenpin=4;
int SouthRedpin=5;
int SouthYellowpin=6;
int SouthGreenpin=7;
int EastRedpin=8;
int EastYellowpin=9;
int EastGreenpin=10;
int WestRedpin=11;
int WestYellowpin=12;
int WestGreenpin=13;
void setup(){
pinMode(2, OUTPUT);
pinMode(3, OUTPUT);
pinMode(4, OUTPUT);
pinMode(5, OUTPUT);
pinMode(6, OUTPUT);
pinMode(7, OUTPUT);
pinMode(8, OUTPUT);
pinMode(9, OUTPUT);
pinMode(10, OUTPUT);
pinMode(11, OUTPUT);
pinMode(12, OUTPUT);
pinMode(13, OUTPUT);
}
void loop(){
digitalWrite(2, low); //North//
digitalWrite(4, High);
delay(5000);
digitalWrite(4, low);
digitalWrite(3, High);
delay(2000);
digitalWrite(2, High);
digitalWrite(5, low);//south//
digitalWrite(7, High);
delay(5000);
digitalWrite(7, low);
digitalWrite(6, High);
delay(2000);
digitalWrite(5, High);
digitalWrite(8, low);//East//
digitalWrite(10, High);
delay(5000);
digitalWrite(10, low);
digitalWrite(9, High);
delay(2000);
digitalWrite(8, High);
digitalWrite(11, low);//West//
digitalWrite(13, High);
delay(5000);
digitalWrite(13, low);
digitalWrite(12, High);
delay(2000);
digitalWrite(11, High);
}



