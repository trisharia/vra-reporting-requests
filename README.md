# vra-reporting-requests
The Latest Requests Report workflow gathers information regarding completed catalog item requests in a single vRA instance submitted after a given date (or within the last 24 hours if no date is given), then logs the data (e.g. number of successful requests, number of failed requests, and error messages for any failures)

Optionally, sends an email with the data.

Installation:
1) Download com.vmware.pso.vra.reporting.requests.package
2) In the vRealize Orchestrator client, import the package

Execution:
1) In the vRealize Orchestrator client, run the Latest Requests Report workflow
