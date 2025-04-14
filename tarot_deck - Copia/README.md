# Playful Tarot Deck

A web-based tarot deck that pairs traditional tarot symbolism with remarkable historical figures. Each card reveals how these individuals embodied the essence of their tarot counterparts through their lives, works, and legacies.

## Project Structure

```
tarot_deck/
├── index.html              # Main page displaying all cards
├── cards/                  # Directory containing individual card pages
│   ├── queen-of-cups.html  # Example card page
│   ├── king-of-swords.html # Example card page
│   └── ...                 # More card pages
├── images/                 # Directory for card images
│   ├── queen-of-cups.jpg
│   ├── king-of-swords.jpg
│   └── ...                 # More card images
└── README.md               # This file
```

## How to Add a New Card

1. **Create the Card HTML File**:
   - Copy an existing card HTML file (e.g., `queen-of-cups.html`) to the `cards/` directory
   - Rename it to match your card (e.g., `the-fool.html`)
   - Update the content with your card's information:
     - Title, subtitle, and tagline
     - Image path
     - Traits table
     - Aesthetic description
     - Notable quote
     - Navigation links

2. **Add the Card Image**:
   - Place your card image in the `images/` directory
   - Use a consistent naming convention (e.g., `the-fool.jpg`)

3. **Update the Main Index**:
   - Open `index.html`
   - Add your card to the `cards` array in the JavaScript section:
   ```javascript
   {
     id: "the-fool",
     title: "The Fool",
     subtitle: "Frida Kahlo",
     image: "images/the-fool.jpg",
     description: "Artist • Revolutionary • Free Spirit • Painter of Self",
     category: "major",
     path: "cards/the-fool.html"
   }
   ```

## Card Categories

- **major**: Major Arcana cards (The Fool, The Magician, etc.)
- **wands**: Wands suit cards
- **cups**: Cups suit cards
- **swords**: Swords suit cards
- **pentacles**: Pentacles suit cards

## Card Template Structure

Each card page follows this structure:

1. **Header**: Card title, historical figure, and tagline
2. **Image**: Visual representation of the card
3. **Traits Table**: Comparison between tarot traits and historical figure
4. **Aesthetic Description**: Visual elements associated with the figure
5. **Notable Quote**: A meaningful quote from the historical figure
6. **Navigation**: Links to return to the deck or navigate to adjacent cards

## Styling

The project uses a consistent color scheme:
- Primary: `#7a5c99` (Purple)
- Background: `#fdfaf5` (Off-white)
- Text: `#2f2f2f` (Dark gray)
- Accents: `#f0eaf2` (Light purple)

## Credits

© 2025 Playful Tarot Project 