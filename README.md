# Ether Mining Games
This repository is the welcome page of an experiment.
Using Ethereum and the mining of it as a source of game mechanics.   
  
Find us on [Discord](https://eloistree.page.link/discordofethermine  )


## What EMG is about ?

The concept is simple.  
To have Ether you need money + mastercard + verified identity.  

But... I don't have money and mastercard.   

So I tried mining...   
But mining take 400 days for 0.1 Ether (200€+) before you can collect the Ether.
So the equation is simple. For 400 people it take 1 days to make 200€+

But how do we split the money ?  
But playing of course :)  

The game(s) designing here are build to involve skills and team play.

Fight for your team and try to be the best of one category of your team in aim to claim the mined Ether.

As soon as the mining pool is above 0.1-1 Ethereum + Winning Condition of the current game, the game is stop.

When the game stop:   
- 60% Go to the winner team  
  - The 60% are split between game categories linked to the team
- 40 % go to the dev team and infrastructure cost
  -  The game stop and the top 1 team receive 60% split through 5 categories. and the developer of the game receive the 39% ( 1% go to Etherum.org ).

Example:

A game is win at 0.4 ETH by the red team.
- 0.24 Eth go the winner team
 - 0,048 Best defenser of the team
 - 0,048 Best Attacker of the team
 - 0,048 Best Populator of the team
 - 0,048 Best Massive Destructor of the team
 - 0,048 Best Air Dropper of the team
- 0.16 Eth go the dev
 - 0,053 developpers
 - 0,053 artists
 - 0,053 sound designers

(*This is just an example to give you the idea)


### What about Pay-to-win ?  

My politics on that is Pay-to-entertain.   

In the worst case scenario, someone can pay maximum 60% of the ETh mined before losing.   
And it does not guaranty his victory.     

Payement/Donation is part of the game but are design to entertain/disrupte other players and not to win.    

Note that every donation and payment are part of the end game reward with the same rules 60%/40%.  
So more people pay to disrupte the game, more the reward is hight.    


### What about Farmer and Streamer

As soon as we can, we will add to the game some highlight of people with hight mining power. 
They will be highlighted to give other players the ability to make cohalition against them.

Farmer and streamer are 100% welcome.
But we need to be fair to the casual player that only own one computer:
As the aim of this game is to help people without access to ether to win ether.

PS: Don't forget that a miner is also more money to win and quicker end game for everybody.

### What about cheater
No game is protected against hacker and cheater... 
- The game is hosted localy -> Low probability
- There is only one lobby -> Ping and admin and we will ban/fix as soon as possible.
- The game is save every minute on a Git repository -> We can pause the game or restore if cheat is detected and 100% verify
- 
 


## Important  Link

Discord server: https://eloistree.page.link/discordofethermine  
Wiki & welcome page: https://eloistree.page.link/ethermine  
Where to mine: https://ethermine.org/miners/60F6A0Dc848eD1D0a27dE73630eFdF46A6a11039/dashboard  
Ehterieum interaction Wallet:[60F6A0Dc848eD1D0a27dE73630eFdF46A6a11039](https://etherscan.io/address/0x60F6A0Dc848eD1D0a27dE73630eFdF46A6a11039)  



## How to play ?

### Chat

When you see that the game live on Twitch, or others, you can use the tchat to interact with the game. 

For example:  
- 'hello 255 000 000' = join the game with my the Color Red by default
- 'cursor 0.5 0.5 = the next action will be apply at 50%  from left to right on the map and 50% from bot to top.
- 'airdrop 600 =  Deplay 600 troups on the pixel of the cursor
- 'nuke mini" =  request to drop a nuke at the cursor (only apply if you have the fund )  
- ... 

When you want to make serveral in one time, you can do it like this:
- 'cursor 0.1 0.1 > 5000 > fullairdrop > 100000 > cursor 0.7 0.5 > fullairdrop'

## Mining Ethereum

By default each player identify in the game received ressources when active and when afk.
This ressource are just here to allow anyone to be able to play a bit for the fun of participating.

If you want to be an active player, you need to mine ethereum on the wallet address of the game.

When a game is online, you can mine at any time of the day.
A software on the computer is tracking 24h/24 7j/7 who is mining on the ethermine address.
https://ethermine.org/miners/60F6A0Dc848eD1D0a27dE73630eFdF46A6a11039/dashboard  

You can find information on how to mine on ethermine here:
https://ethermine.org/start
(Will do a more complet tutorial later)

When mining, you need to specify for who: 
- 60F6...1039.twitchyourusername
- 60F6...1039.discordyourusername
- 60F6...1039.facebookyourusername



For example, I am using [LolMiner](https://github.com/Lolliedieb/lolMiner-releases/releases)

```
@echo off
setlocal enableDelayedExpansion
set "POOL=eu1.ethermine.org:4444"
set "WALLET=60F6A0Dc848eD1D0a27dE73630eFdF46A6a11039.twitcheloistree"										
lolMiner.exe --algo ETHASH --pool !POOL! --user !WALLET! --4g-alloc-size 4024 --keepfree 8 
timeout 10
```
(PS don't stress if you name don't appear on Ethereum directly. It takes 2-8 minutes before we can access them.)
(As soon as it is visible on Ethermine, we can affect your work to the game) 







Welcome to you 
