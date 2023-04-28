# myuw-search versions


## 1.5.6

* Update search input font from 1rem to fixed value of 16px

## 1.5.5

* Fix failing form submission on mobile
* Accessibility fix: add focus style on search button

## 1.5.4

* Adjustments to the position of the Search icon on mobile views

## 1.5.3

* Update web Components imports to use unpkg rather than cdn.my.
* Update position of search icon on mobile view

## 1.5.2

* Fix misaligned position of the icon on mobile views and strengthen the contrast between the background and foreground on hover effect

## 1.5.1

* Added default aria-disabled to Submit Search button
* Added click event listeners for search input
* Inform assistive technologies users when submitting empty search form and when searching begins by adjusting aria-live="assertive"

## 1.5.0

* Added role='search' to the search form
* Added aria-live="assertive" to announce searched activity
* Added mobile style for search input

## 1.3.1

* Added more components to local demo to test mobile search positioning 

## 1.3.0

* Added `myuw-search` CustomEvent that exposes the value in the search field when a search is submitted

## 1.2.4

* Added CSS variable to explicitly set mobile search bar origin position (sets the value of `right`).

## 1.2.3

### Added 

* Responsive theming support

## 1.1.9

### Added

* Now supports setting the `--myuw-search-border` CSS variable to better support theming.

## Changed

* Give search toggle button a margin when form is expanded.

## 1.1.8

This patch adds attribute mirroring so that changes to observed attributes that occur _after_ the initial load are correctly reflected in the component.