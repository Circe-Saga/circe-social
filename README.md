# circe.social

The company site for Circe Social Co. It's plain static HTML with no build step and no JavaScript, so crawlers and reviewers read the same text people do. Hosted on GitHub Pages; `CNAME` sets the custom domain.

- `/`: the company, its product (Saga) and its leadership.
- `/team/`: leadership bios. Keep them word-for-word with saga.you/team (`Saga-React-WebApp` `src/content/team.ts`), because a reviewer compares the two.

Content rules (same as saga.you/team): facts only; no headshots, addresses, phone numbers or cap-table details.
