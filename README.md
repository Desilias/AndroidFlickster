# AndroidFlickster
# Project 1 - * Flickster *

** Flickster ** shows the latest movies currently in theaters. The application uses the Movie Database API to display images and basic information about these movies to the user.

Time Spent: 72 hours Total Time

## User stories

The following required functionality is complete:

 [] The user can scroll through the current movies from the Movie Database API
[] The layout is optimized with the [ViewHolder] pattern (http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView#improving-performance-with-the- viewholder-pattern).
 [] For each movie displayed, the user can see the following details:
   [] Title, Poster Image, Overview (Portrait Mode)
   [] Title, Background Image, Overview (Landscape Mode)

The following optional features are implemented:

[] Show a nice default [placeholder graphic] (http://guides.codepath.com/android/Image-Images-with-Picasso-Library#configuring-picasso) for each image when loading .

The following bonus features are implemented:

 [] Allows the user to view movie details, including ratings and popularity, in a separate activity or snippet.
 [] When viewing a popular movie (ie, a movie voted for more than 5 stars), the video should show the complete background image as a layout. Uses [Heterogeneous ListViews] (http://guides.codepath.com/android/Implementing-a-Heterogenous-ListView) or [Heterogenous RecyclerView] (http://guides.codepath.com/android/Heterogenous-Layouts-inside- RecyclerView) to display different layouts.
 [] Allow full-screen trailers to play using YouTubePlayerView.
    [] Overlay a play icon for videos that can be played back.
     [] The most popular movies must start a separate activity that plays the video immediately.
     [] Less popular videos rely on the details page to view ratings and YouTube preview.
 [] Apply the popular [Butterknife annotation library] (http://guides.codepath.com/android/Reducing-View-Boilerplate-with-Butterknife) to reduce the standard code.
 [] Apply rounded corners for background or poster images using [Picasso Transformations] (https://guides.codepath.com/android/View-Images-with-Picasso-Library#other -transformations)
 [] Replacing the android-async-http network client with the popular networking libraries [OkHttp] (http://guides.codepath.com/android/Using-OkHttp).

The following ** additional ** features are implemented:

[] List anything else you can do to improve the functionality of the app!

## Video step-by-step

Here is an overview of the implemented user stories:

<img src = 'http: //i.imgur.com/link/to/your/gif/file.gif' title = 'Video Step by Step' width = '' alt = 'Video Walkthrough' / >

GIF created with [LiceCap] (http://www.cockos.com/licecap/).

## Notes

I had difficulties using Picasso in the project

## Open source libraries used

- [Android asynchronous HTTP] (https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON analysis
- [Picasso] (http://square.github.io/picasso/) - Image loading and caching library for Android

## Licence

    Copyright [yyyy] [Desilias Dimitry]

    Licensed Apache, Version 2.0 (the "License");
    You may not use this file except in accordance with the license.
    You can get a copy of the license at

        http://www.apache.org/licenses/LICENSE-2.0

    Except as required by applicable law or accepted in writing, software
    distributed under license is distributed "AS IS",
    WITHOUT WARRANTY OR CONDITION OF ANY KIND, express or implied.
    See the license for the specific language governing permissions and
    limitations under the license.
