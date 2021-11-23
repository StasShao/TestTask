Firstly you are need to see in inspector some prefereces:
____________________________________________________________
Create Tags :
(Red , Blue , Yellow , Green , Purpur , Light_blue , Obst , Cristall , Eat_zone ,
Tail, Wall, Red_check ,Purpur_check, Green_check,
Blue_check , Light_blue_check, Yellow_check, Faver);
__________________________________________________

Create Layers:
(Player, Wall , Tails , Eat , Eat_zone);
___________________________________________________
Open Project Settings:
(Desable collisions in Physics)
1 - Eat_zone collision just with Eat;
2 - Player collision with: Default , Wall , Eat;
3 - Tails need desable collision with: Player;
____________________________________________________
 Add layers & tags:
1 - Player - add layer Player;
2 - Tails to all element in hierarchy and in prefabs add layer Tails & add tag Tail;
3 - add tags to check_points the tag corresponding to the name;
4 - add tag Wall to walls;
________________________________________________________