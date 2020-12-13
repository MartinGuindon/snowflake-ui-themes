# snowflake-ui-themes
Themes for the Snowflake UI (to be used with a CSS override add-on like Stylebot).

The Snowflake UI is based on the open source [Code Mirror editor](https://codemirror.net/). While Code Mirror has theme support, the themes does not work as-is in Snowflake. So I made a quick adaptation of the Solarized Dark theme for it to work using Stylebot.

#### Solarized Dark Theme
![Screenshot](screenshot.png "Screenshot")

#### Black and White Theme
![Screenshot](screenshot_sf_black_and_white_theme.png "Black and White Theme")

## Dependencies
- A CSS override add-on, such as [Stylebot](https://chrome.google.com/webstore/detail/stylebot/oiaejidbmkiecgbjeifoejpgmdaleoha?hl=en) for Chrome.
- Either the Inconsolata or the Menlo font installed on your system (or customize the CSS to use your favorite coding font).

## Usage
To add the Solarized Dark Theme:
- Copy/paste the styles found in the file snowflake.css in Stylebot (or alternative add-on) and set the custom stylesheet for your Snowflake instance URL.

To add the Black and White Theme:
- Copy/paste the styles found in the file snowflake_black_and_white.css in Stylebot (or alternative add-on) and set the custom stylesheet for your Snowflake instance URL.

## Known Issues
No known issues at this time. Feel free to issue a PR to contribute or create an issue if you find one.

## Change Log

#### 2019-09-09
- Original version.

#### 2020-12-13
- Added black and white theme.
- Added support for Snowflake metadata pane, history pane, and results pane.
