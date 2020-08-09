# Method-overloading-challenge

	/**
	 * Create a method called calcFeetAndInchesToCentimetres, it needs to have 2 parameters (feet, inches).
	 * 
	 * You should validate that the first parameter feet is >= 0
	 * You should validate that the second parameter inches is >= 0 and <= 12
	 * return -1 from the method if either of the above is not true.
	 * 
	 * If the parameters are valid, then calculate how many centimeters comprise the feet and inches passed 
	 * to this method and return that value.
	 * 
	 * Create a second method of the same name but with only 1 parameter (inches)
	 * validate that its >= 0
	 * return -1 if it's not true.
	 * 
	 * If its valid, then calculate how many feet are in the inches and here is the tricky part:
	 * call the other overloaded method passing the correct feet and inches calculated so that it can calculate
	 * correctly.
	 * 
	 * Hints:
	 * Use double for your number datatypes is probably a good idea
	 * 1 inch = 2.54cm and 1 foot = 12 inches
	 */
