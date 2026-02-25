# ReplayKit Portfolio Embed

Light-theme, self-contained portfolio embed for ReplayKit, built as a single `index.html` page.

## GitHub Pages URL

`https://aelasmar01.github.io/Replay-Kit-Embed/`

## Google Sites Embed

Use the GitHub Pages URL in Google Sites:

1. In Google Sites, choose `Insert` -> `Embed`.
2. Select the `By URL` tab.
3. Paste `https://aelasmar01.github.io/Replay-Kit-Embed/`.
4. Resize the embed to a recommended height of `1100px` (minimum `980px`).
5. Verify behavior in both `Preview` and the published page.

If you need raw HTML for another host, use:

```html
<iframe
  src="https://aelasmar01.github.io/Replay-Kit-Embed/"
  title="ReplayKit Portfolio Embed"
  width="100%"
  height="1100"
  style="border:0; overflow:hidden;"
  loading="lazy">
</iframe>
```

## Compatibility Note

Tabs are implemented with CSS-only radio/label controls (no JavaScript required), so navigation works in restrictive embed environments such as Google Sites.

## Troubleshooting

- If tabs do not appear to switch in the Google Sites editor canvas, test with `Preview` and the published page first.
- Hard-refresh the published page after updates to avoid stale cached content.
