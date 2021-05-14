# Predicting poisonous and non poisonous mushroom
Building a model capable of predicting a mushroom is poisonous or non poisonous with very low generalization error. The Mushroom dataset was downloaded from Machine Learning UCI repository

Number of Instances: 8124

1. Number of Attributes: 22 (all nominally valued)

2. Attribute Information: (classes: edible=e, poisonous=p)
     1. cap-shape:                bell ,conical, convex, flat,
                                  knobbed ,sunken
                                  
     2. cap-surface:              fibrous, grooves, scaly, smooth

     3. cap-color:                brown, buff, cinnamon, gray, green,
                                  pink, purple, red, white, yellow
                                  
     4. bruises?:                 bruises, no

     5. odor:                     almond, anise, creosote, fishy, foul,
                                  musty , none , pungent, spicy
                                  
     6. gill-attachment:          attached, descending, free, notched
     
     7. gill-spacing:             close, crowded, distant
     
     8. gill-size:                broad, narrow
     
     9. gill-color:               black, brown, buff, chocolate, gray,
                                  green, orange, pink, purple, red,
                                  white, yellow
                                  
    10. stalk-shape:              enlarging, tapering
     
    11. stalk-root:               bulbous, club, cup, equal,
                                  rhizomorphs, rooted, missing=?
                                  
    12. stalk-surface-above-ring: fibrous, scaly, silky, smooth
     
    13. stalk-surface-below-ring: fibrous, scaly, silky, smooth
     
    14. stalk-color-above-ring:   brown, buff, cinnamon, gray, orange,
                                  pink, red, white, yellow
                                  
    15. stalk-color-below-ring:   brown, buff, cinnamon, gray, orange,
                                  pink, red, white, yellow
                                  
    16. veil-type:                partial, universal
     
    17 veil-color:               brown, orange, white, yellow
     
    18. ring-number:              none, one, two
     
    19. ring-type:                cobwebby, evanescent, flaring, large,
                                  none, pendant, sheathing, zone
                                  
    21. spore-print-color:        black, brown, buff, chocolate, green,
                                  orange, purple, white, yellow
                                  
    22. population:               abundant, clustered, numerous,
                                  scattered, several, solitary
                                  
    23. habitat:                  grasses, leaves, meadows, paths,
                                  urban, waste, woods

3. Missing Attribute Values: 2480 of them (denoted by "?"), all for
   attribute #11.

4. Class Distribution: 
    --    edible: 4208 (51.8%)
    -- poisonous: 3916 (48.2%)
    --     total: 8124 instances
