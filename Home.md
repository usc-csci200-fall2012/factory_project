## The Factory Project
The two classes, csci201 and csci200, will cooperate to design and build a manufacturing assembly cell. The csci201 team will do the backend, while the csci200 will do the GUI and animation. The teams will cooperate in the design of the API between the backend and frontend.

## The Operational Concepts Description
Please see [The Operation Concepts Description](wiki/Operational-Concepts-Description)

##Requirements
Please see [The Kitting Cell](wiki/The-Kitting-Cell)

## eXtreme Programming
You are to use the eXtreme programming methodology. Details of your meetings, schedule and tasks will be maintained online, with specific details to be determined.

## Git
Git is a distributed version control system for managing your code. Check the [Git Resource Wiki Page](wiki/Git-Resource) for more information on [Git](http://git-scm.com/).

## Deliverables
There will be six deliverables (due dates below):

1. A design for the `v.0` skeleton. This includes interaction diagrams, agent/backend design. The point of `v.0` is to get the teams off to a quick start and have some code working without worrying about the full integration.
1. `v.0`: A skeleton. This will be stored in the tags part of your repository as `KittingCell-v0`. Your skeleton will have 3 non-integrated parts:
  + The kit robot picking kits from the agv/conveyor, putting them on the stand, and the reverse.
  + The parts robot picking up parts from the nests and putting them in the kit—includes vision.
  + Parts dumped into bins and fed down the lanes.
1. A final design that includes both `v1` and `v2`. This includes interaction diagrams, agent/backend design (for csci201), frontend design (for csci200), and the `DoXXX()` API. The design is a living document for the life of the project. As design decisions change, this document should be updated. The design must handle the non-normative scenarios.
1. `v.1`: A working version of the normative scenario for the cell. This will be stored in the tags part of your repository as `KittingCell-v1`.
1. `v.2`: A second and full delivery of the cell with all the non-normative cases handled. This will be stored in the tags part of your repository as `KittingCell-v2`.
1. Final Presentations during the last week of classes.

<table>
    <tr>
        <th>Due Date</th>
        <th>Deliverable</th>
        <th>Notes</th>
    </tr>
    <tr>
        <td>10/28</td>
        <td>Factory Design</td>
        <td><a href="wiki/Factory-Design-Course-Notes">CS 200</a></td>
    </tr>
    <tr>
        <td>11/04</td>
        <td>Factory Skeleton v. 0</td>
        <td><a href="wiki/Factory-Skeleton-v.0-Course-Notes">CS 200</a></td>
    </tr>
    <tr>
        <td>11/18</td>
        <td>Factory v. 1</td>
        <td><a href="wiki/CS-200-Factory-v1-Grading-Guidelines">CS 200</a></td>
    </tr>
    <tr>
        <td>12/02</td>
        <td>Factory v. 2</td>
        <td></td>
    </tr>
    <tr>
        <td>12/3, 12/5</td>
        <td>Final Persentation</td>
        <td></td>
    </tr>
</table>

## Submission & Grading Notes
As issues come up after deliverables, the [submission notes](wiki/Submission-Notes) page will be updated. Teams are to periodically check this page and review it before submitting their deliverables.

### CS 200 Grading Notes
CS 200 students will receive their grading for all deliverables in the form of GitHub issues. As a team, your are to fix these issues and close them. You are to mention the issue number in the commit message fixing the problem and the SHA of that commit in the issue before closing it. This way, we can cross reference the history of it.

Any discussion on an issue with your TAs, graders or professor should be done through comments on the issue tracker **not via email**.
 
If you would like to discuss a specific issues with your TAs (as in a re-grade), you must keep the issue open and not close it. Then, present this issue to the TAs during lab time and they will be able to assist you. Unlike homework assignments, there is no specific TA:Team mapping for the design document. Any TA will be able to help you.