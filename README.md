# CSAReverseNumber
CS AP A ReverseNumberLab

# Instructions  
Write a program that will take an integer and reverse it.  You must use a while loop and % to perform the reverse.

|Sample Data|Sample Output|
|---|---|
|234|234 reversed is 432|
|10000|10000 reversed is 1|
|111|111 reversed is 111|
|9005|9005 reversed is 5009|
|84645|84645 reversed is 54648|
|8547|8547 reversed is 7458|
|123456789|123456789 reversed is 987654321|

Algorithm Help
~~~
rev = 0
while(num > 0)
{
   rev = rev times 10 + right most digit of num 
   chop off the right most digit of num
}
~~~
