# Boarding-simulator

A simulator for airplane boarding. It supports different boarding methods and airplane layouts.

Inspired by Vox - "The better way to board an airplane": 

[![Vox - The better way to board an airplane](https://img.youtube.com/vi/cMgarcFkXz4/0.jpg)](https://www.youtube.com/watch?v=cMgarcFkXz4)

## Usage
usage: ./boardSim \[numRuns\] \[numRows\] \[layout\] \[printPlane\]

numRuns - Number of runs to take the average of

numRows - Number of rows in the airplane

layout - one of "737", "747", "a380"
  
printPlane - 1 if you want the plane to be printed, 0 otherwise

## Icons

'-' a seat

'|' an aisle

'?' a person who has not yet decided what to do next

'S' a sitting person

'B' a person who is putting her/his bags away

'<' a person moving left

'>' a person moving right

'v' a person moving down

finally, a number indicates that there are that many people in the same square. This happes when some people have to stand up to let others sit down on their row.
