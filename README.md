# hello-world
my repository
just to try

function average(array)    // filter odd numbers
{
var total = 0;
for (var i=0; i<array.length; i++) 
{
if (i%2 != 0)

total=total + array[i];
}
var aver = total / array.length;
return aver
}




function charCount(str, letter)
{
var originalWord = " ";
var myWord = originalWord.toLowerCase;  //uppercase to lowercase
var firstLetter = myWord.charAt(0);   //select first character
var letterCount = 0;               //count from 0
var alphabet = 'abcdefghijklmnopqrstuvwxyz';
for (var i=0; i<myWord.length; i++)         // check 1st letter is string
{
if(str.charAt(i) == firstLetter)
{
letterCount +=1;
}
}
return letterCount
}



public class Cards
{ 
private String c;
public Card(String value, String color)
{
var color = ["Heart", "Diamond", "Club", "Spade"]
var value = ["2", "3", "4", "5", "6", "7", "8", "9", "10", "Jack", "Queen", "K", "A"]
c = value + color
}
public static void main(String[] args) 
{
Card c1 = new card(9, "Heart")
Card c2 = new card("J", "Diamond")
IO.outputIn(c1.c);
IO.outputIn(c2.c);
}
}



