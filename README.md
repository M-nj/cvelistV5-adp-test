#### This branch of the adp-test data contains corrections for the date fields affected by the known issue:
> 1. **Added 3/28/2023:** CVE Records published prior to 2023 may have significant publication, reserved, and update date discrepancies. As a result, this repository should not be used for CVE production metrics at this time. A fix will be forthcoming.

---------

The following CVE Ids are in need of date field changes, but have other issues preventing them from being updated with the framework.

Issues: original data does not validate against schema validation:

{'CVE-2018-1890', 'CVE-2018-1495', 'CVE-2018-1822', 'CVE-2019-4036', 'CVE-2018-12480'}
