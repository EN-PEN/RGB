實作：
```C++
int A=0;
void setup() {
  // put your setup code here, to run once:
  for(int i =9 ;i<12;i++)(設定輸出9~12)
  pinMode(i,OUTPUT);(輸出位 = 9)
}

void loop() {
 analogWrite(9,45);(設定數值RGB_B)
 analogWrite(10,90);(設定數值RGB_G)
 analogWrite(11,90);(設定數值RGB_R)
}
```

題目二:呼吸燈
```C++
int x =120;(設定最大值)

int y =10;(設定層遞值)

void setup() {

  // put your setup code here, to run once:

  pinMode (10,OUTPUT);(設定輸出腳為10)

}

void loop() {

  // put your main code here, to run repeatedly:

   analogWrite(10,x);

   x = x-y;

   if(x ==0 || x ==120)(遞增)

   y = -y;

   delay(80);

   }
   ```
   圖：![image](https://github.com/EN-PEN/RGB/blob/master/IMG20200929132851.jpg)
   

  
