# Template - HTTP Client

[![Eclipse License](http://img.shields.io/badge/license-Eclipse-brightgreen.svg)](LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/dirigiblelabs/template-v3-http-client.svg)](https://github.com/dirigiblelabs/template-v3-http-client/graphs/contributors)

## Overview

Simple "HTTP Client" JavaScript service
```javascript
var httpClient = require('http/v3/client');
var response = require('http/v3/response');

var httpResponse = httpClient.get('http://services.odata.org/V4/Northwind/Northwind.svc/');

response.println(httpResponse.text);
response.flush();
response.close();
```


## License

This project is copyrighted by [SAP SE](http://www.sap.com/) and is available under the [Eclipse Public License v 2.0](https://www.eclipse.org/legal/epl-v20.html). See [LICENSE](LICENSE) and [NOTICE.txt](NOTICE.txt) for further details.
