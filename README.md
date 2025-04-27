# spicetify-bigger-album-cover
A CSS snippet for Spicetify that allows customization of album cover dimensions in the player

![Preview](preview.png)

## Features

- Bring back a decent album size to Spotify since they don't seem to care

## Installation

1. Install [Spicetify](https://spicetify.app/) if you haven't already
2. Download or copy and paste `bigger-album-cover.css` from this repository
3. Go to "Snippets"
4. Click on "Add CSS"
5. Follow through and apply.

## Customization

You can customize the album cover dimensions by editing the CSS variables in the `:root` section:

```css
:root {
    --cover-art-width: 250px;    /* Album cover width */
    --cover-art-height: 250px;   /* Album cover height */
    --cover-art-radius: 8px;     /* Corner radius */
    --cover-art-bottom: 90px;    /* Position from bottom */
}
```

Adjust these values to your preference. After making changes, run `spicetify apply` to see the results.

## Compatibility

This snippet should work with most Spicetify themes. It includes extra code to prevent the progress bar from overlapping with the cover art on themes like Sleek.

## Credits

- Adapted and maintained by mynameismaurizio

## License

MIT
