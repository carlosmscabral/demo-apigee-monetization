# BQ Data API

Shows an example on how to expose a REST API fronting a Big Query table.
Using HTTP query params such as filter, orderBy and pageSize, this proxy directly maps the "REST dialect" to 
SQL. This proxy also uses Google Authentication, leveraging the IAM permissions of a service account that can
read data from BigQuery, so this connection is made securely. 

## License

All solutions within this repository are provided under the
[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) license.
Please see the [LICENSE](./LICENSE) file for more detailed terms and conditions.

## Not Google Product Clause

This is not an officially supported Google product, nor is it part of an
official Google product.