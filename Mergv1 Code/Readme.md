This code is part of a youtube play list series found at the link below.

https://www.youtube.com/playlist?list=PL2Mz1GBib5AueluEywwCpPj4Y_bB1dpVP

for this version you need to watch 2 videos 

1. https://www.youtube.com/watch?v=8iKSPyp0_NA&list=PL2Mz1GBib5AueluEywwCpPj4Y_bB1dpVP&index=1

2. 

The blink code is one of the first code people learning to program micro controllers or Raspberry PI tend to learn. So I have also started with this demonstration on here. This example is not the only way this could be done. However I have tried to keep it as simple as I can. The PIC I am using has many inputs and output pins. I will be programming on PORTD this has 8 I/O pins Labelled D0 - D7.

The explanation of the code is after the full code below. I would also suggest that you try to change some of the code to change the led flashing and also the delay time.

Once you are comfortable with the code then you can move onto the next version Blink V2.

---------------------------------------------------------------------------

Try Changing Parts Of The Code

You can change the delay value of each led by changing the value inside of the “(3000)” now 3 seconds delay.

You can change the the allocation of the output pin. To do this you need to change 3 things.

TRISD0 change the 0 to which pin number you want so pin 1 becomes “TRISD1”.

RD0=1; Change the 0 to which pin number you want so pin 1 becomes “RD1=1;”.

RD0=0; Change the 0 to which pin number you want so pin 1 becomes “RD1=0;”.

Now recompile your code and up load to the PIC.