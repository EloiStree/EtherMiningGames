## Good to know
Choose a color don't make you join a team.  
Each action give points and those points make you belong to a team.  
IF you action define you as red. It don't means that you can't set your cursor to green and defend green.  
More you defend green more you will belong to the green team.   


Good to know:
- Airdrop have big malus when attacking
- Troup in defense generate small amount of troup


?$ == the command is not implemented in the current game but I want to test it in future version.

## CMDs
$ is use to request the software to convert you text in commands for the game.
Abuse of it to make the game bug is automaticaly ban.


- [ ] $join 255 000 255 // Join the game with the color to 255 000 255 as rgb

- [ ]  $cursor 0.3 0.5 // move the cursor to 0.3 left2right 0.5 bot2top
- [ ]  $cursor valide 0.3 0.5 // move the cursor to 0.3 left2right 0.5 bot2top and find the valide pixel the nearest of it.
- [ ]  $cursor belgium // try to find the country "Belgium" to set the cursor on it
- [ ]  $cursor px 400 500 // move the cursor at 400 pixel left2right 500 pixel bot2top

- [ ]  $fullairdrop // use all your money in your wallet to drop troup at the location of your cursor
- [ ]  $airdrop 666 // drop 666 troup at the cursor location if you have the fund in your wallet
- [ ]  $airdrop 666 0.1 // drop 666 troup randomly at cursor location on 10% of the map width around cursor.

- [ ]  $defense 666 // put stationary trop at the cursor location. (Do airdrop if the cursor and the territory is not the same color) 


- [ ]  $cursorcolor 255 255 000 //Set the team color of your action to 255 255 000 


- [ ]  $nuke h  // Destroy all troup and defense of a big zone (very expensive cost)
- [ ]  $nuke atomic // destroy all troup and defense of a good zone ( expensive cost)
- [ ]  $nuke mini // destory all troup and 2/3 defense of a small zone ( affordable cost)

- [ ] $laserstrike // Chirugical attack that destroy all troupe and defense of only a pixel ( affordable cost)


//Regrowing is a double side weapon. It allows to build city that produce troup to the pixel owner. 
// N% of the city is destroy when switching color.

//Regrowing is the action of producing troup indirectly but more effectively. 
- [ ] $regrow troup 500 0.1  // Add a bonus for the equivalent of 500 troup in the next turn regrow on the region around the cursor  
- [ ] $regrow city  400 0.05 // invest 400 troup equivalent to build a city that produce troup




