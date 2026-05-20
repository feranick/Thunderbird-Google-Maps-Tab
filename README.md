# Google Maps Tab
Unofficial Google Maps add-on for Thunderbird, it adds a button in Spaces that opens a Google Maps tab in Thunderbird.
The [home page](https://addons.mozilla.org/thunderbird/addon/google-maps-spaces-tab/) of the extension contains the latest code.

#### Installing 
A new Google Maps icon should appear in the Spaces Toolbar of Thunderbird. Click to open.

#### Installing from sources
Download the repository, zip it, rename it to Google-Maps-Tab.xpi and choose install addon from file in Thunderbird.

In linux the xpi file can be created with the following commands
* `git clone https://github.com/feranick/Thunderbird-Google-Maps-Tab`
* `cd ./Thunderbird-Google-Maps-Tab`
* `VERSION=$(cat ./manifest.json | jq --raw-output '.version')`
* `zip -r "../Google-Maps-Tab-${VERSION}-tb.xpi" *`
