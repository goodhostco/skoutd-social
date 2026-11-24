# goodhostco/skoutd-social

Public hosting for rendered @skoutd.ai social media (carousel slides, single images, reels). Instagram and Facebook fetch them by URL through jsDelivr, pinned to the commit. Kept out of the app repo so posting never triggers a deploy.

- Written only by the `social-daily` job (rules live in the private `goodhostco/skoutd` repo, `marketing/social/`).
- Layout: `gen/<YYYY-MM-DD>-<slug>/NN.jpg`, `reels/<YYYY-MM-DD>-<slug>.mp4`.
- Files older than 21 days are pruned; the platforms keep their own copy.
