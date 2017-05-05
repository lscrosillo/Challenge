A.	What is your design and implementation?
My main class name is Challenge1. I create the Randomizer class how created a queue of 100 integer numbers who are going to be the 
initial input for the process (I decided to use 100 for my queue but this value may change for others examples). Then we create an object
of the class Prime and run de method RunPrime who recieved Queue<Integer> and return a Queue<Value> (Value implements the class
Comparable, I override the methods compareTo and toString), The method RunPride reads all the numbers in the queue one by one, if the
reading number is 1 I can concider that the number is prime if not I check if the number is divisible from 2 to the square root of
the number one by one if the number was divisible by any number then is not a prime I use the operator mod to do this, I also use a 
boolean flag if i put true it means is prime if it's false then is not prime; at the end I create a new Object of the class Value 
with the number and the result(Prime or not)  and add this value to the final queue. After that I just print the values taking out
the comas to have a better view.


B. Output Example
Values
[Number=4042550 Is Prime=false
 Number=19166634 Is Prime=false
 Number=72598600 Is Prime=false
 Number=104022057 Is Prime=false
 Number=69136692 Is Prime=false
 Number=306199308 Is Prime=false
 Number=304633820 Is Prime=false
 Number=248683433 Is Prime=true
 Number=157133180 Is Prime=false
 Number=71058165 Is Prime=false
 Number=115126951 Is Prime=false
 Number=390833947 Is Prime=false
 Number=543257716 Is Prime=false
 Number=360944843 Is Prime=false
 Number=525205588 Is Prime=false
 Number=817874582 Is Prime=false
 Number=627294018 Is Prime=false
 Number=821957125 Is Prime=false
 Number=377887307 Is Prime=false
 Number=130206914 Is Prime=false
 Number=124876689 Is Prime=false
 Number=472388161 Is Prime=false
 Number=650057841 Is Prime=false
 Number=671733158 Is Prime=false
 Number=1126416617 Is Prime=false
 Number=752820372 Is Prime=false
 Number=750139338 Is Prime=false
 Number=1288202221 Is Prime=false
 Number=642366575 Is Prime=false
 Number=602001328 Is Prime=false
 Number=1282897680 Is Prime=false
 Number=1638844302 Is Prime=false
 Number=1148589883 Is Prime=false
 Number=978652008 Is Prime=false
 Number=1040409175 Is Prime=false
 Number=844871659 Is Prime=false
 Number=1145764196 Is Prime=false
 Number=909902148 Is Prime=false
 Number=812353753 Is Prime=true
 Number=488765886 Is Prime=false
 Number=174437547 Is Prime=false
 Number=445532394 Is Prime=false
 Number=593493451 Is Prime=false
 Number=723679205 Is Prime=false
 Number=696445511 Is Prime=false
 Number=755867064 Is Prime=false
 Number=1061316868 Is Prime=false
 Number=1000001685 Is Prime=false
 Number=1166442579 Is Prime=false
 Number=1296699985 Is Prime=false
 Number=1477983075 Is Prime=false
 Number=1136599464 Is Prime=false
 Number=1064636068 Is Prime=false
 Number=1595262827 Is Prime=false
 Number=984655590 Is Prime=false
 Number=1618527374 Is Prime=false
 Number=1436207617 Is Prime=false
 Number=1237041884 Is Prime=false
 Number=692133719 Is Prime=false
 Number=2107059879 Is Prime=false
 Number=629452067 Is Prime=false
 Number=1736618535 Is Prime=false
 Number=1375588129 Is Prime=false
 Number=2108637922 Is Prime=false
 Number=1739674077 Is Prime=false
 Number=2055709539 Is Prime=false
 Number=1152894851 Is Prime=true
 Number=1779000386 Is Prime=false
 Number=1986770272 Is Prime=false
 Number=1478742726 Is Prime=false
 Number=1494780785 Is Prime=false
 Number=1909433304 Is Prime=false
 Number=1110199416 Is Prime=false
 Number=2117371111 Is Prime=false
 Number=1842027716 Is Prime=false
 Number=1119686615 Is Prime=false
 Number=1567116084 Is Prime=false
 Number=2063722189 Is Prime=false
 Number=2127050757 Is Prime=false
 Number=1436600552 Is Prime=false
 Number=513566900 Is Prime=false
 Number=1734388923 Is Prime=false
 Number=379903106 Is Prime=false
 Number=1854911256 Is Prime=false
 Number=1340648289 Is Prime=false
 Number=1203354672 Is Prime=false
 Number=1025016278 Is Prime=false
 Number=1779593883 Is Prime=false
 Number=778772972 Is Prime=false
 Number=872065514 Is Prime=false
 Number=723081400 Is Prime=false
 Number=1737736406 Is Prime=false
 Number=1204502252 Is Prime=false
 Number=1386220793 Is Prime=false
 Number=1166498191 Is Prime=true
 Number=2076068425 Is Prime=false
 Number=1795605890 Is Prime=false
 Number=1871981373 Is Prime=false
 Number=1857254106 Is Prime=false
 Number=1567087175 Is Prime=false
]

C. Further work – if you have all the time in the world how would you implement
I wont put a limit number i will ask the user to choose how many numbers wants or maybe when he press a key the process ends.
I would take the branches out in the final result.

