# tiny.london/world

The list behind [tiny.london/world](https://tiny.london/world/): cities drawn as one big isometric pixel-art map, each by someone who wanted one of their own.

## Add a map

The easy way: [open an issue](https://github.com/PennyroyalTea/tiny-world/issues/new?template=add-map.yml) with the link.

Or send a pull request that adds your map to [`maps.json`](maps.json):

```json
{
 "id": "lisbon",
 "city": "Lisbon",
 "country": "Portugal",
 "lat": 38.722,
 "lon": -9.139,
 "title": "Tiny Lisbon",
 "url": "https://example.com/",
 "author": "Your name",
 "author_url": "https://x.com/you",
 "source_url": "https://x.com/you/status/123",
 "launched": "2026-10-31",
 "description": "One plain sentence: what it shows and how it was made."
}
```

Only `id`, `city`, `country`, `lat`, `lon`, `title` and `url` are needed. `lat` and `lon` are the middle of the area your map shows. `source_url` is where you posted it. Add `"wip": true` if it is not finished yet.

What fits: an interactive map of a real place, in the isometric or pixel-art style, live on the web. The picture on the card is taken from your page's `og:image`, or a screenshot if it has none.
