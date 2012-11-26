## Non Normative Scenarios for Kitting Cell

Non-Normatives scenarios all start from a non-normative vision result. There are 3 such results:
  1. Inspection of kit fails
  1. Inspecting a nest returns "parts missing"
  1. Inspecting a nest returns "no good part found"  (formally call "bad parts" in the requirements)

The first thing to do is figure out what could have happened, then determine tactics for each case we are to handle, then come up with interaction diagrams, and finally a design. 

### Inspection of Kit Fails
What could be wrong?
  1. Parts could be missing from the kit (parts robot could have dropped the part).
  1. Parts are in the wrong place.
  1. Camera could have failed.
  1. other?

We will only worry about case 1. In the original specification it says to dump the kit on the floor if the picture fails. We will use different tactics as follows:
  + Move the kit from the inspection position back to a kitting position. [You must make sure you haven't put an empty kit onto the position from which the bad kit came.]
  + Tell the parts robot about the configuration of the bad kit.

You will have a GUI titled `Bad Kit - Non normative` that will have kit configuration information on it. The user can select the kit positions that will be `empty`. On hitting the `GO` button, the animation will "transform" the next inspected kit to look like the configuration, and send the vision result `BadKit(config)` to the agent expecting the vision result.


### Inspecting a Nest Returns "Parts Missing"
What could be wrong?
  1. Nothing, just wait a little longer.  This may be the first time parts are coming down the lane and your estimation may be wrong.
  1. Lane is jammed.
  1. The lane is not turned on.
  1. The feeder is off/broken
  1. Gantry has screwed up.
  1. Your feeder algorithm for keeping parts in two lanes did not changeover fast enough.
  1. other?

We will worry about cases (1), (2), and (6).  Tactics for (1) are simple. Just wait a little longer and see if parts have arrived.  If that fails, maybe the problem is (2).  In that case, hi-speed (turn up the amplitude of the lanes). If that fails, consider that (6) is your problem. Then adjust the parameter of your feeder algorithm for changing parts over from one lane to another.

You will have a GUI titled `Missing Parts in Nest - Non normative`. You can figure out what needs to be in the GUI. I would expect the animation result to be something like `PartsMissingInNest()`.


### Inspecting a nest returns "no good part found"  
What could be wrong?
  1. All the parts are bad.
  1. The parts have piled on each other and can't be properly identified by vision.
  1. Camera error.
  1. Robot in the way.
  1. Parts are not yet stable.
  1. other?

In cases (1) and (2) we'll just dump the nest after stopping the lanes. Case (5) should be handled by waiting a little while, hoping the nest stabilizes.  Case (4) is really an error of the parts robot agent--this is actually in the specifications.  Let's treat it first like case (5).

You will have a GUI titled `No Good Parts in Nest - Non normative`. You can figure out what needs to be in the GUI. I would expect the animation result to be something like `NoGoodPartsInNest ()`.
