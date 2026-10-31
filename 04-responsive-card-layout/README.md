# 03 - Responsive Card Layout

## Concepts practiced
*CSS Grid
*Responsive layout
*Positioning

## Challenges
-Figuring out the root for each media query

## Solutions
-I made research and found out that to figure out our root font size we just scale up/down pixel by pixel
-So to the calculations for the mobile we scalled down to 7px thats 7/16 (16 is the default font size for root
) * 100 equals 43.75% for our mobile
-BUT when we input sizes in the mobile media query we just use our CSS Baseline which is 10px rather than manualy 
adjusting everything as it will automatically scale the elements down

## What I learned
-Calculating HTML roots for each media query

## Next improvements
-Better responsiveness to other screen sizes such as some tablet views may have a viewport of a small destop laptop rather than a mobile screen viewport responsive design