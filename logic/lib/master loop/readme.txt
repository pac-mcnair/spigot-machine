'master loop' is the highest level part of the spigot machine. This circuit makes use of a number of other circuits, as depicted below:

  [master loop version Z 19 feb 2022.dig]
	|		
	|		
  |-----[3 x 10 bit multiply version E 19 feb 2022.dig] (purple)
	|		
	|		
  |-----[6 x 10 bit multiply version K 19 feb 2022.dig] (yellow)
	|		
	|		
  |-----[15 bit div 11 bit blocked version E 05 feb 2022.dig] (orange)
	|     |				
  |     |----------[15 bit div 11 bit triple block version B 05 feb 2022.dig] (teal)
	|		
  |
  |-----[6 bit div ten version I 06 feb 2022.dig] (green)
  
  Note that the '15 bit div 11 bit blocked' circuit (which divides a 15 bit number by an 11 bit number) itself uses the sub-circuit '15 bit div 11 bit triple block'.
  
  Dates/versions are those at which point the whole edifice was transferred to GitHub.
