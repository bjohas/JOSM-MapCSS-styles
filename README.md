# JOSM-MapCSS-styles

In JOSM: Preferences > Map > Map Paint Styles > Active Styles > +

Or use the right-most button in the Map Paint Styles panel. 

You may need to re-order / de-activate other styles in the Map Paint Styles panel.

Used initially for "Salima District Malawi Road Network" HOTOSM task.

Older versions of JOSM: You may need to save Africa.css as Africa.css.zip (i.e. just add the extension .zip, not actually a zip file). 

# Styles

- Highways are labeled with the highway type (tertiary, residential, unclassified etc)
- highway=residential: light purple (to distinguish from unclassified)
- highway=track: solid green line with white halo (as they are at the same level as unclassified)
- highway=path: blue (not passable by vehicle, but passable by people)
- Highways that don't have a surface tag have label highlighted in pink, with "NO SURFACE" added.
- Highways that have surface tag, text halo: surface=unpaved->blue; surface=paved->greyish/white.
- landuse=residential: blue outline, with halo at lower z to improve visibility
