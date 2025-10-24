# Spryker Glue API

[SprykerBasic.postman_collection.json](SprykerBasic.postman_collection.json) contains API to let you test default Spryker's headless functionality.

In order to test our public [B2B demoshop](https://www.b2b-eu.demo-spryker.com/), please import and activate [B2B demoshop.postman_environment.json](B2B%20demoshop.postman_environment.json)

**Warning**
In B2B context cart items receive special GroupKeys, which are not equal to the product SKU, thus to make update item quantity or delete item call work, you have to replace _{{concrete_product_1}}_ in the _Change qty of a product #1 in the guest cart_ with the actual value.
You can find it in the **Get Cart Contents** response.

In order to test our public [B2C demoshop](https://www.b2c-eu.demo-spryker.com/), please import and activate [B2C demoshop.postman_environment.json](B2C%20demoshop.postman_environment.json)
