實作：
int A=0;
void setup() {
  // put your setup code here, to run once:
  for(int i =9 ;i<12;i++)
  pinMode(i,OUTPUT);
}

void loop() {
 analogWrite(9,45);
 analogWrite(10,90);
 analogWrite(11,90);
}


題目二:呼吸燈
int x =120;

int y =10;

void setup() {

  // put your setup code here, to run once:

  pinMode (10,OUTPUT);

}

void loop() {

  // put your main code here, to run repeatedly:

   analogWrite(10,x);

   x = x-y;

   if(x ==0 || x ==120)

   y = -y;

   delay(80);

   }
   圖：![image](https://github.com/EN-PEN/RGB/blob/master/IMG20200929132851.jpg)
   

  
