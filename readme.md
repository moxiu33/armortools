![](https://armorpaint.org/img/git_root.jpg)

armortools/armourpaint binaries
==============
### ArmourPaint bianry (1.0-alpha-11_02_2025):
> it comes as .7z package so make sure to have tool like 7-zip or peazip to extract it

[/tag/1.0-a-11_02_2025](https://github.com/moxiu33/armortools/releases/tag/1.0-a-11_02_2025)

3D content creation tools.

[armorpaint/](https://github.com/armory3d/armortools/tree/main/armorpaint)<br>
[armorlab/](https://github.com/armory3d/armortools/tree/main/armorlab)<br>
[armorsculpt/](https://github.com/armory3d/armortools/tree/main/armorsculpt)<br>
[armorforge/](https://github.com/armory3d/armortools/tree/main/armorforge)

**Generating a locale file**
```bash
./armorcore/make --js base/tools/extract_locales.js <locale code>
# Generates a `base/assets/locale/<locale code>.json` file
```

**Embedding data files**
```bash
# Requires compiler with c23 #embed support (clang 19 or newer)
../armorcore/make --embed
```
