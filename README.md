# JOSM-MapCSS-styles

You need to save Africa.css as Africa.css.zip (i.e. just add the extension .zip). 

In JOSM: Preferences > Map > Map Paint Styles > Active Styles > +

Or use the right-most button in the Map Paint Styles panel. 

You may need to re-order / de-activate other styles in the Map Paint Styles panel.

Used initially for "Salima District Malawi Road Network" HOTOSM task.

# Styles

- Highways are labeled with the highway type (tertiary, residential, unclassified etc)
- highway=residential: light purple (to distinguish from unclassified)
- highway=track: solid green line with white halo (as they are at the same level as unclassified)
- highway=path: blue (not passable by vehicle, but passable by people)
- Highways that don't have a surface tag are highlighted in pink. Text halo: Surface=unpaved->blue; surface=paved->grey.
- landuse=residential: blue outline, with halo at lower z to improve visibility
