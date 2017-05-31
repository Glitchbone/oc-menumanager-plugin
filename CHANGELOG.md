OctoberCMS Menu Manager Plugin - Change Log
=====================

Old version change log.

### 1.5.1

- Add homepage for plugin details, thanks [@gegor85](https://github.com/gergo85)
- Added a couple of missing translations

### 1.5.0

- Added support for postgres and sqlite by fixing migrations and updating mutator and accessors

### 1.4.8

- Merged PR to fix re-order errors. Thanks [@CptMeatball](https://github.com/CptMeatball)

### 1.4.7

- Merged PR to fix syntax errors with fresh install of 1.4.6. Thanks [@devlifeX](https://github.com/devlifeX)

### 1.4.6

- Merged PRs that fix bug with plugin not working with stable release

### 1.4.5

- Fixed bug where getBaseFileName method was moved to a different object

### 1.4.4

- Fixed bug with incorrect labels. Thanks @ribsousa

### 1.4.3

- Fixed bug where getBaseFileName method was moved to a different object

### 1.4.2

- Fixed bug where url field was not saving. Refactored code to use a Laravel Mutator.

### 1.4.1

- Fixed bug caused by deleting method I shouldn't have. Thanks @MatissJA

### 1.4.0

- Multiple bug fixes due to new features in OctoberCMS
- Ability to translate added
- Ability to add fragments to URL added

### 1.3.4

- JSON validation now works

### 1.3.3

- Fixed typo in JSON help text

### 1.3.2

- Bug fixed where param checking breaks active query. Thanks @alxy

### 1.3.1

- Bug fixed where incorrect active menu was set
- JSON validation of parameters has been added
- Both courtesy of @whsol

### 1.3.0

- Added translations

### 1.2.0

- Added list item classes; Fixed validation and admin bugs

### 1.1.3

- Fixed bug that prevented multiple components showing on the same page

### 1.1.2

- Reformatted admin interface to make more sense (possibly just to me ...)
- Removed CSS and JS partial, and replaced with an asset JS file
- Added escaping to any query string values used on a menu item
- Small updates to text to make more sense
- Reformatted some functions for future enhancements

### 1.1.1

- Added ability to enable/disable individual menu links
- Added ability for url parameters &amp; query string
- Fixed issue of "getLinkHref()" pulling through full page url with parameters rather than the ACTUAL page url
- All these changes are courtesy of [@DanielHitchen](https://github.com/DanielHitchen)

### 1.1.0

- Added ability to link to external sites. Thanks [Adis](https://github.com/adisos)

### 1.0.6

- Removed NestedSetModel
- Added NestedTree trait, thanks @daftspunk
- Fixed bug when no menus set, thanks @danielhitchens

### 1.0.5

- Moved link creation code into the model in preperation for external links coming in 1.1.0
- Brought list item class creation into the model
- Fixed typo with default menu class so it will display as pills

### 1.0.4

- Fixed bug where Nested Set traits needed to be included in the class, introduced by CMS upgrade

### 1.0.3

- Menu items no longer need to link anywhere
- Ensured the active node must always be a child of the parent node

### 1.0.2

- Added active classes to component
- Added ability to select a menu item other than the current page as the active item
- Added ability to control depth of menu

### 1.0.1

- Created backend area to manage menu items
- Created backend area to re-order menu items
- Created component to output menu in a page/partial/layout