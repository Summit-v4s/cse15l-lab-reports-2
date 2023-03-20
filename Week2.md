**CSE 15L Week 2 Lab Report**

**Seungki Kim**

**Part 1**
This is the code for writing web server called StringServer.
![](https://cdn.discordapp.com/attachments/890102969536753746/1087227203357511720/image.png)

This is the first added string.
<br>
![](https://cdn.discordapp.com/attachments/890102969536753746/1087228463108341831/image.png)

For this first line of string, method handleRequest was called. When 'add-message' was added to the URL, String array parameters were also changed, and the if statement added the following string into the list.

This is the second added string.
<br>
![](https://cdn.discordapp.com/attachments/890102969536753746/1087228463108341831/image.png)

For this second string, method handleRequest was called, going through the same step of changing the array parameter as the URL also changed. Lastly, new string was added to the list.


**Part 2**
<br>
Failure-inducing input
<br>
![](https://cdn.discordapp.com/attachments/890102969536753746/1087231540133642250/image.png)

This test case 'testReversedNonEmptyArray' checks that the method does not correctly reverse an array of int when there are more than one element in the array.
<br>
Non-failure inducing input
<br>
![](https://cdn.discordapp.com/attachments/890102969536753746/1087232545797713930/image.png)

Symptom of failure-inducing input
<br>
![](https://cdn.discordapp.com/attachments/890102969536753746/1087231701362688130/image.png)

Fixed bugs
<br>
![](https://cdn.discordapp.com/attachments/890102969536753746/1087238223610249316/image.png)
<br>

reversedInPlace: Updated loop condition to 'i < arr.length / 2'
reversed: Created new array 'newArray' to store the reversed elements and updated the loop to store 'newArray' in reverse order.
averageWithoutLowest: Added varaible 'count' to measure the number of elements that are being used for average calculation. Also, updated the loop to only add elements not equal to the lowest value, and increment 'count' afterwards.

**Part 3**
In lab 2&3, I've learned how codes for running servers work, and how I can create my own local server using functions in java. I've always wondered how web servers are created from scratch, and this gave me the very basic information on how servers run.
