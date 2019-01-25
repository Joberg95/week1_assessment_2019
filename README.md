## WEEK 1 ASSESSMENT
<b>
In this repo i will go over some of the different types of data in ruby and how to store data in arrays.<b>

Below is a code example in irb on how to create a hash, put it into an array and then access a value of a specific hash. And in this case i wanted to know the value of car2's color.
``` irb
2.6.0 :001 > car1 = {wheels: 4, max_speed: 100, color
: "blue"}
 => {:wheels=>4, :max_speed=>100, :color=>"blue"} 
2.6.0 :002 > car2 = {wheels: 8, max_speed: 75, color:
 "red"}
 => {:wheels=>8, :max_speed=>75, :color=>"red"} 
2.6.0 :003 > cars = []
 => [] 
2.6.0 :004 > cars << car1
 => [{:wheels=>4, :max_speed=>100, :color=>"blue"}] 
2.6.0 :005 > cars << car2
 => [{:wheels=>4, :max_speed=>100, :color=>"blue"}, {:wheels=>8, :max_speed=>75, :color=>"red"}] 
2.6.0 :006 > car2[:color]
 => "red"  
 ```

