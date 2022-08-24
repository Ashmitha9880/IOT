# IOT

https://wokwi.com/projects/333715334647251538 :TRAFIC SIGNAL<br>
https://wokwi.com/projects/333715334647251538 :TRAFIC SIGNAL<br>
https://wokwi.com/projects/333801348249158228 :RGB LIGHTS<br>
https://wokwi.com/projects/333804935094207058 :lcd<br>
https://wokwi.com/projects/322062421191557714 :HELLO,WOKWI<br>
https://wokwi.com/projects/334977500040921682 :servometer<br>
https://wokwi.com/projects/335703098296107604 :servometer with button<br>
https://wokwi.com/projects/334980975137129043<br>
https://wokwi.com/projects/334982758191333971 :potentiometer slide<br>
https://wokwi.com/projects/335065585212719699 :buzzer<br>
https://wokwi.com/projects/335067506404229716 :BUZZER +button<br>
https://wokwi.com/projects/335070214584533588 :ultra sonic senser<br>
https://wokwi.com/projects/335073264458007124 :ultra sonic +buzzer<br>
https://wokwi.com/projects/335075055329346132 :varring with intensity<br>
https://wokwi.com/projects/335611957619982931 :ultra sonic +buzzer+led<br>
https://wokwi.com/projects/335617038976287315 :using 2 ultrasonic senser<br>
https://wokwi.com/projects/335702624840974931 :potentiometer with LED<br>



https://wokwi.com/projects/337602055475561044 :led with buzzer<br>
https://wokwi.com/projects/337604163653337682 :DHT22(Humidity and Temperature sensor ESP32<br>
https://wokwi.com/projects/337604296859189842 :DHT22(Humidity and Temperature sensor ESP32 with LCD<br>


int ldr=A0;//Set A0(Analog Input) for LDR.<br><br>
 int value=0;<br><br>
 int led=D1;<br><br>
 void setup() {<br><br>
 Serial.begin(9600);<br><br>
 pinMode(led,OUTPUT);<br><br>
 }<br><br>
</br>
     void loop() {<br><br>
     value=analogRead(ldr);//Reads the Value of LDR(light).<br><br>
     Serial.println("LDR value is :");//Prints the value of LDR to Serial Monitor.<br><br>
     Serial.println(value);<br><br>
     if(value<50)<br><br>
       {<br>
         digitalWrite(led,HIGH);//Makes the LED glow in Dark.<br>
       }<br>
       else<br>
       {<br>
         digitalWrite(led,LOW);//Turns the LED OFF in Light.<br>
       }<br>
       delay(1000);<br>
     }<br>
    <br>


https://wokwi.com/projects/340775764469219922 - LED_CHASER<br>
https://wokwi.com/projects/340776572602548818 - LDR<br>
https://wokwi.com/projects/340776926585029204 - LDR_LED<br>
https://wokwi.com/projects/340779619162522195 - IR_LED<br>

ESP32<br>
https://wokwi.com/projects/336966830711112275 - LED<br>
https://wokwi.com/projects/336967978479256147 - 3 LED<br>
https://wokwi.com/projects/340853325803029074 (RGB MULTICOLOR)
