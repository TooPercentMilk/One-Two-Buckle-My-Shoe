Git Commands in Terminal

To download world file:
$ cd ~/Desktop/One-Two-Buckle-My-Shoe
$ git pull
$ cp ~/Desktop/One-Two-Buckle-My-Shoe/Penis_Palooza.wld ~/Library/Application\ Support/Terraria/Worlds

To upload world file:
$ cp ~/Library/Application\ Support/Terraria/Worlds/Penis_Palooza.wld ~/Desktop/One-Two-Buckle-My-Shoe
$ cd ~/Desktop/One-Two-Buckle-My-Shoe
$ git add ~/Library/Application\ Support/Terraria/Worlds/Penis_Palooza.wld
$ git commit -m "<your name>"
$ git push origin main
