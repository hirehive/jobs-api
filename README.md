# HireHive Jobs API

You can use this API to get a paginated list of your company's published jobs. You should use this option if you wish to display jobs on your site in a custom layout/design.

Alternatively you can use our iframe embed option which will also display published jobs on your site and allow candidates to apply directly within the iframe. [Read more information about our iframe integration](https://github.com/hirehive/embed-options/)

### Documentation

Our documentation is generated by Swagger. [View our interactive docs](https://hirehive-testing-account.hirehive.com/api-documentation/)
The subdomain of the request url determines which company the results are returned for. eg `https://{companyname}.hirehive.com/api/v1/jobs`
Your subdomain is usually a url friendly version of your company's name.

### The API has 3 endpoints:

- `/jobs` Get a paginated list of published jobs. Optional parameters to get jobs by country/category and change source for reports
- `/jobs/{jobId}` Get an individual job object
- `/categories` Returns a list of categories and the count of published jobs in that category

### Examples

We have created a collection on codepen.io of examples of using our API.
There is examples of search, grouping by country, grouping by category and various different designs.
If you have any questions or would like an example for a specific use case just ask.
[View examples on codepen.io](https://codepen.io/collection/XEWQqY/)
