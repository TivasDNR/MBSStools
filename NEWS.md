NEWS-MBSStools
================

<!-- NEWS.md is generated from NEWS.Rmd. Please edit that file -->

    #> Last Update: 2021-04-01 15:01:16

# MBSStools v1.1.0.9037 (2021-04-01)

-   style: Fix items from goodpractice::gp()
    -   Trim lines to 80 characters
        -   IonContrib
        -   test-qc\_taxa
        -   qc\_taxa
        -   data
        -   MapTaxaObs
        -   server
        -   global
    -   Replace ‘=’ with ‘&lt;-’
        -   IonContrib
-   style: Fix typos

# MBSStools v1.1.0.9036 (2021-01-12)

-   chore: Rename files in instwith non-portable names

# MBSStools v1.1.0.9035 (2021-01-11)

-   chore: Fix comment line without leading comment symbol
-   chore: Document subfunctions of metric.values()
-   chore: Rename files in instwith non-portable names

# MBSStools v1.1.0.9034 (2021-01-10)

-   chore: Add bindings for global variables
    -   MapTaxaObs
    -   metric.scores
    -   metric.values
-   style: Trim lines to 80 characters
    -   metric.scores
    -   runShiny
    -   PHIcalc
-   chore: Remove View() from examples
    -   metric.scores
    -   metric.values
    -   PHIcalc
    -   IonContrib
    -   FlowSum

# MBSStools v1.1.0.9033 (2021-01-10)

-   chore: Remove Excel files from data folder
    -   AllFish\_95to16.xls
    -   TaxaMapsCrossWalk20170731.xlsx
-   style: Trim to 80 character lines
    -   FlowSum.R
-   chore: Remove orphaned package from DESCRIPTION
    -   plotly in Suggests
-   chore: Add non standard files to .Rbuildignore
    -   NEWS.rmd
    -   README.Rmd
-   chore: Change default for ion.ref parameter in IonContrib to NA
    -   Use MBSS.Ion.Ref if NA

# MBSStools v1.1.0.9032 (2020-12-27)

-   docs: DESCRIPTION, add Bug Reports entry
-   tests: qc\_taxa, replace = with &lt;-
-   refactor: Add foo:: to missing functions.

# MBSStools v1.1.0.9031 (2020-12-24)

-   docs: Readme, add codecov badge
-   docs: Readme, add gh R-CMD-check badge
-   docs: Readme, sort badges

# MBSStools v1.1.0.9030 (2020-12-24)

-   docs: Add test-coverage gh Action, codecov.io

# MBSStools v1.1.0.9029 (2020-12-24)

refactor: CodeFactor change 1:foo() to seq\_len(foo()) + MapTaxaObs.R

# MBSStools v1.1.0.9028 (2020-12-24)

-   docs: Remove docs folder for pkgdown in main branch
    -   pkgdown now handled by GitHub Action and is stored in the
        gh-pages branch

# MBSStools v1.1.0.9027 (2020-12-24)

-   docs: Add pkgdown github action
-   ci: Remove travis.yml (free service shutting down)

# MBSStools v1.1.0.9026 (2020-12-23)

-   docs: ReadMe, add lifecycle badge

# MBSStools v1.1.0.9025 (2020-12-23)

-   docs: ReadMe, not all changes updated from previous update

# MBSStools v1.1.0.9024 (2020-12-23)

-   docs: ReadMe, add CodeFactor badge

-   docs: ReadMe, Remove TravisCI badge as service is shutting down free
    accounts

-   ci: Remove TravisCI yaml and switch to GitHub Actions CI

# MBSStools v1.1.0.9023 (2020-07-09)

-   Rebuild vignette with taxa distribution map as image; Issue \#33

# MBSStools v1.1.0.9022 (2020-07-09)

-   Shiny app, ensure download button is not active until create zip
    file; Issue \#32

    -   Add shinyjs to DESCRIPTION

# MBSStools v1.1.0.9021 (2020-07-09)

-   metric.values; Issue \#30 and \#31

    -   Modify Exclude column QC check.

# MBSStools v1.1.0.9020 (2020-07-09)

-   metric.values; Issue \#34

    -   Added Piercer as valid FFG entry.

-   UI.R

    -   Added version number to title of Shiny app.

# MBSStools v1.1.0.9019 (2020-07-02)

-   metric.values; Issue \#30
    -   Add basic QC fixes for non-standard bug files.

# MBSStools v1.1.0.9018 (2020-07-02)

-   qc\_taxa
    -   Fix typo in example.

# MBSStools v1.1.0.9017 (2020-07-01)

-   metric.scores; Issue \#29
    -   Fish message about 0 individuals always showing.
        -   Added condition so prints only if relevant.

# MBSStools v1.1.0.9016 (2020-07-01)

-   Update taxa\_fish data without an extra column.

# MBSStools v1.1.0.9015 (2020-06-30)

-   Remove SiteID from \_95to16.xls.
-   Replace example data files in shiny app (munged Site IDs).
-   Update Vignette.

# MBSStools v1.1.0.9014 (2020-06-30)

-   Modify Site IDs in bug (genus and family) and fish data.
-   Update Vignette.

# MBSStools v1.1.0.9013 (2020-06-26)

-   Vignette not rebuilding.
    -   Replace XLConnect with readxl.
        -   Java issue.

# MBSStools v1.1.0.9012 (2020-06-23)

-   Update Shiny app to use qc\_taxa(); Issue \#26

# MBSStools v1.1.0.9011 (2020-06-23)

-   Update pkgdown website.

# MBSStools v1.1.0.9010 (2020-06-23)

-   metric.values
    -   QC checks on valid values; Issue \#26

# MBSStools v1.1.0.9009 (2020-06-23)

-   qc\_taxa
    -   New function; Issue \#13 and \#26
-   tests
    -   Add tests for qc\_taxa

# MBSStools v1.1.0.9008 (2020-05-22)

-   taxa\_fish
    -   Update 2 Species name errors so passes QC check.

# MBSStools v1.1.0.9007 (2020-05-21)

-   Add testing
    -   DESCRIPTION, add testthat to Suggests
    -   test PHIcalc, Issue \#19

# MBSStools v1.1.0.9006 (2020-05-20)

-   metric.scores.R, Issue \#20
    -   Update column name checking for user input data frame.
        -   Edit error message to user.

# MBSStools v1.1.0.9005 (2020-05-20)

-   metric.scores.R
    -   Fix error in assigning final IBI due to changes in behavior of
        Tibbles.

# MBSStools v1.1.0.9004 (2020-05-20)

-   Shiny App, Issue \#22.
    -   File upload size increased from 10 to 25 MB.
    -   Output file format, tsv to csv.
    -   Zip file download.
        -   Remove input file (original and transformed).
        -   Keep only the “results\_” files (values, scores, and plot).

# MBSStools v1.1.0.9003 (2020-05-20)

-   Update fish metric scoring for no taxa obsevered, Issue \#26
    -   taxa\_fish.rda
    -   data.r
    -   metric.scores.r

# MBSStools v1.1.0.9002 (2020-05-18)

-   Update metric.values.
    -   Error when using R v4.0. Issue \#28.

# MBSStools v1.1.0.9001 (2019-06-13)

-   Add pkgdown website.
    -   Examples failed for FlowSum and IonContrib.

# MBSStools v1.1 (2019-06-13)

-   Shiny release version

# MBSStools v1.0.2.9015 (2019-06-13)

-   Shiny app, Issue \#22
    -   Remove link to package vignette (doesn’t work on Shiny.io)

# MBSStools v1.0.2.9014 (2019-06-13)

-   Additional packages to Suggests for the Shiny app, Issue \#22

# MBSStools v1.0.2.9013 (2019-06-13)

-   Complete Shiny app, Issue \#22

# MBSStools v1.0.2.9012 (2019-05-17)

-   README
    -   Update install example to ensure vignettes are installed.

# MBSStools v1.0.2.9011 (2019-05-17)

-   Update for R v3.6.0, Issue \#27
    -   README
        -   Added extra line to make work devtools::install\_github()
    -   DESCRIPTION
        -   Remove StagedInstall: no
-   README
    -   Update badges.

# MBSStools v1.0.2.9010 (2019-05-01)

-   Shiny app development, Issue \#22
    -   Not complete.

# MBSStools v1.0.2.9010 (2019-05-01)

-   Revise for staged install for R v3.6.0, Issue \#27
    -   DESCRIPTION
        -   StagedInstall: no
    -   Temporary fix. Still needs to be installed from a local file.
-   Edits to Shiny App. Issue \#22.
    -   Incomplete.

# MBSStools v1.0.2.9009 (2019-05-01)

-   Revise “EXCLUDE” column in benthic data from “Y” and "" to TRUE and
    FALSE. Issue \#25.
    -   data
        -   taxa\_bugs\_family
        -   taxa\_bugs\_genus, ProcessData had additional issues that
            weren’t present in prior versions.
    -   function; metric.values
        -   Function help text
        -   Example use “MetricName.Other” rather than “Metric” to get
            pertinent metrics.
        -   Replace EXCLUDE!=“Y” with EXCLUDE!=TRUE
-   Vignette
    -   Example for installing a package (line 51) had a typo.
    -   droplevels update for MetricName.Other (line 110, 161, and 187).
    -   Shiny example code, eval=FALSE

# MBSStools v1.0.2.9008 (2019-02-21)

-   Revised scoring thresholds table, per MBSS. Issue \#23.
-   metric.scores.R
    -   Update example code to match the MBSS metric names.
    -   Slight tweaking of QC check for column names.

# MBSStools v1.0.2.9007 (2019-02-12)

-   Shiny app, Issue \#22
-   Include function to launch the Shiny app.
    -   runShiny
    -   Add to Vignette.

# MBSStools v1.0.2.9006 (2017-07-31)

-   metric.scores
    -   Add example of adding narrative to IBI scores. Issue \#21.

# MBSStools v1.0.2.9005 (2017-07-31)

-   DESCRIPTION
    -   Suggests; XLConnect (MBSStools\_vignette.Rmd)
    -   Maintainer; <Erik.Leppo@tetratech.com> (Needed if submit to
        CRAN)
    -   Description; make more verbose. (Needed if submit to CRAN)
    -   Title; remove ending period.
-   NEWS
    -   Restructure. Still not right but has all info now.
    -   Remove planned updates.
-   Shorten long lines.
    -   FlowSum.R
    -   IonContrib.R
    -   MapTaxaObs.R
    -   metric.scores.R
    -   metric.values.R
    -   PHIcalc.R
-   Remove “keywords” (incorrect usage).
    -   FlowSum.R
    -   IonContrib.R
    -   MapTaxaObs.R
    -   metric.scores.R
    -   metric.values.R
    -   PHIcalc.R

# MBSStools v1.0.2.9004 (2017-07-31)

-   .travis.yml
    -   Add TravisCI yml to GitHub directory.
    -   Add TravisCI yml to Rbuildignore.

# MBSStools v1.0.2.9003 (2017-07-30)

-   Add continuous integration (TravisCI) badge to ReadMe.

# MBSStools v1.0.2.9002 (2017-07-25)

-   DESCRIPTION
-   Move dplyr and rgdal from Suggests to Imports
    -   Packages not always loading. Issue \#15 and Issue \#17
-   Modify minimum version of R from 3.3.2 to 3.4.0.
    -   MapTaxaObs did not work in earlier version of R.  
        Updated to v3.4.0 and no issue. Issue \#17.

# MBSStools v1.0.2.9001 (2017-05-11)

-   Issue \#17 with MapTaxaObs
-   Removed extra file in vignette folder.
-   Update Vignette as doesn’t build in check; commented out MapTaxaObs.

# MBSStools v1.0.2.0000 (2017-10-26)

-   Corrected metric.score() \[line 181\] for fish for “HIGHLANDS” was
    incorrectly designated. These sites were not getting a final FIBI
    score.

# MBSStools v1.0.1.0000 (2017-09-26)

-   Update each function’s description and vignette with the packages
    needed for that function to work properly.

-   Update Vignette for a few typos and so shows in final package. Also
    messages=FALSE for XLConnect example.

-   DESCRIPTION. Move rgdal from Depends to Suggests.

-   Fish metric example not working in metric.values(). Issue \#14.
    Extra parameter. Removed and works.

# MBSStools v1.0.0.0000 (2017-09-24)

-   Release version 1.

# MBSStools v0.0.0.9018 (2017-09-24)

-   Add install guide notebook.

-   Tweak vignette.

-   Update Readme.

-   Final version before going to v1.0.0.

-   IonContrib, ensure data input is a data frame.

-   PHI, ensure data input is a data frame.

# MBSStools v0.0.0.9017 (2017-09-20)

-   Update vignette.

-   Fixed example for fish metrics in metric.values(). 20170920.

# MBSStools v0.0.0.9016 (2017-09-19)

-   IonContrib() added barplot example. 20170919.

# MBSStools v0.0.0.9015 (2017-09-13)

-   Fix typo in example for metric.scores(); “Metrics.Bugs.Scores” to
    “Metrics.Bugs.Scores.MBSS”. 20170913.

# MBSStools v0.0.0.9014 (2017-09-09)

-   Added MSW (family) data, values, and scores. 20170909.

# MBSStools v0.0.0.9013 (2017-09-09)

-   Added BIBI.
-   Updated metric names to match those used by MBSS.
-   Updated metric.values() and metric.scores().
-   Updated genus level bug data file.

# MBSStools v0.0.0.9012 (2017-09-08)

-   Add FIBI. 2017-09-05.
-   metric.values.R
-   metric.score.R
-   example data files
-   -raw.scoring.tab and metric adjustment
-   Added dplyr to DESCRIPTION. Needed for metric values and scores.
    20170908
-   Modified -raw.scoring.tab to resolve QC issues with 2016
    data. 20170908.

# MBSStools 0.0.0.9011 (2017-08-22)

-   Updated taxa map data for typo in “no fish observed”. 20170822.

# MBSStools v0.0.0.9010 (2017-07-31)

-   Updated fish data and crosswalk table examples so have more matched
    data. Also update help to remind that data has to be on the first
    worksheet for the Excel file. 20170731.

# MBSStools v0.0.0.9009 (2017-07-28)

-   Updated DESCRIPTION. “Erik” to “Erik W.” and added Matt Ashton as
    data contributor. 20170728.

# MBSStools v0.0.0.9008 (2017-07-21)

-   Added TaxaMapsObs(). Issue \#2. 20170720.

-   Libraries readxl (suggested) and rgdal (required) added to
    DESCRIPTION. Maps won’t generate without rgdal loaded. 20170720.

-   Added example data and GIS files (zipped). 20170721.

# MBSStools v0.0.0.9007 (2017-06-23)

-   Added “LazyData: true” to DESCRIPTION. Data was not being loaded
    properly. Issue \#9. 20170623.

# MBSStools v0.0.0.9006 (2017-06-23)

-   Modified vignette.

-   Modified data-raw Process data R files (wd).

-   Added IonContrib.R

# MBSStools v0.0.0.9005 (2017-06-14)

-   Added vignette for documentation of each function and the library as
    a whole.

# MBSStools v0.0.0.9004 (2017-04-28)

-   Address issues with PHIcalc from testing. Removed extra rows from
    Excel import for data MBSS.PHI. Added line to convert values to
    numeric inside MBSS.PHI. (not complete)

# MBSStools v0.0.0.9003 (2017-04-21)

-   FlowSum(). Added Error Handling for misidentified Channels. Updated
    data MBSS.flow.

# MBSStools v0.0.0.9002 (2017-04-20)

-   Flow sum calculation completed. Included Channel Number as grouping
    variable but sum across channels to get the total site flow.

-   PHI, edit script for outlining in RStudio.

-   PHI.calc() to PHIcalc().

-   Data.R and folder “data-raw”.

-   PHI, tweak for created data. Using Excel to build rda rather than
    txt file from the Excel.

# MBSStools v0.0.0.9001 (2017-03-29)

-   Completed PHI calculation.

# MBSStools v0.0.0.9000 (2017-03-27)

-   Created GitHub repository.

-   Added ReadME.RMD and NEWS.RMD

-   PHI calculation started.
