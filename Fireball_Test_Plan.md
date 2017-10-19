<h1>Fireball Test Plan</h1>
<p><h2>Introduction :</h2> I am a student at Northwest Vista College. I am going to be making a test plan document using the Fireball design document. Fireball is a budget game for PS2. The player controls a ball of fire, and traverses a landscape made of blocks of different materials. As the player sets fire to these blocks, they grow hotter, and can set fire to more and more different types of blocks. The fireball the player controls can also rise up in height and the hotter the player gets, the higher they can jump in this fashion. On each field (level), the player has an ultimate goal of igniting the torch (brazier) and thus clearing the field – but the torch is generally positioned at a high point and out of reach. The player must use a combination of platform skills and dynamic environmental features (for instance, by burning the supports under the torch down to the ground) in order to clear the field. Simple, clean cut graphics and controls combine to give an easy to learn but engaging play experience. This is the final phase of the project, which includes the test plan and the implementation of the game. This test plan contains a comprehensive list of tests that will be performed along with a workflow of how the tests will be executed. </p>
<p><h3>Purpose :</h3> The purpose of the test plan is to gather all of the information needed to plan and control the test effort for this phase.</p>
<p>This Test Plan for the Fireball game supports the following objectives :</p>
    <ul>
        <li>Test Strategy: Guidelines that the test will be based on and descriptions of the process to set up a valid test.</li>
        <li>Execution Strategy: How the test will be executed and the process to identify and report bugs, and to fix and implement fixes</li>
        <li>Test Management: Handling the logistics of the test and all the events that come up during execution of a test.</li>
    </ul>
<p><h3>Scope :</h3> This document is intended to provide a test plan to test the Fireball game, which International Hobo developed. The test plan will consist of unit, integration, function, performance, and load testing. The testing techniques that will be performed include black box testing. Some test that were omitted in the test plan include: stress, smoke, regression, and compliance testing. A test plan workflow will be included along with milestones that have been set for the test plan phase.</p>
<p><h3>Document Overview :</h3> This document will go over the project in detail, user characteristics, general constrains, and then requirements entailed.</p>
<p><h2>Project Eplained :</h2></p>
<p><h4>Game Engine - </h4> The game engine should poll the blocks of the world at the fastest rate feasible without causing slowdown – blocks near to the player should be polled in as close to real time as possible, whilst blocks far from the player are lower priority. However, within an approximately ten second cycle, all blocks in the game world should be polled at least once to determine if they start any fires nearby. The game front end operates using the main game engine. The player moves around between objects (which are kept well spaced), and when near an object, text appears indicating what will happen if they burn that object. This saves developing a separate front end</p>
<p><h4>Menu Driver- </h4> The menu holds the audio tracks and reset field options which resets the field.</p>
<p><h4>Audio Driver - </h4> Displays the current track, the player can push left and right to change the track. Displayed on screen when the game is paused.</p>
<p><h4>Timer - </h4> Keeps track of elapsed time, burn time, and ignition times. Also gives the player a time limit for objectives to be completed.</p>
<p><h3>Project Functions :</h3></p>
<p><h3>User Characteristics :</h3> The users of this game will have to have a PlayStation 2 console. Although given current technologies, it can be emulated on several devices, most notably on pc.</p>
<p><h2>Requirements :</h2></p>
<p><h3>Game Engine :</h3></p>
<ul>
<li><p>testtesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttesttest</p></li>
</ul>
<p><h3>Menu Driver Requirements:</h3></p>
<p><h3>Audio Driver Requirements :</h3></p>
<p><h3>Timer Requirements :</h3></p>
<p><h3>Scope :</h3></p>
<p><h2>Assumptions :</h2></p> 
