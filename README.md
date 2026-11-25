# Operation: The Forbidden Bricks

Standalone web edition v1.4 of the fictional Digital Forensics Essentials investigation.

## Publish to GitHub Pages

1. Put the contents of this folder or ZIP in the root of the branch you want to publish. Include the hidden `.nojekyll` file.
2. Configure the repository's GitHub Pages settings to publish that branch from its root.
3. Open the published site over HTTPS. The site works at the repository URL, including any repository name in its path.

Progress persists in the learner's browser for this site. The Case Journal can export a progress backup and the finished investigation produces a downloadable evidence packet.

## Preview locally

From this folder, run `python3 -m http.server 8765 --bind 127.0.0.1` and open `http://127.0.0.1:8765/` in a browser. The local server and the published HTTPS site both provide the secure context needed to verify file hashes.

The briefing opens with **Plastic Underfoot**. Use the music control if the browser blocks autoplay. Inspecting the shipping box cues **The Block Syndicate**. The computer cue starts **Red Circles Mark the Map**. Audio, fictional evidence, illustrations and SQLite all load from this site's files.

To regenerate from the source project, run `python3 lab/build_web.py --esbuild /path/to/esbuild` in that project.
