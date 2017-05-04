The topic for CS5103 Project II is an elevator control system.
I wrote the code using Nusmv format. Other two members do the verification and report.

Six parts are included:
1.InsideButton(inreset_cmd)--inside the elevator, to floor 1-3. 
  {pressed,unpressed}
2.OutsideButton(outreset_cmd)--outside the elevator on each floor of the building, to floor 1-3.
  {pressed,unpressed}
3.DoorButtons(doorreset_cmd)--to open or close the door or the cabin, no matter inside or outside the cabin.   {pressed,unpressed}
4.Cabin(move_cmd)--status of cabin. 
  {floor,direction}
5.Door(door_cmd)--can be open or closed and receives door command.
  {open,closed,light}
6.CONTROLLER--inside controller system, there are 5 command for each item mentioned above.
