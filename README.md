# String similarity / String distance problem

The task involves comparing the characters of two strings and calculating the distance between them. 
The distance is computed by adding 0 for characters that can align and 1 for characters that do not align. 
The final distance represents the number of characters that do not match between the two strings, along with any remaining characters in the longer string that cannot be aligned.

The steps to get this done involves;  

* You define the computeDistance function that takes two strings, s and s_prime(s'), as input.
* You find the lengths of both strings using len() and store them in len_s and len_s_prime.
* You find the minimum length between the two strings, as we need to iterate only up to the minimum length to avoid index errors.
* You iterate through each character in the strings using a for loop.
* If the characters at the same position do not match, we increment the distance variable by 1.
* After the loop, we add the absolute difference between the lengths of the two strings to the distance. This accounts for any remaining characters in the longer string that cannot be aligned with the other string.
* Finally, you return the computed distance.
