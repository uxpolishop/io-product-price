# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.9.1] - 2020-11-03

## [1.9.0] - 2020-09-22
### Changed
- Hide `Saving` component when `product-summary` is loading.

## [1.8.0] - 2020-09-10
### Added
- `product-seller-name` block.

## [1.7.0] - 2020-09-10
### Added
- `product-spot-price-savings` component

### Removed
- Spot price logic from `product-price-savings` since it was causing "0%" to appear as savings on some stores. 

## [1.6.1] - 2020-09-09
### Removed
- Mocked type definitions from `vtex.product-context` in favor of the actual ones.

## [1.6.0] - 2020-09-04 [YANKED]
### Added
- Calculate discounts based on the Spot Price

## [1.5.3] - 2020-08-04
### Fixed
- Documentation about `product-list-price`.

## [1.5.2] - 2020-08-04
### Fixed
- Add preventions for negative savings.

## [1.5.1] - 2020-08-03
### Added
- `message` prop usage and example on documentation

## [1.5.0] - 2020-07-23
### Added
- `product-installments-list` block.

### Security
- Bump dependencies versions.

## [1.4.0] - 2020-07-22
### Added
- `hasListPrice` on `product-selling-price`.

## [1.3.2] - 2020-06-03
### Fixed
- The blocks won't be rendered if there are no available products.

## [1.3.1] - 2020-06-01
### Fixed
- Improved the `spot-price` documentation to have more details.
- Updated the README.md file with a disclaimer regarding the deprecation of Product Summary Price and Product Price block. 

## [1.3.0] - 2020-05-11
### Added
- More variables that can be interpolated on the components that can change with taxes.

## [1.2.3] - 2020-05-06
### Fixed
- Add message variables to docs.

## [1.2.2] - 2020-04-22
### Fixed
- Missing defaults on `defineMessages`.

## [1.2.1] - 2020-04-15
### Fixed
- Documentation about `spot-price` by adding a link to the document teaching a store how to set it up.

## [1.2.0] - 2020-04-15
### Added
- `SpotPrice` component.

## [1.1.0] - 2020-04-13
### Added
-  `sellingPrice--hasListPrice` handle to the `selling-price` block if there is a `list-price`.

### Security
- Bump dependency versions.

## [1.0.5] - 2020-04-08
### Fixed
- `undefined` check in `Installments`.

## [1.0.4] - 2020-04-08
### Fixed
- `Installments` now renders nothing if there are no installments in a product.

## [1.0.3] - 2020-04-07

## [1.0.2] - 2020-04-06
### Fixed
- Issues causing console errors: FormattedNumber used wrongly on Installments and missing Key on some spans.

## [1.0.1] - 2020-04-02
### Fixed
- Blocks' names on README.

## [1.0.0] - 2020-04-01
### Fixed
- `README.md`.

## [0.5.2] - 2020-03-26
### Fixed
- Some `handlebases` that weren't right.

## [0.5.1] - 2020-03-26
### Changed
- Default messages.

## [0.5.0] - 2020-03-24
### Added
- `ListPriceRange` and `SellingPriceRange` component.

### Changed
- Made `ListPrice` render null if it is the same as `SellingPrice`.

## [0.4.1] - 2020-03-18
### Changed
- Overall refactor.
- Added translation to some ES and PT messages.

## [0.4.0] - 2020-03-17
### Added
- `SellingPrice` component.

## [0.3.0] - 2020-03-11
### Added
- `Installments` component.

## [0.2.0] - 2020-03-10
### Added
- `Savings` component.

## [0.1.0] - 2020-03-03
### Added
- `ListPrice` component.
