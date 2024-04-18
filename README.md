## Kirby Parcel Starter
- kirby installed through composer for easy updating
- Parcel and PostCSS for JS and CSS asset compiling.

## Setup
- `composer install` to make sure kirby is installed
- `npm install` to load all dependencies
- `npm run dev` for development
- `npm run build` for production

## Notes
- Uses Laravel Valet to make a local dev server.
- No live reloading or hot module replacement
- `/package.json` has scripts for watching and building
- Only one JS and one CSS entry point at the moment. Change that in the scripts.
- Targets last 2 browser versions for compilation.
- Add PostCSS plugins to `/.postcssrc`. Supports CSS nesting, url() and imports currently.
- Includes a bunch of Kirby blueprints and templates

## To-do
- [ ] Clean up blueprints and templates
- [ ] Figure out rsync
- [ ] Find a way to include live reloading and hot module replacement