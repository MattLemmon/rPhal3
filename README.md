# rPhal3 - Alternate folder structure for rPhalanx2 by allcaps (mikezila)

  I have not changed the original game at all.

  The only thing I have done is to move the files around a little and put some of them into a folder called 'rb'. I also renamed 'bg.rb' to 'parallax.rb'.

  And I also changed the .TTF files to .ttf for case-sensitivity purposes.

  Original README included below:


# rPhalanx 2 - by allcaps

## What is this?
It's a very early and equally poor re-make of the SNES/GBA/ancient Sharp PC game Phalanx.  A game that is mostly famous for having an old guy with a banjo on the north american SNES box art.

## Why?
Just as a programming exercise, for fun.  I don't actually plan to turn this into a full game.  If I do I'll be changing the name and replacing the art obviously.  I'm mainly sharing so that other beginner Rubyists can see the code and draw inspiration from it.  Or steal bits of it.  I don't know or care about licenses, so any code in this project is yours to use however you want.  This doesn't apply to the art, since that was lifted from an SNES game.

## Why 2?
This is my second attempt at remaking the game, or at least its engine.  This version includes support for gamestates, object tagging, and is generally much cleaner than my initial attempt.  The first time I did things quickly to make cheap progress, this time I did things correctly.  Well, more correctly.

## Requirements
Just Ruby and the Gosu gem.  If you're on Windows use Ruby 1.9.3, as Gosu doesn't work with Ruby 2.0 on Windows yet.  Just do...

     gem install gosu

I presume it'll work on Ruby 2.0 as well if you're using OS X or Linux, but I haven't tested it.  It can get a little hairy on slower computers, but any Core2Duo or better should be capable.

## Known Issues
I don't do resource loading like I should, so it might not work for you due to working directory nonsense.  Sorry.  I'll fix that at some point.

## What are the controls?
You can move with the arrows and fire shots with spacebar.  Press B to cycle through the three levels of movement boost.  There are no other keys right now.
