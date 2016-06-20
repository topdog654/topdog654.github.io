---
title: flashpoint
layout: post
author: luke.john
permalink: /flashpoint/
source-id: 1SuGSSMzfdM1hWUCibZY5pHnLj-qjeLL0IxGKZr-FK5o
published: true
---
function onStart(  ) {

	globals.readyForNewGame = true;

	

}

function onShake(  ) {

	globals.readyForNewGame = false;

	if (___) {

		

		microbit.say("*");

		microbit.clear();

		Random.number(5000, 10000);

		microbit.clear();

		microbit.draw(Pattern("11111.11111.11111.11111.11111"));

		

	}

	

	

}

function onPressA(  ) {

	if (___) {

		

		microbit.on(0, 1);

		microbit.draw(Pattern("00100.01000.11111.01000.00100"));

		else {

			

			microbit.draw(Pattern("10001.01010.00100.01010.10001"));

			wait(1000);

			microbit.draw(Pattern("00100.00010.11111.00010.00100"));

			

		}

		

		globals.readyForNewGame = true;

		

	}

	

	

}

function onPressB(  ) {

	

}

