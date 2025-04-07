# Lots of cell types --> extending predefined colors

* we edit `paint_by_number_cell_coloring` in `modules/PhysiCell_pathology.cpp` to allow more colors
  - e.g., https://github.com/rheiland/annaj/blob/main/modules/PhysiCell_pathology.cpp#L1738
* requires recompiling when edited

Run `python get_studio.py` to create a local Studio directory, then:

```
python studio/bin/studio.py -c PhysiCell_settingsHuman_rh.xml
```
