---
title: Copy of coding proof
layout: post
author: luke.john
permalink: /copy-of-coding-proof/
source-id: 1ngw4Z_KVHRo2zVNIm_ij7QyiwXnOizgbJrWrLlOiKEI
published: true
---
/ When the BBC micro:bit runs.

function onShake(  ) {

	microbit.say(Random.number(1, 6));

	

}

// When the BBC micro:bit runs.

function onStart(  ) {

	while (true) {

		

		if (microbit.tiltY == 2) {

			

			microbit.draw(Pattern("01010.01010.00000.00000.11111"));

			

		}

		

		if (microbit.tiltY == 2) {

			

			microbit.draw(Pattern("01010.01010.00000.01110.10001"));

			

		}

		

		if (microbit.tiltY > 2) {

			

			microbit.draw(Pattern("01010.01010.00000.10001.01110"));

			

		}

		

		

	}

	

	

}

// When the BBC micro:bit runs.

function onStart(  ) {

	if (globals.readyForNewGame == true) {

		

		

	}

	

	

}

function onShake(  ) {

	if (globals.readyForNewGame == false) {

		

		microbit.say("*");

		microbit.clear();

		wait(Random.number(5000, 10000));

		

	}

	

	microbit.draw(Pattern("11111.11111.11111.11111.11111"));

	microbit.draw(Pattern("00100.01110.10101.00100.00100"));

	

}

function onPressA(  ) {

	if (___) {

		

		microbit.on(0, 1);

		microbit.draw(Pattern("00100.01000.11111.01000.00100"));

		else {

			

			microbit.draw(Pattern("10001.01010.00100.01010.10001"));

			wait(1000);

			microbit.draw(Pattern("00100.00010.11111.00010.00100"));

			if (globals.readyForNewGame == true) {

				

				

			}

			

// When the BBC micro:bit runs.

function onStart(  ) {

	globals.readyForNewGame = true;

	

}

function onShake(  ) {

	if (globals.readyForNewGame) {

		

		globals.readyForNewGame = false;

		microbit.say("*");

		microbit.clear();

		wait(Random.number(5000, 10000));

		microbit.draw(Pattern("11111.11111.11111.11111.11111"));

		

	}

	

	

}

function onPressA(  ) {

	if (microbit.isOn(0, 1)) {

		

		microbit.draw(Pattern("00100.01000.11111.01000.00100"));

		

	}

	

	else {

		

When the BBC micro:bit runs.

function onStart(  ) {

	/* create variables to keep track of the:

	   the player's score, called score (should start at 1000)

	   the player's x-position, called posX (should start at 0)

	   the player's y-position, called posY (should start at 4)

	   the apple's x-position, called appleX (should start at 4)

	   the apple's y-position, called appleY (should start at 3)

	   the current level of the game, called level (should start at 0)

	   */

	// create a while loop which checks whether the current level of the game is less than 10

	while (globals.level < 10) {

		

		// make the player's dot flash by turning it on, off and on again (with small pauses inbetween)

		// (remember the x and y coordinate of the player's dot is stored in posX and posY

		// and you can turn a single LED off by using microbit.on and microbit.off!)

		// display the apple on the screen (remember the apple's position is stored in appleX and appleY)

		/* create an if chunk that checks whether the player's X position (stored in posX)

		   is equal to the apple's X position (appleX) and the same for their Y positions.

		   You can check if two things are equal inside a condition by using '=='

		   */

		if (globals.posX == globals.appleX) {

			

			// if the condition is true, that means the player has collected the apple,

			// so draw a happy face on the screen for a short amount of time (e.g., 300ms)

			// increase the game level by one

			// set the apple's x- and y-position to a random number between 0 and 4

			// clear the screen

			

		}

		

		/* create an if chunk to see if the micro:bit is being tilted to the right

		   AND that the player's dot is at x-position 1 or more (i.e., not at the edge)

		   */

		if (globals.posX <= 1) {

			

			// turn off the player's dot

			// update the player dot's x-position to be 1 less

			

		}

		

		/* create an if chunk to see if the micro:bit is being tilted to the left

		   AND that the player's dot is at x-position 3 or less (i.e., not at the edge)

		   */

		if (globals.posX < 3) {

			

			// turn off the player's dot

			// update the player dot's x-position to be 1 more

			

		}

		

		/* create an if chunk to see if the micro:bit is being tilted down

		   AND that the player's dot is at y-position 1 or more (i.e., not at the edge)

		   */

		if (globals.posY > 1) {

			

			// turn off the player's dot

			// update the player dot's y-position to be 1 less

			

		}

		

		/* create an if chunk to see if the micro:bit is being tilted up

		   AND that the player's dot is at y-position 3 or less (i.e., not at the edge)

		   */

		if (globals.posY < 3) {

			

			// turn off the player's dot

			// update the player dot's y-position to be 1 more

			

		}

		

		// at the end of the loop, decrease the player's score by 1

		

	}

	

	// out of the loop so the game is over! display the player's score to the screen

	

}

