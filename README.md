# " tou"


syntax (bad) (ignore the #):



#2d pointer 20-256x5-32 (ascii out) ( TOU)
#arr1 = [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0]
#arr2 = [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0]
#arr3 = [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0]
#arr4 = [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0]
#arr5 = [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0]

#ptp = [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0]




# lang firstblock:
#.p skibidirizz (pack)
#.p ohirofanumtax (pack)
#ext to exit block

# lang 2ndblock:
#.w for width (default: 20)
#.ptp0 // 1 disables ptps, 0 does nothing
#ptps=(1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20)
# // sets the ptps to do stuff
#+* to change ptp cell
#. to point at next ptp
#ext to exit block

# lang 3rdblock:
# // starts at idx0
# <>ˇ^ to move pointer (wraps around)
#+-* to change cell
#% to print cell at pointer (ascii)
#$ to get input (gets char at pointer cell)
# _^^^^_#++++#{++++-`+`} makes loop until cell pointer ^^^^ gets ++++ ( meanwhile the pointer gets ++++-)
# -y-{>>>+++} if ascii char (from number) = y: >>>+++
#@skibidirizz§ohio§
#clr to clear screen
#ext to exit block



#example program (does not use all features):
#ext 

#.ptp0
#ext

#>>>++******+%
#ext

