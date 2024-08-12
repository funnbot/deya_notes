# Context
Entomologist that lives in the village wants to expand their collection of live specimens and requests help from the #PC in exchange for bugs the entomologist will give varying sums of money or even prizes to entice the player to continue catching rather than just for the sake of it. Bugs if duplicates can also be sold for gold furthering #PC wealth
## Hypothesis
The impact of this feature will lead to hopefully some sort of bug exhibit where the #PC can view the spoils of their work anytime with a cute detail about the bug. #PC will also receive treats to keep them interested in getting new bugs regardless if they do or don’t care about the exhibit as a final product.
## Measuring success
Uh hopefully whenever the #PC net collides with a bug on screen it will result in a catch, and as for its popularity? I guess? Animal crossing and Dinkum both feature a large museum and bug collecting mechanic which has been loved by players for years so I think people will like it.
Write down how you are going to test that this feature works. What metrics are you looking out for (if you’re using analytics)? What behaviour are you expecting (if you’re doing playtesting)?
# Design
#PC can carry a net in their inventory at all times if they wish and will be pressing the interact button to swing their net to catch bugs in front of them, 
## Summary
if #PC just clicks interact with net they will swing at regular height, but if they hold interact the #PC will crouch and hit the ground catching ground bugs instead of airborne ones, maybe we could even crouch walk with the net?

Write down a summary of how the feature works. Include images or sketches if you have any.
## User journey

 .   P <— net
 O/l   <— #PC   db  <— bug
 /l
  ^
## Flow
#PC gets request for bug from entomologist-> #PC acquires net-> #PC promised reward for bug-> #PC find bug-> #PC catch bug-> #PC delivers bug to entomologist-> #PC receives reward-> repeat
## Values
Bugs get you both rewards from the entomologist as well as money if you sell them
## Edge cases
Maybe a floor catching mechanic like I explained earlier but it’s not necessary
# Research and testing
I make bug asset, I make pc asset, I make net asset, bean code bug movement depending on bug, bean program pc movement and actions with net, bean program that when net interact with bug , bug go in #PC pocket.

