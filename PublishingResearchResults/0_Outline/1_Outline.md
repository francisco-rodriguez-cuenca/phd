# Outline - Closer Control of Loops with Dead Time

## Three central points of the paper

* It is difficult to stabilize process control loops that contain large amounts of dead-time.
* This novel method enables high accuracy in loops with high dead-time by reducing the time to recover from an upset to approximately the value of the system dead-time.
* It is theoretically impossible to reduce the correction time further.

## Summarize the paper in one sentence

The proposal of a novel method of obtaining high accuracy in a process control by using a minor feedback loop around the controller to prevent dead-time-excited oscillations.

## Try to describe the work in under one minute

1. State your problem and questions
   * It is difficult to stabilize process control loops that contain large amounts of dead-time.
   * We need a method that provides high accuracy in process control loops that contain large amounts of dead-time.
2. Relate your own work to previous work
   * It is difficult to stabilize loops containing high dead-time with the conventional proportional plus rate plus reset controllers method.
3. Show the overall significance. Identify an existing need.
   * Lots of systems have large amounts of dead-time: cold rolling mill, catalytic cracker...
4. Define the principal findings and results
   * A minor feedback loop around the controller prevents dead-timed oscillations
   * The minor feedback loop generates the difference between the system output without dead-time and the system output with dead time.
   * When this difference is introduced in negative feedback to the input of the controller, it allows the permissible gain to be adjusted a very high value, stabilizing the system.
   * This reduces the time to recover from an upset to approximately the value of the system dead-time.
   * It is theoretically impossible to reduce the time even further
5. Describe the conclusions and applications
   1. The loop proposed stabilizes process-control loops with dead-time
   2. This solution can be applied to the control of any system with high dead-time.

* Organize and group related ideas together
  * Done it by points
* Identify the references that apply to each of the key points
  * Applications: 1,2,3

