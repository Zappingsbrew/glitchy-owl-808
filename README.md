# glitchy-owl-808

My super private Minecraft server for my family. Not your family, sorry.

---

## What is this?

Welcome to **glitchy-owl-808**, the code name for my ultra-secret Minecraft server project that me and my siblings/cousins are building together.

This isn’t just any server — it’s a place where we explore sprawling cities, build epic structures, and go on crazy adventures without the usual internet noise.

---

## Why “glitchy-owl-808”?

Because every good project needs a quirky name!  
- **Glitchy:** For the unexpected twists and Minecraft bugs we love to exploit.  
- **Owl:** Because owls are cool, mysterious, and watchful.  
- **808:** Because it sounds cool and reminds me of classic drum machines.

---

## What’s inside?

- Multiple pre-made city worlds (including **Greenfield** and others!) for us to explore and build on.  
- Warp points carefully organized so you can jump from city to city without getting lost.  
- Resource packs that keep the world looking fresh and awesome on both Java and Bedrock editions.  
- Geyser and Floodgate support to let Bedrock players join in the fun.  
- EssentialsX managing warps, permissions, and basic server magic.  
- Multiverse plugin to handle multiple worlds seamlessly.

---

## How to use this repo

This repo contains:  
- Config files for EssentialsX warps (including custom warps for all cities)  
- Sample server.properties for resource pack URLs  
- Geyser config snippets for Bedrock resource packs  
- Instructions on setting up your own private Minecraft server similar to ours  
- Scripts and batch files (coming soon!) for automating backups and restarts

---

## Server setup overview

1. Clone or download this repo to your server folder.  
2. Place your resource packs somewhere public (GitHub Pages, Dropbox, etc.) and update URLs accordingly.  
3. Install PaperMC 1.21.4 jar for best plugin compatibility.  
4. Install plugins: EssentialsX, Multiverse-Core, Geyser-Spigot, Floodgate.  
5. Copy warp yml files to `plugins/Essentials/warps/` folder.  
6. Edit warp files to reflect your world folder names (important if you use multiple worlds).  
7. Update `server.properties` with your resource pack URL and SHA-1 hash.  
8. Configure Geyser to point to the Bedrock resource pack.  
9. Start server and enjoy!

---

## Tips & Tricks

- Always test new warp files on a backup copy first.  
- Keep your worlds organized in neat folders — no messy clutter.  
- Use a text editor like Notepad++ to batch edit warp yml files faster.  
- For resource pack hosting, GitHub Pages is free and reliable.  
- Regularly back up your worlds and config files to avoid data loss.  
- Have fun, but keep the griefers out — whitelist only your trusted players.

---

## Troubleshooting

- **Warp doesn’t teleport properly?**  
  Check if `world:` and `world-name:` fields in the warp yml file match the exact folder name of your world.

- **Resource pack not applying?**  
  Double-check your `server.properties` URLs and SHA-1 hashes. Also verify Geyser’s Bedrock resource pack settings.

- **Bedrock players can’t connect?**  
  Confirm Floodgate plugin is installed and configured, and ports 19132 (default) are open on your router/firewall.

---

## Future plans

- Automate warp file edits with scripts (Python or batch).  
- Add more custom cities and cool warp points.  
- Integrate Discord bot for server announcements and warp commands.  
- Create a custom launcher to bundle resource packs and mods easily.

---

## License

This repo is private and just for family fun — please don’t share or use without permission. But if you want tips or help setting up your own, I’m happy to share knowledge!

---

## Thanks for stopping by!

If you found this by accident, sorry — the server’s invitation is strictly family-only. But feel free to check out my other Minecraft projects or ask me questions about server setup.

---

*Stay glitchy, stay owl-ish.* 🦉✨

---

