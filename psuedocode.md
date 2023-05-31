# Instructions on Making a Bottle for a Baby

## About

-When baby cries it's usually time for a bottle
-Bottles are hand mixed by the parents
-Bottles use precise measurements
-Most formula measurements are universal

## Init: Set Variables for Process

formula = Similac Advance
-Baby Formula Being Used in Example

water = Purified or Distilled Water

scoop = Measuring Tool
-Tool used to Measure Formula **Provided in Formula Can**

bottle = Dr. Brown Infant Bottle
-Bottle Used in Example

lid = Lid for Bottle
-Used to Close Bottle

nipple = Bottle Nipple
-Nipple for Baby to Eat Out of

## Mixing Variables

Ounces = Amount of Water in Bottle
-Marked on the side of bottle

measure = measurement
-One Scoop for every 2 Ounces

## Property Variables

smooth = Mixed evenly with no clumps of formula

## Array

mixAll[
    bottle, water, formula
]

## Start:

set (var)(Move Var to starting location)
-Repeat for all Variables 

IF ounces < 4
    ADD 1 ounce Water

IF ounces = 4
    MEASURE 2 scoops

IF ounces = 4 && measure = 2
    mixALL

## Finish

IF property = smooth
    console.log(Here Child)