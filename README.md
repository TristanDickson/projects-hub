# Projects Hub

A simple landing page showcasing various game projects.

## Live Site

🔗 **https://tristandickson.github.io/projects-hub/**

## Projects Featured

- **🚀 SpaceTS** - Space combat game with helicopters and airships
- **🦑 SquidTS** - Top-down melee action game
- **🔧 Testbed** - Physics collision testing sandbox
- **🍔 Gastronopoly** - Strategic restaurant management board game

## Deployment

This site uses GitHub Pages with automatic deployment via GitHub Actions.

### Setup

1. Go to repository Settings → Pages
2. Under "Build and deployment":
   - Source: **GitHub Actions**
3. Push to main branch - auto-deploys!

### Local Development

Simply open `index.html` in your browser. No build step required!

## Adding New Projects

Edit `index.html` and add a new card:

```html
<a href="https://tristandickson.github.io/your-project/" class="game-card">
  <div class="emoji">🎲</div>
  <h2>Your Project</h2>
  <p>Project description here.</p>
</a>
```

Commit and push - it will auto-deploy!

## License

MIT
