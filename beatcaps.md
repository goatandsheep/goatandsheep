# BeatCaps portfolio

> An accessibility-driven project to piggyback on the captions protocol for time specific events such as gaming rumble and musical rhythms. This method is patent-protected.

## Beatcaps

> A software platform that generating rhythms from music and videos

### Current projects

* [Marketing site](https://www.beatcaps.io/)
* [Sample page](https://goatandsheep.github.io/beatcaps-sample/): [source](https://github.com/goatandsheep/beatcaps-sample)
* Beatcaps library: a library that analyzes music and video files for rhythms using Fourier and outputs the times of the rhythms in JSON
* Beatcaps server: a Docker server that runs the beatcaps library in a secure way and works best with Amazon Web Services
* [Node-webvtt](https://github.com/osk/node-webvtt/): a convertor from JSON to VTT captions format (major contributors)
* [Dashboard](https://app.beatcaps.io/): [source](https://github.com/goatandsheep/beatcaps-react)
* Dolby Digital Audio integration

### Future Projects

* [Node-srt](https://github.com/goatandsheep/node-srt/): a convertor from JSON to SRT captions format (WIP)

## Hapticast

> A system for streaming timing events through captions protocol, especially for gaming

### Current projects

* Haptic router: a driver that taps into computer games and channels it into [OBS Studio](https://obsproject.com/), an open source program for video streaming to social media platforms like Twitch
* [Slide Deck](https://docs.google.com/presentation/d/1TeZfb4tftIsxQ-1Zd-7kaAQG1lgAyOUo6bCtmrGt-NY/edit?usp=sharing)
* [Deck Video](https://www.youtube.com/watch?v=iGXXlaUfa8w)
* [Demo video](https://www.youtube.com/watch?v=J0VdJMUe9lE)
* [Browser Extension](https://gist.github.com/goatandsheep/06c8885aecd0366653e0f8885066e311)
* [Mobile Twitch demo page](https://goatandsheep.github.io/hapticast/)

### Future projects

* Haptics player to use captions files

## Related Open Source Repos

* [Color Randomizer](https://github.com/goatandsheep/color-randomizer): an open source Javascript library to easily change the color of HTML elements on event. This could be an output effect of a rhythmic event
* [Piez](https://github.com/goatandsheep/piez): an open source Javascript library to toggle the mobile browser haptic engine on event
* [Closed Captions Listener](https://github.com/goatandsheep/closed-captions-listener): an open source Javascript library to listen for caption events on video players and triggers callback events
* [Video shake](https://github.com/goatandsheep/video-shake): an open source Javascript library that creates a visual shaking effect on video players on receiving events

## Unrelated Projects in umbrella

* [Overleia](https://github.com/goatandsheep/overleia): an open source Javascript library for generating picture-in-picture videos using [ffmpeg](https://ffmpeg.org/)
* [PIP YouTube Viewer](https://goatandsheep.github.io/pip/): an open source viewer for watching YouTube videos with sign language interpreters ([see source](https://github.com/goatandsheep/pip))
* [PIP Project](https://github.com/goatandsheep/pip/wiki): a curated resource on how to create picture-in-picture videos for sign language interpreters 
* [Transcript CC](https://github.com/goatandsheep/transcript-cc): an open source Javascript library to turn a transcript into a time-estimated captions file
* [Watson JSON](https://github.com/goatandsheep/watson-json): an open source script to turn IBM Watson caption output into caption JSON to be used with other libraries like node-webvtt
