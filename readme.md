# Git Commands in Terminal

## To clone repo onto your local machine:
$ cd ~/Desktop
$ git clone https://github.com/TooPercentMilk/One-Two-Buckle-My-Shoe.git

## To download world file:
$ cd ~/Desktop/One-Two-Buckle-My-Shoe<br>
$ git pull<br>
$ cp ~/Desktop/One-Two-Buckle-My-Shoe/Penis_Palooza.wld ~/Library/Application\ Support/Terraria/Worlds

## To upload world file:
$ cp ~/Library/Application\ Support/Terraria/Worlds/Penis_Palooza.wld ~/Desktop/One-Two-Buckle-My-Shoe<br>
$ cd ~/Desktop/One-Two-Buckle-My-Shoe<br>
$ git add ~/Library/Application\ Support/Terraria/Worlds/Penis_Palooza.wld<br>
$ git commit -m "\<your name\>"<br>
$ git push origin main<br>
