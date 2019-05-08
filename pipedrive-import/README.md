# Pipedrive-import connector

This plugin provides a read connector to interact with [Pipedrive CRM](https://www.pipedrive.com) in [Dataiku Data Science Studio](http://www.dataiku.com/dss/). You can import deals, contacts and organizations.

## How to set-up

* Get a Pipedrive API key.
* Install the plugin in DSS.
* Create a new dataset with this connector. Fill the API key field and click on the “Test & Get schema“ button. Then, “save“ and “explore“.

## Changelog

**Version 1.0.1 (2016-02-02)**

* Change dependency (unidecode is an optional dependency, no more dependency)

**Version 1.0.0 (2016-01-12)**

* Easier installation (awesome-slugify dependency now packaged in the plugin)
* Dates are automatically parsed
* Display the Pipedrive API error if there is one

**Version 0.9.1 "beta" (2015-11-13)**

* Small fixes and cleaning -> ready for DSS 2.2.0

**Version 0.9.0 "beta" (2015-11-06)**

* New datasets: people and organizations
* Deals datasets renamed -> compatibility broken with 0.0.1
* Columns names are now suglified

**Version 0.0.1 "alpha" (2015-10-02)**

* Initial release: deals dataset

## Non-Roman characters

This plugin optionnaly uses the [unidecode](https://pypi.python.org/pypi/Unidecode) library from Tomaz Solc for the transliteration of non-Roman characters.

You can install this package if required with the [pip of the DSS virtualenv](http://learn.dataiku.com/howto/code/python/install-python-packages.html):

`data_dir/bin/pip install --upgrade unidecode`

## Need help?

Find out more on the [plugin page](https://www.dataiku.com/dss/plugins/info/pipedrive.html) on Dataiku's website.

Ask your question on [answers.dataiku.com](https://answers.dataiku.com). Or, [open an issue](https://github.com/dataiku/dataiku-contrib/issues).
