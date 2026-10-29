# Rural Opportunity Lab

From insight to opportunity.

A single-page static site (no build step). Everything lives in `index.html`:

- **Words:** edit the `SITE` block near the top of the `<script>` (initiatives, framework, team, beliefs, partners).
- **Colors and fonts:** the `:root` tokens at the top of the `<style>` block.
- **Photos:** add images to `photos/` and set each person's `photo` field in `SITE.team`.

Pages are routed by hash: `#home`, `#work`, `#approach`, `#about`.

**Before launch:** remove the `noindex` meta tag in `index.html` and delete `robots.txt`.
