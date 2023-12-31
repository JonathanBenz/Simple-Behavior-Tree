# Simple-Behavior-Tree

This was a personal project I did when learning about video game AI. 

I implemented a behavior tree made up of a selector root node that would choose a priority from either a melee sequence node, a ranged attack sequence node, or a wander leaf node. 

In the melee sequence node, the AI would run a condition node to see if it was within a melee attack range. If it was, then it would run a pursue node to run up to the target, then it would run a melee attack node to actually strike at the target. 

In the ranged attack sequence node, the AI would run a condition node to see if the target was outside of melee attack range, but within ranged attack range. If it was, then it would run a ranged attack node where it would shoot a projectile at the target's direction. 

In the wander node, it would randomly wander around the level if the target was outside of the ranged attack range. 
