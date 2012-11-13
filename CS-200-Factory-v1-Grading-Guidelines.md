They are to have the simulation of the entire factory - what is called the "normative" scenario. This means that the agents are controlling the factory hardware - all the hardware - and the CSCI 200 code is animating the hardware.

## Managers
There are to be the 6 managers - acting as clients. The managers are:
<dl>
  <dt>Parts Manager</dt>
  <dd>The parts manager has no graphical display. They only create parts. Parts have a part number, part name, part description, and an image filename. Students do not have to upload images, the image files already exist in a directory. Only the image file name is entered by the parts manager. The parts manager is to be able to create parts, edit existing parts, and delete parts.</dd>

   <dt>Kit Manager</dt>
   <dd>The kit manager creates kits by assigning parts to a kit. Kits are to have from 4 to 8 parts. The parts that the kit manager can use come from the parts manager. When a new part is created by a parts manager, it should show up on the kit manager screen. The kit manager also has no graphics. The kit manager can create kits, edit existing kits, or delete kits.</dd>

    <dt>Factory Production Manager</dt>
    <dd>The factory production manager decides what the factory is to actually produce. They select a kit (created by the kit manager) and set how many of that kit are to be produced. Once this happens, the factory should begin producing that kit. The FPM does not have to wait for a set of kits to be finished, before they can set other kits to be made. The FPM can see the animation of the entire factory, as well. They can also see the pending production schedule - the kit currently being produced, and any others that are waiting to be produced.</dd>

    <dt>Gantry Robot Manager</dt>
    <dd>The GRM, for <code>v1</code>, is graphical only. The GRM can see the parts bins, the gantry robot, and the feeder bins. But that is all they are to see. They cannot control anything, they can just watch the animation.</dd>

     <dt>Lane Manager</dt>
     <dd>The LM, for <code>v1</code>, is graphical only. The LM can see the feeders (including the feeder bins), the lanes, the flash when a picture is taken, and the nests. They cannot control anything either.</dd>

     <dt>Kit Assembly Manager</dt>
     <dd>The KAM, for <code>v1</code>, is also graphical only. They can see the nests, the part robot, the kit robot, the conveyor where empty kits come from (and full kits are put back onto), the kitting station, and when a picture is taken at the kitting station. Like the LM and GRM, the KAM does not control anything for <code>v1</code>.</dd>
</dl>


## Server
They must also have a server application that contains the factory state. It will also have all the agents for CSCI 201, but there's no CSCI 200 points for that. The server will "talk" with all the six manager clients to connect them all together.


## Grading Scheme
`v1` is worth **40** points. That is 20 points for each individual and 20 points for the team.

The team points are divided as follows:
  + 2 points: parts manager
  + 2 points: kit manager
  + 5 points: factory production manager
  + 2 points: gantry robot manager
  + 2 points: lane manager
  + 2 points: kit assembly manager
  + 2 points: design document
  + 3 points: server application

I would suggest grading the entire factory project first. This will give you an idea as to whether they completed all the requirements, or not. If a team does not get all the manager and server points (18 total) as a team, then all the students cannot get 100% individual points.

The **individual** points come from having completed what they were assigned, and that it works correctly. The 20 points are to be divided as follows:
  + 14 points: The code they wrote works properly and correctly per the factory specifications.
  + 4 points: Design document for what they did matches their code and is a good design - meaning that someone could write the code from their design documentation
  + 2 points: Code comments. Their code is properly commented