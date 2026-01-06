# LLM-VA Project Page

This is the GitHub Pages site for the paper "LLM-VA: Resolving the Jailbreak-Overrefusal Trade-off via Vector Alignment".

## Setup Instructions

### For GitHub Pages

1. Create a new GitHub repository (or use an existing one)
2. Copy `index.html` to the root of your repository
3. Go to repository Settings → Pages
4. Under "Source", select "Deploy from a branch"
5. Select the branch (usually `main`) and root folder
6. Save and wait a few minutes
7. Your site will be available at `https://yourusername.github.io/repository-name/`

### Local Preview

Simply open `index.html` in your web browser to preview the page locally.

## Customization

### Update Links

In `index.html`, update the following:

1. **Paper Link** (line ~90): Replace `https://arxiv.org/abs/XXXX.XXXXX` with your actual arXiv link
2. **Code Link** (line ~93): Update if you change the anonymous repository
3. **Models Link** (line ~96): Update if you change the Figshare link

### Add Figures

To add figures from your paper:

1. Create a `figures` folder in the same directory as `index.html`
2. Copy your figures (e.g., from `latex/figure/`)
3. Add them to the HTML using:

```html
<div class="figure-container">
    <img src="figures/your-figure.png" alt="Description">
    <p class="figure-caption">Figure caption here</p>
</div>
```

### Update Authors

After de-anonymization, update the authors section (around line 85):

```html
<div class="authors">
    Author1<sup>1</sup>, Author2<sup>1,2</sup>, Author3<sup>1</sup>
</div>
<div class="affiliation">
    <sup>1</sup>Institution 1, <sup>2</sup>Institution 2
</div>
```

### Change Colors

The color scheme uses purple gradients. To change:

- Primary color: Search for `#667eea` and `#764ba2` in the CSS
- Replace with your preferred colors

## Features

- ✅ Responsive design (mobile-friendly)
- ✅ Clean, modern academic style
- ✅ Font Awesome icons
- ✅ Easy to customize
- ✅ No external dependencies except Font Awesome CDN
- ✅ Fast loading

## Tips

- Keep the page concise - highlight key results
- Add visual elements (figures, diagrams) to make it more engaging
- Update regularly as your paper progresses through review
- Consider adding a video demo if applicable

## License

This template is free to use for academic purposes.
