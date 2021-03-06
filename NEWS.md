## cancensus 0.1.8

### Major changes
- Remove dependency on development versions of `sf` and `ggplot2` packages
- Add feature allowing for named vector retrieval

### Minor Changes
- Vignette updates
- Calls that retrieve only geography will now return geographic hierarchy information as well
- Small tweaks that make it easier to do 2011-2016 intra-census comparisons

### Bug fixes
- Fix labels when geo format is `sf`
- Remove some unnecessary code for geographic hierarchies

## cancensus 0.1.7

### Major changes 
- Set default caching to `tempdir()`
- Encourage users to set up local persistent caching using `options(cancensus.cache_path = 'XXX')`

## cancensus 0.1.6

### Major changes
- First released on CRAN

### Minor changes
- Ensured that data frames were `sf`-class data frames if option `sf` was selected for spatial data. 

### Bug fixes
- Fixed a bug where `read.csv` was incorrectly loading text data if `readr::read_csv` was not available 

## cancensus 0.1.5

### Major changes
- Added a `NEWS.md` file to track changes to the package.
- Added pkgdown documentation
- New vignettes - _cancensus_ and _Making maps with cancensus_

### Minor changes
- Default behaviour for `list_census_vectors()` changed to have `quiet = TRUE`

## cancensus 0.1.0

### Major changes
- Added vector and geography search and discovery capabilities
- Improved performance
- Error and API issue messaging

### Minor changes
- Reduced package dependencies

## cancensus 0.0.1

### Major changes
- Initial release
