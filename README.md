# Flix Assignment 1
 Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.



### App Walkthrough GIF


<img src="http://g.recordit.co/EhayRlkKYs.gif" width=250><br>

### Notes
Had issues with pod install. Found out that it's an issue
with M1 Macs. After some research "pod install" will NOT work for M1 macs instead
I used "arch -x86_64 pod install" for terminal.
Link to where I found pod install issue resolution:
https://github.com/CocoaPods/CocoaPods/issues/10518


## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.



### App Walkthrough GIF
<img src="http://g.recordit.co/PJduON1ZV1.gif" width=250><br>

### Notes
I had issue when it came to adjusting sizing. I played around with they layout line spacing and with screen resizing. Issue with transparent "Details" tap label since it was all see through.
