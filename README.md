Did my eyes read this challenge level correctly? JUNIOR! I had completed all the Jr ones and was more than half way through the intermediate level challenges when I saw this one pop up as "new". I thought it would be a breeze but... not so much.

I was able to do the HTML, CSS and some of the JS but then I got a bit lost! So I searched YouTube for help and found this from CodeExplained: https://www.youtube.com/watch?v=UcrypywtAm0&t=1560s
and it was exactly as it said on the tin - the code was explained ... BEAUTIFULLY! I had to watch it MANY times and practice it "in my own code" for a few days - but I LOVE what I learned from him.

The first thing I did after fetching the data from the API was to give each object in the array an id. I did this by doing a forEach on the array and setting 2 parameters: item and index like this:
dataArray.forEach((item, index) => {
item.id = index + 1;
});

I used .toFixed(2) to get 2 decimal points after the price as it was inconsistent once I displayed the products from the API.

The key for being able to calculate the number of items in the cart was to create a new key - value object pair in the array called: numberOfUnits and = it to 1. I did this using destructuring. I also had to do this for the number in the red button which pops up when the user clicks the Add to Cart button.

I know my code is very messy and juvenile in some areas but this was a great learning experience for me.
