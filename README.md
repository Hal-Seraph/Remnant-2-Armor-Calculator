# Remnant II: Armor Calculator <a href="https://threeskimo.github.io/Remnant-2-Armor-Calculator/" target="_blank" ><img align="right" style="margin-top:10px;" src="https://img.shields.io/badge/Demo-238636?style=for-the-badge"></a>
A calculator that helps determine the highest armor value you can achieve at a specific weight in Remnant II. Calculations are performed in javascript.

>**NOTE:** This calculator currently only contains the Armor sets that are available at launch. If I'm still playing Remnant II at the time of any additional armor sets being released, I will update the calculator.

## Why?

If you are familiar with how Remnant II's armor system works, weight is directly related to your character’s Dodge and Stamina. Each armor has a certain weight number, and you will receive a stamina cost penalty if the total Weight value exceeds a certain threshold. Generally, you want to keep your character as light as possible without sacrificing your defense. The thresholds are as follows:

* ![#72c2dc](https://placehold.co/10x10/72c2dc/72c2dc.png) **Light:** <=25 – Fast Dodge. No Stamina Cost Penalty.
* ![#71b465](https://placehold.co/10x10/71b465/71b465.png) **Normal:** 26-50 – Normal Dodge. 25% Stamina Cost Penalty.
* ![#c9c96b](https://placehold.co/10x10/c9c96b/c9c96b.png) **Heavy:** 51-75 – Slow Dodge. 50% Stamina Cost Penalty.
* ![#f24a45](https://placehold.co/10x10/f24a45/f24a45.png) **Ultra:** >=76 – FLOP. 75% Stamina Cost Penalty.

This calculator determines the best armor pieces (head, body, legs, gloves) to use to receive the highest armor value possible at a given weight. The calculator does not take into account armor resistances such as bleed, fire, shock, etc. or rings/amulets that reduce your total weight, although this is easy to calculate on your own. (For example, if you wish to achieve "50" target weight, to be within the Normal Dodge threshold, and you are wearing the Twisted Idol, an amulet that reduces your weight by 15 and increases armor effectiveness by 30%, input a target weight of "65" (50+15). Then multiple the armor result by 1.3 to get your total armor value. I may add this functionality to the calculator later.)

## Usage
1. Download the `remnant-armor-calculator.html` file, which you can run locally on your machine.
2. Enter a "target weight" in the input field and click "Update". If you'd like to use a specific piece of armor, use the drop down menus.
3. The tool should show sets of armors (head, body, legs, gloves) that will get you the highest armor value possible for the weight specified.

## Changelog

* [[08-18-2023](https://github.com/threeskimo/Remnant-2-Armor-Calculator/commit/222a1cacdb8b93fbff207b248c148c32629f109c)] Added ability to lock-in armors, for you fashion conscious travelers out there. 😉
* [[10-29-2023]I have edited for new stats. Lab Gloves show expected new stats after change coming soon as stated by Tragic here: https://www.reddit.com/r/remnantgame/comments/17iiwnz/comment/k6unz8h/?utm_source=share&utm_medium=web2x&context=3

## Images
![Preview image](https://github.com/threeskimo/remnant-2-armor-weight-calculator/blob/main/preview.png?raw=true)
