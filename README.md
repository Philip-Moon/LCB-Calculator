# LCB-Calculator
https://philip-moon.github.io/LCB-Calculator

## Introduction
It is a calculator for limbus company player.

It can calculate winning percentage of clash and expected value of damage.

You can input some values of two characters who are going to clash each other.
 * Resistance	: Increase or decrease damage in proportion to the value. (min = 0)
 * Skill Power : Base power of the skill.
 * Coin Power	: Icreases or decrease power by the value per the number of heads of coins.
 * Coin Number : Number of coins which the skill has. (min = 0)
 * Sanity : Increase or decrease probability 1% per the value. (min = -45, max = 45)
 * Power Adjustment : Increase or decrease the final power by the value while clash. (Doesn't affect damage)

If you input all value and press confirm button, it will show you the value rounded to two decimal place.

## Notice
 * if the power calculated by rolling coins is less than zero, it changes the value to zero.
 * if both two characters can't beat each other, then it makes winning percentage 50% and makes all damage zero.
