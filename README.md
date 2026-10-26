# Wandering Green

A responsive browser golf prototype with five original ink-wash inspired courses. Click or tap to aim, choose putter or wedge, adjust power, and shoot. Best scores are saved locally on the device. Sound is optional.

## Development

Requires Node.js 22 or newer.

```sh
npm ci
npm run dev
```

`npm run build` produces a static site in `dist/`. Deploy that directory to a static hosting service. `npm run preview` serves the production build locally.

## Physics

Fixed 120 Hz simulation with ground friction, simple course gradients, increased sand friction, ballistic wedge flight, bounce energy loss, speed-dependent hole capture, and one-stroke water penalties. This is a stylized prototype, not a calibrated golf simulator. Terrain and boundaries are approximations; playtesting and visual browser QA remain necessary.

## Monetization roadmap

No live advertising or tracking is installed. A sensible first placement is an optional sponsored card between completed holes, outside active play. Connect a publisher account only after deploying to an approved domain. An ad provider may require privacy disclosures, consent management, an ads.txt file, and traffic approval. Keep gameplay available when advertising is blocked or unavailable. Do not offer incentivized ad views unless the provider explicitly supports that format. Revenue depends on audience, retention, geography, and advertiser demand.

The artwork is procedurally drawn and original; no manga panels, characters, or licensed assets are used. Fonts load from Google Fonts with local serif and sans-serif fallbacks.
