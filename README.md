icsy - I Can't Sleep Yet!
=========================

a silly alarm for people with not-so-silly deadlines

icsy is a simple alarm that deters its user from falling back asleep after
going off.


## Usage

1.  Set the amount of time you want to sleep.

2.  When that time is up, icsy will start the alarm.

3.  Press enter to shut the alarm off.  icsy will start asking you a few simple
    math questions to get you to wake up.

4.  If you answer any questions incorrectly and fall back asleep, a snooze
    alarm will go off later.

You can find detailed configuration instructions by invoking `icsy -h`.

You can change the alarm time, snooze time, number of questions asked, alarm
sound to play, and even specify a custom wakeup command.

icsy can be run from anywhere.  There's no real installation required.


## Sample Output

```
$ icsy -t 2 -s 5 -n2
setting alarm for 2 seconds
press enter when awake 
starting snooze timer for 5 seconds
are you __really__ awake?
what is 5-53? 0  
what is 82+20? 0
0/2 correct... try again
what is 34+90? 124
what is 28+47? 75
:) everything was correct
now get back to work!
```
