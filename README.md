# LUQI group poster templates

## Choose your template size

- `template-48x36.tex` - 48" x 36" (4' x 3' landscape)
- `template-72x36.tex` - 72" x 36" (6' x 3' landscape)
- `template-72x48.tex` - 72" x 48" (6' x 4' landscape; fits a **4' high x 6' wide** board)
- `template-96x48.tex` - 96" x 48" (8' x 4' landscape; fits a **4' high x 8' wide** board)

The `72x48` / `96x48` variants use `fontscale=0.14` and a `\huge` title (~2" lettering,
~1" body) so they are legible from 10-12 ft. `baposter` sets physical font size from
`fontscale` alone (it magnifies a `fontscale x board` base page by `1/fontscale`), so a
bigger board viewed from farther uses a *smaller* `fontscale` to get *larger* letters.

## Example

See `example.tex` for guidance on content and layout.

## Compile

```bash
pdflatex template-48x36.tex
```

## License

MIT

