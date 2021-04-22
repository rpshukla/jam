# JAM

A live coding environment that allows realtime collaboration through a web browser.

Inspired by other live coding systems such as:
- [Sonic Pi](https://sonic-pi.net/)
- [Tidal Cycles](https://tidalcycles.org/)
- [Gibber](https://github.com/gibber-cc/gibber)

## Project Status

I just started working on this so basically nothing is implemented yet :(

## TODO

- Implement backend with syncing
  - [ ] implement rudimentary syncing by sending enter buffer
  - [ ] implement differential syncing
  - [ ] implement 
- Add features to user API
  - [ ] silence function
  - [ ] sequence manipulation through decorators and dot operators

	  e.g. seq("c4 e4 g4").rand().half()
	       this would be a wrapper around:
		   new HalfSequence(new RandomSequence(new ListSequence(...)))

  - [ ] configuration of options such as cycles per second
  - [ ] effects
  - [ ] samples
- UI improvements
  - [ ] don't crash or stop music when an error occurs
  - [ ] show other users' cursors
  - [ ] keyboard shortcuts
  - [ ] syntax highlighting

## References
- https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Advanced_techniques
- https://www.html5rocks.com/en/tutorials/audio/scheduling/
