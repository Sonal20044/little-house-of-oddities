# The Little House of Oddities

A calm, painted fairy house you can explore. It's a hollow tree stump with six small rooms and the fairies who keep them.

**[Visit the live site →](https://YOUR-USERNAME.github.io/little-house-of-oddities/)**

## What you can do

- Click a room to step inside, and use the arrows to wander from room to room.
- Rearrange each room like a craft board by dragging the jars, books, cups, lamps, and even the fairies.
- Switch the candles, lamps and jars of light on and off.
- Draw anything you like in the Painting Pod. Your drawing appears in the little pod on the house.
- Play soft background music.

## How it was made

I designed and art-directed this project and built it with **Claude** (Anthropic's AI assistant) on claude.ai.

- **My role:** the concept, the moodboard and visual direction, the room and character ideas, accessibility goals, and many rounds of feedback. One big decision was moving it from a busy game to a calm space for exploring.
- **Built with:** one self-contained HTML file that uses SVG and plain JavaScript, with no frameworks and no image files.
- **Painted look:** SVG filters (turbulence and displacement) give the shapes uneven, brushy edges.
- **Music:** generated live in the browser with the Web Audio API.
- **Saving:** your room layouts and your drawing are kept in your own browser with localStorage.

## Accessibility

- Every room and object can be reached with Tab and used with Enter or Space.
- Arrow keys move the decorations, and Esc returns to the house.
- Focus is always visible.
- Motion stops for anyone who has reduced motion turned on.

## Inspiration

The moodboard included vintage cutaway dollhouses, colourful theatrical miniature interiors, and painterly fairy and creature illustrations by 2GHOSTS and Kim Minji. All the characters in this project are original.
