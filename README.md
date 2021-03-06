# The Movies

Simple app witch provide a list of movies from [The Movie DB](https://www.themoviedb.org) API and a short
details with cover image and background. Also this project follow the  MVVM architecture.

If you want to know more about this API follow  [The Movie API](https://www.themoviedb.org/documentation/api)

## Features

- List  of movies
- Search movies
- Movie details (with more info now)
-  Favorite a movie

## Other implementations

- UI improvements using UIDynamics to animate cover image and cnahges the cell background color to differ the following cell.

## Code coverage

More than 89% with UI test included.

## Build

To build you will need to install [Pods](https://cocoapods.org) and call pod update in your terminal.
```
pod update
```

## Pods used in this app

```
pod 'Alamofire', '~> 4.4'
pod 'AlamofireImage'
pod 'SwiftyJSON'
pod 'OHHTTPStubs/Swift', '~> 6.0.0'
```

## Layout

I also uploaded in this repository a [Sketch](https://www.sketchapp.com) file with the initial idea about the app layout.

## Contributors

[Phelippe](https://github.com/phyll88) with your amazing knowledge with size class and constraints.

## Next Steps

- About
- Re order my movies
- Custom transactions
- UI Improvements
- Tag movie as watched
