# Release Notes

## 2.5 (2015-MM-DD)
This update includes the following changes:

* Use the latest version of the common POM (ets-common-5)
* Add the importElement() and evaluateXQuery() methods to `XMLUtils`


## 2.4 (2015-04-13)
This release includes the following notable changes:

* Use the latest release of the common POM (ets-common-4)
* Add `CommonFixture` (base class that sets up a common test fixture)
* Add `TestFailureListener` (augments a test result with diagnostic information 
in the event that a test method failed)
* Add `ClientUtils` (provides utility methods for using the Jersey client API)

## 2.3 (2015-01-07)
This minor update includes the following changes:

* Use latest release of the common POM (v3).
* Update site documentation.

## 2.2 (2014-10-30)
This update incorporates the following noteworthy changes:

* Don't use TestNG Reporter API in listeners.
* Remove Saxon XPath implementation dependency.
* Configure Maven Release plugin (tagNameFormat).

## 2.1 (2014-08-21)
This minor update incorporates the following changes:

* Use latest parent POM (ets-common-2).
* Add method ValidationUtils#createSchemaResolver.
* Update assembly descriptor (ctl-scripts).

## 2.0 (2014-05-23)
This major release introduces several significant changes:

* Adapt project POM for GitHub hosting.
* Refer to parent POM (org.opengis.cite:ets-common).
* Add site content (also incorporated within the ctl-scripts assembly).
* Move assembly descriptors to standard location.
* Add unit test to verify results produced by TestNGController.
* Change license to Apache License, Version 2.0.

## 1.3 (2014-04-07)
This minor release includes the following updates:

* Refactor or fix various utility methods.
* Amend Javadoc overview, schema catalog.
* Update dependencies (of generated artifact).
