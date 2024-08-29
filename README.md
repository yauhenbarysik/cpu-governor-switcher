# Description
Simple bash script for changing ***CPU frequency scaling governor*** for better performance and/or battery life. 
***</br>Very useful for music production, streaming, gaming, etc.***

# Usage
Script have **2 modes** - ***WITH*** and ***WITHOUT*** argument. The are the same with one little different - you can parse argument directly to avoid argument request. See ***Examples*** for more refference.

# Examples
WITHOUT direct argument parsing:

> **$#./cpu-governor** 
></br>Select CPU governor mode:
></br>0 - Performance
></br>1 - Poversave
></br>0
></br>[sudo] password for user: 
></br>performance
></br>INFO: Your CPU governor is set to performance

</br>WITH direct argument parsing:

> **$# ./cpu-governor 0**
></br>performance
></br>INFO: Your CPU governor is set to performance
