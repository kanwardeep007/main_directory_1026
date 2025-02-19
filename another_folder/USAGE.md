<!-- Start SDK Example Usage [usage] -->
```python
# Synchronous Example
from my_company_sdk import MyCompanySDK

with MyCompanySDK() as my_company_sdk:

    res = my_company_sdk.read_item_items_item_id_get(random_id=False)

    # Handle response
    print(res)
```

</br>

The same SDK client can also be used to make asychronous requests by importing asyncio.
```python
# Asynchronous Example
import asyncio
from my_company_sdk import MyCompanySDK

async def main():
    async with MyCompanySDK() as my_company_sdk:

        res = await my_company_sdk.read_item_items_item_id_get_async(random_id=False)

        # Handle response
        print(res)

asyncio.run(main())
```
<!-- End SDK Example Usage [usage] -->