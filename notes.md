1. Since I was new to Javascript, trying to figure out what was going on with the source code took quite a while. I was expecting something visual that might help me, but opening the index.html file only shows a blank page (at least that's what I thought)

2. Looking at the task, an echo application would need the following components:

    i. Enable the notebox so that the user can actually click on the different notes (notebox#enable)

    ii. Start a timer for 2.5 seconds while the notebox has been enabled (timer or similar syntax in Javascript)
    
    iii. Stores the note and the time spent on each note in memory while the users interacts with the notebox within the 2.5 seconds (int for time, var for note)
    
    iv. Disables the noteboxes to prevent further input by the user beyond the 2.5 second timeframe (notebox#disable)
    
    v. Plays the sequence of notes that the user played.(notebox#play)

3. The unfamiliarity of Javascript structure and syntax has limited what I can do on the simon.js file that was provided, but if I was accepted as a developer for Launchpad, I will committ the time and effort to catch up on the Javascript language and contribute to the various projects in Launchpad.

4. Looking at the challenge task, I would implement a modified version of the algorithm for the echo application to run the Simon game in Javascript.

    i. Use a random function to select random notes from the four notes given (c,d,e,f) and save it in memory. The notebox buttons should be disabled as well (rand or similar syntax in Javascript, var for note, notebox#disable)
    
    ii. Plays the note that was randomly selected to the user (notebox#play)
    
    iii. Enables the notebox and records the notes that were clicked by the user (notebox#enable, var for note)
    
    iv. Checks the note played by the user with the note that was generated. If they match, generate another note using the random function and save the note in addition to the last note in the same variable (if else, var for note)
    
    v. If the notes do not match, reset the Simon game and restart.


