# Let-s-find-the-keys
int buzzer = 5;
void setup() 
{
    
    pinMode(buzzer,OUTPUT);    
}


void loop()
{
   
    tone(buzzer,261);    
   
    delay(200);
    
    noTone(buzzer); 
    
    tone(buzzer,293);             
    delay(200);    
    noTone(buzzer); 
    
    tone(buzzer,329);      
    delay(200);
    noTone(buzzer);     
    
    tone(buzzer,349);    
    delay(200);    
    noTone(buzzer); 
    
    tone(buzzer,392);            
    delay(200);
    noTone(buzzer); 
}
