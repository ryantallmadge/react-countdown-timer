react-countdown-timer
=====================

A timer component for React that counts down to zero for a specified number of milliseconds.

 **props**
 
 `initialTimeRemaining: Number`
 The time remaining for the countdown (in ms).

`setClass: String (optional -- default: 'timer')`
Override the 'timer' class with a custom class name

 `interval: Number (optional -- default: 1000ms)`
 The time between timer ticks (in ms).

 `formatFunc(timeRemaining): Function (optional)`
 A function that formats the timeRemaining.

 `tickCallback(timeRemaining): Function (optional)`
 A function to call each tick.

 `completeCallback(): Function (optional)`
 A function to call when the countdown completes.
