# BlindFire

**Automated Statistically Likely for your User Enumeration.**

**NOT** Windows Compatible

This was a repetitive Perimeter process of identifying the email schema, downloading the correct file, and editing. The correct file can now be selected and modified from a single tool!

https://github.com/insidetrust/statistically-likely-usernames

## Installation
```
$ go mod tidy
$ go build
$ ./BlindFire
```

## Execute From Anywhere
```mv BlindFire /usr/local/bin```


# Example Usage
```
$ ./BlindFire  
.______    __       __  .__   __.  _______   _______  __  .______       _______ 
|   _  \  |  |     |  | |  \ |  | |       \ |   ____||  | |   _  \     |   ____|
|  |_)  | |  |     |  | |   \|  | |  .--.  ||  |__   |  | |  |_)  |    |  |__   
|   _  <  |  |     |  | |  . `  | |  |  |  ||   __|  |  | |      /     |   __|  
|  |_)  | |  `----.|  | |  |\   | |  '--'  ||  |     |  | |  |\  \----.|  |____ 
|______/  |_______||__| |__| \__| |_______/ |__|     |__| | _| `._____||_______|
                                                                                       
                                                   @AchocolatechipPancake

Select Statistically Likely Format:
  1. jjs
  2. jjsmith
  3. john.smith
  4. john
  5. johnjs
  6. johns
  7. johnsmith
  8. jsmith
  9. jsmith2
  10. places
  11. service-accounts
  12. smith
  13. smithj
  14. smithj2
  15. smithjj
>> 3
Download saved to john.smith.txt
File exists
Enter Domain to Append:
>> domain.com

File Is Ready For User Enumeration
```

## Results
```$ head john.smith.txt```
```
john.smith@domain.com
david.smith@domain.com
michael.smith@domain.com
chris.smith@domain.com
mike.smith@domain.com
arun.kumar@domain.com
james.smith@domain.com
amit.kumar@domain.com
imran.khan@domain.com
jason.smith@domain.com
```
