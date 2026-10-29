# Cabane agent skills have moved

Cabane's skills are now maintained in [cabane-app/cabane](https://github.com/cabane-app/cabane#build-with-ai)
so they stay consistent with the product. This repository is archived and will
receive no further updates.

## Install from the new repository

```sh
npx skills add cabane-app/cabane --skill create-cabane-model
```

Run the command in the same working folder and select the same agents as before.
If you previously installed globally, add `--global`. Installing from the new
source switches the skill's update tracking to `cabane-app/cabane`.

Existing installed copies continue to work. Their recorded source still points
here until you reinstall from the new repository, so `npx skills update` alone
will not pick up future changes from Cabane.

The [model skill](https://github.com/cabane-app/cabane/tree/main/.agents/skills/create-cabane-model)
still works without a Cabane checkout and retains its MIT license, Blender and
Three.js examples, sample desk GLB and Python validator.

For creating a floor layout from a plan, see
[build-floor-layout](https://github.com/cabane-app/cabane/tree/main/.agents/skills/build-floor-layout).
The [full skill list](https://github.com/cabane-app/cabane#build-with-ai) also covers
room furnishing, catalog presets and local setup.

The original files remain here to preserve existing links and installations.
They are a historical snapshot, not a maintained copy. Their [MIT license](LICENSE)
is unchanged.
