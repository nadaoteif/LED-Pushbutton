
# Design LED Controller using Pushbutton
## Overview:

These tasks is completed by [Nada Oteif](https://sa.linkedin.com/in/nadaoteif) as a part of [Smart Method](https://s-m.com.sa/en/index.html) for Summer training in 2022 at Electronics and Power track.

## Description:

### LED Pushbutton simulation


https://user-images.githubusercontent.com/85653190/184541626-f2135bc2-8d00-4512-9275-5205297b1c68.mp4


[Click here to view simulation in Tinkercad](https://www.tinkercad.com/things/0qY8K9aWPTH)

### Code 
``` c++ 
int btn = 0;

void setup() {
  pinMode(2, INPUT);
  pinMode(13, OUTPUT);
}

void loop() {
  btn = digitalRead(2);
  if(btn == HIGH){
    digitalWrite(13,HIGH);
  }
  else{
    digitalWrite(13, LOW);
  }
  delay(10);
}
```
