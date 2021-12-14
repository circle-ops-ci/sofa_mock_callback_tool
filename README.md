# Overview

- The tool uses [Postman](https://learning.postman.com/) as the underlying platform to facilitate the integration of SOFA API callbacks. It simulates the callback data sent from the SOFA API server.

# How to use

- Import the Postman collection from the following button.

	[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/648921209724ab38f951?action=collection%2Fimport)

- Download the callback [data template JSON file](https://github.com/CYBAVO/SOFA_MOCK_CALLBACK_TOOL/blob/master/template/mock-callback-data-template.json).

- Fill up the `callback_url`, `api_code` and `api_secret` with the test data.

- Run the Postman collection with data file.

> Refer to the official Postman [document](https://learning.postman.com/docs/running-collections/working-with-data-files/) to learn how to run collections with data files.