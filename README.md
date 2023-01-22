# IntelligentFridge-wiki

```mermaid
  graph TD;
      user-->application;
      application-->introduce_product;
      introduce_product-->supermarket_API
      application-->list_products;
      application-->delete_products;
      application-->edit_products;
```

```mermaid
  graph TD;
      API_server<-->database;
      API_server<-->frontend;
      API_server<-->supermarket_API;
      API_server<-->esp32;
      esp32<-->barcode_reader;
```
