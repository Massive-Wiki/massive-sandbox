## 2021-03-13, Pete

### Installing
How to install Vinzent03's fork of `obsidian-git`. Since there aren't releases of it yet, we pull from 'master'. Caveat utilitor!

Change directory to your vault's plugin directory.

`git clone https://github.com/Vinzent03/obsidian-git.git cd obsidian-git npm i npm run build`

Enable plugin within Obsidian.

### Configuring
(I already have git configured, so nothing for me to do about that.)

I enabled the plugin in Obsidian.

I set hotkeys: I'm trying ⌘L for pull, and ⌘U for push.

### Using (Experiment 1)

- yay, ⌘L worked (no updates)
- created this page, will try to push
- no joy, maybe I need to `git add .` by hand...
- ... and maybe even `git commit` by hand?
-  okay, adding and committing by hand let the plugin do its push
-  let's try some added lines (this and one above), maybe now it'll commit
-  ... nope.  Hmm.
-  I'll add+commit by hand with my Git client, and push again.  Thus ends Experiment 1.
