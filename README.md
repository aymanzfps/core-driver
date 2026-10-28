# Core Diver

A one-finger arcade game: steer a drill down through layers of rock to reach the core.

- **Hold** to drill, **drag** to steer.
- Rock shatters and gems are worth bonus points. **Black bedrock breaks your drill.**
- Smash 10 blocks in a row for double points; 20 without letting go turns you **Molten** for 3 seconds, and you plow through bedrock too.
- Each level is deeper and faster, with more bedrock.

## Play

It's a single `index.html` with no build step. Open it in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000. Your best score and level are saved in the browser.
