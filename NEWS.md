NEWS
================
<Erik.Leppo@tetratech.com> and <jon.harcum@tetratech.com>

<!-- NEWS.md is generated from NEWS.Rmd. Please edit that file -->

    #> Last Update: 2019-10-30 11:59:27

# baytrendsmap 0.0.3.9003

  - Released - 2019-10-30
  - Shiny
      - Map, Trend, Add point outlines, Issue \#2.
  - NEWS
      - Keep NEWS.md file rather than delete.

# baytrendsmap 0.0.3.9002

  - Released - 2019-10-30
  - Shiny
      - Map, Range, Add point outlines, Issue \#2.
      - Update Help text., Issue \#1

# baytrendsmap 0.0.3.9001

  - Released - 2019-10-29
  - Shiny
      - Update Help screen, Issue \#1.

# baytrendsmap 0.0.3

  - Released - 2019-09-24
  - Release stable version with updates.

# baytrendsmap 0.0.2.9002

  - Released - 2019-09-24
  - Filter
      - Update “clearFilters” button.

# baytrendsmap 0.0.2.9001

  - Released - 2019-09-24
  - global.R
      - Test map zoom in global.
      - Make Shiny load silently as well.
  - Added 2nd test data file.
  - tab\_Data.R
      - Fix typo.
  - Trend map
      - NS points
          - Change “gray” to “dark gray”.
      - Modified (removed debug mode):
          - UpisGood
          - p value significant threshold
          - p value possible threshold
      - Proper map is created for title and river names.
  - Range map
      - “Pretty” option ignores number of breaks.
          - Added error trapping to use number of breaks output from
            pretty option.
  - Filters
      - Add “ClearFilters” button.
          - Inactive at this point.

# baytrendsmap 0.0.2

  - Released - 2019-09-19
  - Interim release.

# baytrendsmap 0.0.1.9013

  - Released - 2019-09-19
  - Trends map
      - Edits to global test.
      - Create Trends tab; similar to Range tab.
      - Create map.
  - Remove dynamic version number from title.
      - Causes Shiny.io to fail.
  - global
      - Base map declare fill color so don’t use scale\_fill\_manual.
  - tab\_Filter
      - Reorder tabs with filter summary before data.
      - Rename data tabs.

# baytrendsmap 0.0.1.9012

  - Released - 2019-09-18
  - Trends map, legend to include range of values.
  - DESCRIPTION; add packages
      - Add grid, lubridate, and sp
  - global.R
      - Suppress messages
          - library
          - readOGR
          - fortify
  - range map
      - Add button to auto-generate map title based on filtered
        selections.
      - Make auto-title wrap lines.
      - Add cut (break) numbers to legend.

# baytrendsmap 0.0.1.9011

  - Released - 2019-09-18
  - Add number of non-“one” entries on “Data Filter Summary” tab.
  - Modifty title to include dynamic package version number.

# baytrendsmap 0.0.1.9010

  - Released - 2019-09-05
  - DESCRIPTION
      - Reduced required R version from 3.6.0 to 3.2.0.
      - Matches baytrends package.

# baytrendsmap 0.0.1.9009

  - Released - 2019-09-04
  - Returned to use of shp file.

# baytrendsmap 0.0.1.9008

  - Released - 2019-09-04
  - GIS shapefile (cbpseg) to RDA.
      - Speed and file size improvement.

# baytrendsmap 0.0.1.9007

  - Released - 2019-09-03
  - Range map working.

# baytrendsmap 0.0.1.9006

  - Released - 2019-08-30
  - Range map selection buttons (not finished).

# baytrendsmap 0.0.1.9005

  - Released - 2019-08-29
  - Range map options.
  - Default Range map.

# baytrendsmap 0.0.1.9004

  - Released - 2019-08-29
  - Add dplyr package to global and DESCRIPTION.
      - Need for filter summary table.

# baytrendsmap 0.0.1.9003

  - Released - 2019-08-29
  - Filters working.
  - Structure for maps.
  - Filter summary so can find non-uniques and re-apply filters.
  - Packages to global.R.
  - Package updates to DESCRIPTION.

# baytrendsmap 0.0.1.9002

  - Released - 2019-08-28
  - Filters and other additions.

# baytrendsmap 0.0.1.9001

  - Released - 2019-08-26
  - Redesign interface.

# baytrendsmap 0.0.0.9005

  - Released - 2019-08-23
  - Add test data to create new map.
  - Modify Shiny app to use imported data file.

# baytrendsmap 0.0.0.9004

  - Released - 2019-08-21
  - Update Readme with usage directions.

# baytrendsmap 0.0.0.9003

  - Released - 2019-08-21
  - Update Readme with installation directions.

# baytrendsmap 0.0.0.9002

  - Released - 2019-08-21
  - Updated repository with working files.
  - Rename without underscore to baytrendsmap.

# baytrendsmap 0.0.0.9001

  - Released - 2019-08-21
  - Initial commit to GitHub