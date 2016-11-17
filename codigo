#include <TVout.h>
#include "TVoutfonts/fontALL.h"
#include "schematic.h"
#include "TVOlogo.h"

TVout TV;

int db0s=0;
int db1s=0;
int db2s=0;
int db3s=0;
int db4s=0;
int db5s=0;
int db6s=0;
int db7s=0;
int rws=0;
int rs=0;


void setup() {
  TV.begin(NTSC,120,96);
  TV.select_font(font6x8);

  pinMode(2, INPUT);
  pinMode(3, INPUT);
  pinMode(4, INPUT);
  pinMode(5, INPUT);
  pinMode(6, INPUT);
  pinMode(8, INPUT);
  pinMode(10, INPUT);
  pinMode(11, INPUT);
  pinMode(12, INPUT);
  pinMode(13, INPUT);
  
}

void loop() {
  char a[] = "assss";
  long t=0;
  int s2=digitalRead(2);
  int s3=digitalRead(3);
  int s4=digitalRead(4);
  int s5=digitalRead(5);
  int s6=digitalRead(6);
  int s8=digitalRead(8);
  int s10=digitalRead(10);
  int s11=digitalRead(11);
  int s12= digitalRead(12);
  int s13= digitalRead(13);

  if(s12==HIGH){

    if(s2==LOW && s3==LOW && s4 ==LOW && s5 == LOW && s6 ==LOW && s8==HIGH && s10 == LOW && s11==LOW){

    }
    else{
      if(s2==HIGH && s3==LOW && s4 ==LOW && s5 == LOW && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("A");
      }
      if(s2==LOW && s3==HIGH && s4 ==LOW && s5 == LOW && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("B");
      }
      if(s2==HIGH && s3==HIGH && s4 ==LOW && s5 == LOW && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("C");
      }
      if(s2==LOW && s3==LOW && s4 ==HIGH && s5 == LOW && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("D");
      }
      if(s2==HIGH && s3==LOW && s4 ==HIGH && s5 == LOW && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("E");
      }
      if(s2==LOW && s3==HIGH && s4 ==HIGH && s5 == LOW && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("F");
      }
      if(s2==HIGH && s3==HIGH && s4 ==HIGH && s5 == LOW && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("G");
      }
      if(s2==LOW && s3==LOW && s4 ==LOW && s5 == HIGH && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("H");
      }
      if(s2==HIGH && s3==LOW && s4 ==LOW && s5 == HIGH && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("I");
      }
      if(s2==LOW && s3==HIGH && s4 ==LOW && s5 == HIGH && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("J");
      }
      if(s2==HIGH && s3==HIGH && s4 ==LOW && s5 == HIGH && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("K");
      }
      if(s2==LOW && s3==LOW && s4 ==HIGH && s5 == HIGH && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("L");
      }
      if(s2==HIGH && s3==LOW && s4 ==HIGH && s5 == HIGH && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("M");
      }
      if(s2==LOW && s3==HIGH && s4 ==HIGH && s5 == HIGH && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("N");
      }
      if(s2==HIGH && s3==HIGH && s4 ==HIGH && s5 == HIGH && s6 ==LOW && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("O");
      }
      if(s2==LOW && s3==LOW && s4 ==LOW && s5 == LOW && s6 ==HIGH && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("P");
      }
      if(s2==HIGH && s3==LOW && s4 ==LOW && s5 == LOW && s6 ==HIGH && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("Q");
      }
      if(s2==LOW && s3==HIGH && s4 ==LOW && s5 == LOW && s6 ==HIGH && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("R");
      }
      if(s2==HIGH && s3==HIGH && s4 ==LOW && s5 == LOW && s6 ==HIGH && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("S");
      }
      if(s2==LOW && s3==LOW && s4 ==HIGH && s5 == LOW && s6 ==HIGH && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("T");
      }
      if(s2==HIGH && s3==LOW && s4 ==HIGH && s5 == LOW && s6 ==HIGH && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("U");
      }
      if(s2==LOW && s3==HIGH && s4 ==HIGH && s5 == LOW && s6 ==HIGH && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("V");
      }
      if(s2==HIGH && s3==HIGH && s4 ==HIGH && s5 == LOW && s6 ==HIGH && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("W");
      }
      if(s2==LOW && s3==LOW && s4 ==LOW && s5 == HIGH && s6 ==HIGH && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("X");
      }
      if(s2==HIGH && s3==LOW && s4 ==LOW && s5 == HIGH && s6 ==HIGH && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("Y");
      }
      if(s2==LOW && s3==HIGH && s4 ==LOW && s5 == HIGH && s6 ==HIGH && s8==LOW && s10 == HIGH && s11==LOW){
        TV.print("Z");
      }
      if(s2==HIGH && s3==LOW && s4==LOW && s5== LOW && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("a");
      }

      if(s2==LOW && s3==HIGH && s4==LOW && s5== LOW && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("b");
      }

      if(s2==HIGH && s3==HIGH && s4==LOW && s5== LOW && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("c");
      }

      if(s2==LOW && s3==LOW && s4==HIGH && s5== LOW && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("d");
      }

      if(s2==HIGH && s3==LOW && s4==HIGH && s5== LOW && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("e");
      }

      if(s2==LOW && s3==HIGH && s4==HIGH && s5== LOW && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("f");
      }

      if(s2==HIGH && s3==HIGH && s4==HIGH && s5== LOW && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("g");
      }
      if(s2==HIGH && s3==LOW && s4==LOW && s5== HIGH && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("h");
      }
      if(s2==LOW && s3==HIGH && s4==LOW && s5== HIGH && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("i");
      }
      if(s2==LOW && s3==HIGH && s4==HIGH && s5== LOW && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("j");
      }
      if(s2==HIGH && s3==HIGH && s4==LOW && s5== HIGH && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("k");
      }

      if(s2==LOW && s3==LOW && s4==HIGH && s5== HIGH && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("l");
      }

      if(s2==HIGH && s3==LOW && s4==HIGH && s5== HIGH && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("m");
      }

      if(s2==LOW && s3==HIGH && s4==HIGH && s5== HIGH && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("n");
      }

      if(s2==HIGH && s3==HIGH && s4==HIGH && s5== HIGH && s6==LOW && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("o");
      }


      if(s2==LOW && s3==LOW && s4==LOW && s5== LOW && s6==HIGH && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("p");
      }

      if(s2==HIGH && s3==LOW && s4==LOW && s5== LOW && s6==HIGH && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("q");
      }

      if(s2==LOW && s3==HIGH && s4==LOW && s5== LOW && s6==HIGH && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("r");
      }

      if(s2==HIGH && s3==HIGH && s4==LOW && s5== LOW && s6==HIGH && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("s");
      }

      if(s2==LOW && s3==LOW && s4==HIGH && s5== LOW && s6==HIGH && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("t");
      }
      if(s2==HIGH && s3==LOW && s4==HIGH && s5== LOW && s6==HIGH && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("u");
      }
      if(s2==LOW && s3==HIGH && s4==HIGH && s5== LOW && s6==HIGH && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("v");
      }
      if(s2==HIGH && s3==HIGH && s4==HIGH && s5== LOW && s6==HIGH && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("w");
      }
      if(s2==LOW && s3==LOW && s4==LOW && s5== HIGH && s6==HIGH && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("x");
      }
      if(s2==HIGH && s3==LOW && s4==LOW && s5== HIGH && s6==HIGH && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("y");
      }
      if(s2==LOW && s3==HIGH && s4==LOW && s5== HIGH && s6==HIGH && s8==HIGH && s10==HIGH && s11==LOW){
        TV.print("z");
      }  
    }
  }



  delay(1000);
  TV.clear_screen();

}

void intro() {
  unsigned char w,l,wb;
  int index;
  w = pgm_read_byte(TVOlogo);
  l = pgm_read_byte(TVOlogo+1);
  if (w&7)
    wb = w/8 + 1;
  else
    wb = w/8;
  index = wb*(l-1) + 2;
  for ( unsigned char i = 1; i < l; i++ ) {
    TV.bitmap((TV.hres() - w)/2,0,TVOlogo,index,w,i);
    index-= wb;
    TV.delay(50);
  }
  for (unsigned char i = 0; i < (TV.vres() - l)/2; i++) {
    TV.bitmap((TV.hres() - w)/2,i,TVOlogo);
    TV.delay(50);
  }
  TV.delay(3000);
  TV.clear_screen();
}
