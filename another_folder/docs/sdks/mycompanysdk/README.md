# MyCompanySDK

## Overview

FastAPI: stop complaining

### Available Operations

* [read_item_items_item_id_get](#read_item_items_item_id_get) - Read Item

## read_item_items_item_id_get

Read Item

### Example Usage

```python
from my_company_sdk import MyCompanySDK

with MyCompanySDK() as my_company_sdk:

    res = my_company_sdk.read_item_items_item_id_get(random_id=False)

    # Handle response
    print(res)

```

### Parameters

| Parameter                                                           | Type                                                                | Required                                                            | Description                                                         |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- |
| `random_id`                                                         | *bool*                                                              | :heavy_check_mark:                                                  | N/A                                                                 |
| `retries`                                                           | [Optional[utils.RetryConfig]](../../models/utils/retryconfig.md)    | :heavy_minus_sign:                                                  | Configuration to override the default retry behavior of the client. |

### Response

**[Any](../../models/.md)**

### Errors

| Error Type      | Status Code     | Content Type    |
| --------------- | --------------- | --------------- |
| models.APIError | 4XX, 5XX        | \*/\*           |