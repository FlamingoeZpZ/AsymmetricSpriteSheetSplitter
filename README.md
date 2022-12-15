# AsymmetricSpriteSheetSplitter
//**********************
// * Automatic image splitter
// * Inspired by Unitys image splitter
// * I needed a way to split images quickly, w/o BS and w/ varying cell sizes. 
// *
// * Splits images based on gaps between each image
// * NOTEs: 
// * This can mean that any gap between objects is split into a different sprite
// * I got lazy towards the end and just took a flood fill from the web. Any "BaseColor (0,0)" touching a neighbouring pixel will be deleted. In other words, make sure you have an outline.
// * I may not even get around to chucking in the FF because this serves what I needed
// *
// * Also, this app can convert jpg spritesheets into png sprites
// *
// * Made by: Gabe Kotton (P.S. JS is not my main language lol)
// * Last Edited: 2022-12-15
//**********************

Make sure you edit the declared variables
