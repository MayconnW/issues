# Error when trying to render the map  in test

It seems we are getting an error with how libtess.js has been compiled

## Our environment

 - We are using the latest webpack@5 accordling with this [instruction](https://developers.arcgis.com/javascript/latest/es-modules/);
 - Our package.json has this: "@arcgis/core": "^4.25.5";
 - We are copying the issues locally setting the assetsPath.
![enter image description here](https://i.ibb.co/jkY6Kr4/i-Screen-Shoter-2022-12-12-17-55-48-247.jpg)

## The test
After all set, in our acceptance test, we need to interact with the map. For example we use the native search bar to search address. We are able to have everything working, but there is one error that shows everytime and we can't find a solution. 
![enter image description here](https://i.ibb.co/rMmm0g7/i-Screen-Shoter-2022-12-12-18-03-15-805.jpg)
![enter image description here](https://i.ibb.co/80LMrVP/i-Screen-Shoter-2022-12-12-18-02-46-878.jpg)
We tried to run the test pointing to the api instead of using the assets locally, just to see if it will work, but still having the same issue. 

