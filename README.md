# CPSC474-Parallel and Distributed Computing-Project-1
## Project 1: Lamport Clock

The Lamport Logical clock determines the timelines of asynchronous processes in a distributed system.
Timelines are generated sequentially until a receive request that is generated from another process is encountered, in which case,
the clock manager determines if the current process' current time is greater or less than the time the send request was sent,
and applies the timeline accordingly.

There is also an instruction generation tool from a valid lamport clock timeline that generates instructions from the numerical
lamport clock timeline.


## Group members:
Michael Moon m-moon@csu.fullerton.edu

## To run:
Download the executable .jar file present in the Github Repository titled MoonMichaelLamportClock.jar located at
https://github.com/CSUF-CPSC-Bein-FA21/project-1-servers-michael-moon.git
Open with JDK/JRE | Compiled in Java ver 17, compatible with Java SE-16.
