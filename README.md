# Elivator-CCA
Algorithm for elivator CC
Elivator CC 
(Start)
Read and Initialise up(op),up-button(ip),up-destination(op)
UP FLOW 
If (up=up-button) then we need to move the lift in upwards direction and we are confirming that we have presses up button
If(up-button<up-destination) we need to perform tasks such that lift moves up wards for the given up-destination
Read and initialize the level sensor value say s and also consider upd,up1 as op
Take upd=up-destination- s
Take up1= s+upd 
Next we have to run the motor in clockwise direction in such a way that up-destination=up1
If (up-destination =up 1) then motor off and also we have reached our destination
Make sure that  (down -destination = up-dest) this will be helpful for further calculation
KEY UP FLOW  
Read and Initialise key-button(ip),key-destination(op)
If (key button <key destination) then we need to move the lift in upwards direction and we are confirming that we have presses up button and also we need to perform tasks such that lift moves up wards for the given key-destination
Read and initialize the level sensor value say s and also consider kd,kup1 as op
Take kd=key destination- s
Take kup1= s+kd 
Next we have to run the motor in clockwise direction in such a way that key-up destination=kup1
If (key-up destination=kup1 ) then motor off and also we have reached our destination
Make sure that  we need to store the values of up dest,down dest ,key- updest,key – down dest values which can be used for further calculation
KEY DOWN FLOW  
Read and Initialise key-button(ip),key-destination(op)
If (key button > key down destination) then we need to move the lift in downwards direction and we are confirming that we have presses up button and also we need to perform tasks such that lift moves downwards for the given key-destination
Read and initialize the level sensor value say s and also consider kdo,kdn 1 as op
Take kdo= s -key destination
Take kdn1= s-kd 
Next we have to run the motor in clockwise direction in such a way that key-down destination=kdn1
If (key-down destination=kdn1 ) then motor off and also we have reached our destination
Make sure that  we need to store the values of up dest,down dest ,key- updest,key – down dest values which can be used for further calculation
DOWN FLOW 
Read and Initialise down(op),down-button(ip),down-destination(op)
If (down=down-button) then we need to move the lift in down wards direction and we are confirming that we have presses down button
If(down-button > down -destination) we need to perform tasks such that lift moves down wards for the given down-destination
Read and initialize the level sensor value say s and also consider dd,dw1 as op
Take dd= s- down dest
Take dw1= s - dd
Next we have to run the motor in anti clockwise direction in such a way that down-destination=dw1
If (down-destination =dw 1) then motor off and also we have reached our destination
Make sure that  (up -destination = down-dest) this will be helpful for further calculation
(Stop)
Here 
i/p or ip means input
o/p or op means output
dest means destination







