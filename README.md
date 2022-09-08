# AutocorrelationArt

This program is written in Java 8. There are two components to the program. The first program, TMauto.java generates an array of 4th-order Thue-Morse autocorrelation functions called ArtOutput.csv . TMart.java converts the array into a bitmap, each entry of the array has its output as a color.

You may change the size of the array by changing the input[3] integer in TMauto.java. Let's call this integer z. Then the (x,y) entry of the array will consist of Thue-Morse autocorrelation function with parameters (x,y,z), with x ranging from input[1] to z, and y ranging from input[2] to z.

  
