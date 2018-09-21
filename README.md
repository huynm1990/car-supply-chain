# car-supply-chain
Blockchain project for car supply chain

## Use Case Scenario Overview

### The scenario consists of 4 participants:
* **Manufacturer**: An entity that is selling products
* **Inspector**: An entity that is inspecting products
* **Shipper**: An entity that is shipping products
* **Wholesaler**: An entity that is buying products

### Business
* **Wholesaler** sends a request for buy the products. **Ex: Model=Prime, Color=Green, Number=3**.
* **Manufacturer** accepts the request and manufactures the products. After completed, they send a request to **Inspector** for inspection.
* **Inspector** inspects the products and confirm if they are ok for delievering.
* **Manufacturer** receives confirmation from **Inspector** that all the products are ok to deliver. Then they send a request to **Shipper** for shipping the products to **Wholesaler**.
* **Wholesaler** receives the products, re-checks and confirms they received the products as expected.
* **Wholesaler** gives a payment to **Manufacturer**.
* **Manufacturer** confirms that they received the money.
* The deal is completed. Process is end.

### Network structure
* 4 peers
* 1 orderer
* 5 CAs
