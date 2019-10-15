# Array-5

## Problem1: Bind Robot in a Circle (https://leetcode.com/problems/robot-bounded-in-circle/)

Given a robot initially standing at (0, 0) and faceing north.  The robot can receive only three instructions:

"G": go straight 1 unit;

"L": turn 90 degrees to the left;

"R": turn 90 degress to the right.

The robot performs the instructions given in order, and repeats them forever.

Return true if and only if there exists a circle in the plane such that the robot never leaves the circle.

Example 1:

Input: "GGLLGG"

Output: true

Explanation: 

The robot moves from (0,0) to (0,2), turns 180 degrees, and then returns to (0,0).

When repeating these instructions, the robot remains in the circle of radius 2 centered at the origin.

Example 2:

Input: "GG"

Output: false

Explanation: 

The robot moves north indefinitely.

Example 3:

Input: "GL"

Output: true

Explanation: 

The robot moves from (0, 0) -> (0, 1) -> (-1, 1) -> (-1, 0) -> (0, 0) -> ...

## Problem2: Calculate Tax

 Write a program to calculate tax if Salary and Tax Brackets are given as list in the form [ [10000, .3],[20000, .2], [30000, .1], [None, .1]]. You don’t know in the beginning how many tax brackets are there. You have to test for all of them 
