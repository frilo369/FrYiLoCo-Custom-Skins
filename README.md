# FrYiLoCo Custom Skins

The shared custom skin collection that FrYiLoCo's **Update Custom Skins** (Settings > Library)
downloads from. `Custom Skins` here is the app's `Custom Skins` folder, exactly as the skin
database names it: one folder per champion, named as League names the champion, holding that
champion's `.fantome` files.

```
Custom Skins/Zed/Chibi Zed.fantome
Custom Skins/Zed/Minato Zed.fantome
```

- The file name is the name the catalogue shows.
- A picture beside a skin with the same name (`Ink Fizz.jpg`, also `.png` or `.webp`) is the
  artwork its catalogue card shows. Use the skin's Divine Skins thumbnail (640x360), or the skin's
  own loading screen when it has none there.
- This repository is full at about 1 GB. New skins go into `frilo369/FrYiLoCo-Custom-Skins-2`, laid
  out the same way; FrYiLoCo reads both.
- Keep every file an ordinary Git file under 100 MB. Do not use Git LFS.
- The update adds the skins a player does not have, and never replaces or renames theirs.
- To withdraw a broken skin, delete it here and add it to `removed.json` with Git's name for its
  contents (`git hash-object`) and its size. The update moves every file with exactly those
  contents to the player's Recycle Bin, whatever it is called; their own skins are never touched.
