## Interview tips
* Properly understand the problem. Ask clarifying questions, and also ask about constraints if not provided. Just don't assume anything. Ask everything in the beginning before you jump into solving it.
    * Ask if there are negative values?
    * Ask if there are duplicate values?
    * Ask if the size of the given array/string or whatever DS it is, will be zero?
* Tell brute force first , then incrementally for optimal solution.
* Maybe, first write your approach in comments at the top. This small tip could be super helpful.
* They are checking your Communication also. Explanation should be crystal clear. Don't assume that interviewer is a friend. Explain him thoroughly. If you choose any algorithm then give him proper intuition that why you think that intuition will work, rather than simply telling him high level.
* Keep asking him is everything clear upto now, or was there any part I should explain in more depth?
* Don't be silent for too long. Doesn't leave good impression. Try to break ice at specific intervals if silence is too long. May use fillers like "Questions would have been simpler if....", "Thought for this approach but this won't work because of this problem...", etc.
* If stuck for too long, then be shameless and ask "Could you share any hint?"
* Check if it will work for edge cases:
    * Empty array/string
    * Single element array/string
    * All elements same
    * negative values
    * duplicate values
    * Very large values
    * will it work for last iteration? (Very important, as I always miss this)


## DSA tips
* Use good varible names, even they are little long, they make things more intuitive.
* Write modular code! For e.g. if you need to use next smaller element and previous smaller elememt. Don't do everything in main function itself. Create functions for them so that code is modularised and is easier to debug.
* In graph, if constraints are 1-based then don't forget to -1 them to offset because generally we use 0-based indexed arrays.
* If working with binary strings then please use '1'/'0' instead of 1/0