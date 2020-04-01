# FreeCAD Adjustable Storage Dresser

## ATTENTION: This project is in the process of being depricated

I'm scrapping this project in favor of a different workflow. I've found that
a majority of this design can be easily replicated in the LC Workbench.
Therefore, I've decided to phase this project out while documenting a similar
build with the aforementioned workbench. The goal will be to cover the knowledge
gap for building a similar design from start-to-finish, along with pre-fabs &
additional resources.

Adjustable storage dresser designed in FreeCAD. Design inspired by a [drawing found on
3axis.co](https://3axis.co/small-dresser-storage-mdf-4mm-8mmdxf-file/d1ledz7m/), created by YOANN.

![Example drawing](Storage_Dresser_Drawing.svg)

## Goals/Features:

The aim of this project is to make a CAD file with all necessary shapes to make
a storage dresser & drawers. Additional goals are:

- Adjustable for all material thicknesses.
- Fully automated tab depth adjustment (changing material thickness changes tab
  depth by default).
- All dimensions kept in an associated spreadsheet for easy adjustment & repurposing.
- Shapes should hold true under any input dimension.
- All fitment features (such as tab width & drawer depth) should automatically
  be calculated from:
  - Dresser Height
  - Dresser Width
  - Dresser Depth
  - Drawer Height
  - Drawer Width
  - Drawer Count Up
  - Drawer Count Across 

## ToDo:

- [ ] Fix "Dresser Side" sketch so that it conforms to the rest of the dresser
      solid dimensions.
- [ ] Finish adding all relavant constraints to all solids, re-adding or
      removing constraints as necessary.
- [ ] Clean up spreadsheet calculations (remove redundancy).
- [ ] Confirm placement of each solid is calculated through its neighbor, in such a way that
      changing dimensions doesn't shift parts closer (or further away) from its neighbor.
- [ ] Tie drawer number to some kind of array mechanism, so that shelf count
      & dresser width can be added through the spreadsheet.

## License:

All items in this project are released under the [GNU GPL v3.0 license](https://www.gnu.org/licenses/gpl-3.0.en.html).
