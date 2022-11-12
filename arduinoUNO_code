\

#define sensorpin1 A0 // analog pin 0
#define sensorpin2 A1
#define sensorpin3 A2
#define sensorpin4 A3
const int buzzer=7;
void setup() {
 Serial.begin(9600);
 pinMode(buzzer, OUTPUT);
}

void loop() {
  int a=analogRead(sensorpin1);
  int b=analogRead(sensorpin2);
  int c=analogRead(sensorpin3);
  int d=analogRead(sensorpin4);
   Serial.println(a);
   Serial.println(b);
   
   Serial.println(c);
   Serial.println(d);
   Serial.println("----------------------------");
    if(a>1000 || b>1000 || c>1000 || d>1000){
      delay(500);

      
     tone(buzzer,1000);
      delay(1007 );
    }
    else {
      
      
     noTone(buzzer);
     delay(100);
    }
    delay(1000);
}
