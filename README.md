const int SWITCH1=14;


const int relay1=2;

void setup()  {
pinMode(SWITCH1,INPUT_PULLUP);
           
 

   
pinMode(relay1,OUTPUT);

 }
 void loop() {


  if (digitalRead(SWITCH1)==LOW)
  
  digitalWrite(relay1,LOW);

    delay(60000);
  {
    if (digitalRead(SWITCH1)==HIGH)
 {
    digitalWrite(relay1,HIGH);
  }
    delay(200); 
   }
 }

 
