# Cursive Writing Practice App

An interactive, educational web application designed to help children learn cursive handwriting. The app provides animated demonstrations, step-by-step instructions, and practice features.

## Features

### Core Functionality
- **Animated Writing**: Watch letters being written slowly, stroke by stroke
- **Step-by-Step Instructions**: Detailed guidance for each letter explaining how to form it
- **Copybook Lines**: Traditional lined paper with:
  - Top line (for tall letters like b, d, h, l)
  - Midline (where short letters like a, c, e reach)
  - Baseline (where all letters sit)
  - Descender line (for letters like g, j, p, q, y)

### Input Options
- Type any word, letter, or complete sentence
- Quick letter selection grid for single letter practice
- Pre-made practice word suggestions
- Handles both uppercase and lowercase letters

### Settings
- **Cursive Style**: Choose from Modern, Traditional D'Nealian, Italic, or Spencerian
- **Writing Speed**: Adjustable from Very Slow to Very Fast (10 levels)
- **Letter Size**: Small, Medium, or Large
- **Pen Color**: Black, Dark Blue, Purple, Red, or Green

### Practice Mode
- Repeat words multiple times for practice
- Set number of repetitions (1-10)
- Progress indicator shows which letter is currently being written
- Jump to any letter by clicking the progress dots

### Navigation Controls
- Previous/Next letter buttons
- Pause/Resume animation
- Repeat button to restart the current word

## How to Use

1. **Open the App**: Open `index.html` in any modern web browser
2. **Enter Text**: Type a word, single letter, or sentence in the input box
3. **Click "Write It!"**: Watch the animated cursive writing demonstration
4. **Read Instructions**: Follow the step-by-step guidance in the yellow instruction box
5. **Practice**: Use the repeat function or practice mode to write along

## Educational Features

Each letter includes:
- **Instruction**: Step-by-step description of how to write the letter
- **Tips**: Helpful hints and things to remember
- **Visual Animation**: See exactly how the pen moves

Example instruction for the letter 's':
> Start below the midline. Curve up and to the left, then snake down and curve the other way. It's like a curvy snake!

## Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies required
- **Responsive Design**: Works on desktop and tablet devices
- **SVG Animation**: Smooth, scalable letter animations
- **Self-contained**: Single HTML file for easy deployment

## Browser Support

Works in all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Getting Started

Simply open the `index.html` file in your web browser. No installation or server required!

```bash
# Or serve locally if preferred
python -m http.server 8000
# Then open http://localhost:8000/cursive-writing-app/
```

## Tips for Teachers and Parents

1. **Start Simple**: Begin with single letters before moving to words
2. **Use Speed Settings**: Slow down the animation for beginners
3. **Practice Mode**: Set 3-5 repetitions for effective practice
4. **Read Aloud**: Have children read the instructions aloud as they watch
5. **Write Along**: Encourage children to write on paper while watching

## Letter Groups for Practice

**Round Letters**: a, c, d, g, o, q
**Tall Letters**: b, d, f, h, k, l, t
**Descender Letters**: f, g, j, p, q, y
**Challenging Letters**: f, r, s, z

## License

Part of the Lego Serious Play educational materials collection.
