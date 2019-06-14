# CodingExercisesDay027
# Counting Number Frequency
Used a comma separated file (CSV) file located on the hard drive. Ive used loto numbers from the 6/49 Lottery . Open the file and then create a 50 integer array which will hold the counts for our 1-49 numbers. Meaning that if the number 1 is drawn, we are going to increment the value at numbers[1] and if we draw 15 we are going to increment the value at numbers[15].

We read each line and then split it into the various columns of data. Since the split is going to produce strings, we are going to need to read columns 1 through 6 and convert them to integers before we can use them as indexes. We loop through each of the 6 numbers, find the correct index in the array and increment its value by 1. We will do this for all numbers drawn across all games. When the loop is done, then our array is going to hold the total count for each number. So all that is left is to loop through them and print them out.
