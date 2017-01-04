# tile-recognition: https://developer.clarifai.com/

This project uses Clarifai image and video recognition API, in order to perform tile recognition.

#Usage

1. Run the project using Chrome
2. Paste the Tile image url, then send the image to Clarifai.
   Note: Clarifai contains a set of tiles from the CTM website.
3. Clarifai will return all the images that are visually similar to the one provided 
   and the best 6 will be presented to the User 
   
#How the search is performed
The search is performed using what Clarifai calls Reverse Image Search (RIS).
With RIS, the user provides an image (url or bytes) and the results will return all the images in the search index 
that are visually similar to the one provided.
