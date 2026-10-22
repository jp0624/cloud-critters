# Cloud Critters · Weather Playground

An original browser weather toy by John Parker. Mix four weather sliders, meet Pip, Moss and Puddle, discover six combinations and complete six meadow missions. Play immediately; no account or personal data required. This fictional simulation uses no real weather data.

## Run

Node.js 22+. `npm ci`, then `npm run dev`. `npm test` checks mission reachability, discovery boundaries and creature reactions. `npm run build` creates `dist/`, ready for Vercel.

## Interaction

Touch or drag native sliders; keyboard users can Tab to each control and adjust with arrows. Click or keyboard-activate critters, recipes, hints, surprise and reset. The sound toggle starts Web Audio only after interaction. Discovery and mission progress save locally with guarded storage and recovery from invalid data. Reset the sky preserves progress; fresh journal clears it after confirmation. Reduced-motion mode stops ambient animation.

## Implementation

Vite with native ES modules, semantic HTML, CSS, SVG character controls and Web Audio. A framework isn't needed for four sliders and a compact state model. Deterministic weather rules are isolated in `src/weather.js`. Original generated painted meadow art is combined with precise code-native SVG characters, particles and weather effects.

Artwork prompt: original hand-painted cartoon floating meadow, bold navy outlines, mint grass, coral mushroom house, turquoise pond, purple hills and a clear sky; no characters, text or fixed weather. Generated using the built-in image-generation tool.
