# nosql-challenge
Module 12 challenge assignment

The first issue I faced during this assignment was when I tried importing "establishments.json". My original code for this import was "mongoimport --type json -d uk_food -c establishments --file establishments.json" but this kept giving me errors because the file "establishments.json" is contained entirely within one large array. Once I figured out that that was the issue, I used Xpert Learning Assistant to fix my original code, where I came up with the corrected version: "mongoimport --type json -d uk_food -c establishments --file establishments.json --jsonArray".

Secondly, I also had to use the Xpert Learning Assistant for some general debugging, most of which centered around syntax errors in the "regex" part of the assignment. But other than those general debugging errors, the assignment was pretty staightforward. I particularly enjoyed the part where I had to figure out how to search for restaurants within 0.01 degrees latitude and longitude of a particular restaurant.

