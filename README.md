# Unity Animator Extended

> “If you wish to make an apple pie from scratch, you must first invent the universe.”
> — Carl Sagan

Simply put, I wanted animator transition route nodes. That's all I needed. But in order to get that, I had to re-create (almost) the entire animator window...

**Animator Extended** is a single-file Unity editor tool that rebuilds the Animator graph experience with a practical goal: add transition reroutes, add transition parameter copy.

It does not try to replace Mecanim.
Just tries to add a simple thing that hasn't been added in decades
Eventually, I might start adding more stuff. But for now... 


## Features
- Animator-like graph window
- Editable transition reroute points
- Copy of transition parameters between transitions
- And (HOPEFULLY!) all the animator features we commonly use

## Installation

Install from Unity Package Manager using a Git URL:

https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git?path=/Assets/UnityAnimatorExtended

## Usage

Open from:

Window > Animation > Animator Extended

Then select an AnimatorController or a GameObject with an Animator.

## Notes

This is an editor-only tool.
It does not modify runtime Animator behavior.
But USE IT WITH CAUTION as always, I'm not responsible if you nuke your animator because you press the wrong button. This is still in development and it's a tool I'm using consistenly

## License

MIT License
