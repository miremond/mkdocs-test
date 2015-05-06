# Getting started

## Introduction

This documentation gives a technical overview of the Slimpay infrastructure allowing you to perform direct debit, mandate signature and more...

## Slimpay resources

* **Merchant** uses SlimPay EPT to collect signed mandates from its customers and manage its payment orders. The merchant is the creditor in the payment transaction.
* **Customer** or **User** uses the solution to sign a mandate for a specific merchant. He is considered as a debtor in the payment transaction and a customer of the merchant.
* **EPT** stands for Electronic Payment Terminal. SlimPay provides an EPT for mandate signatures and direct debit payments. 

## Sequence diagrams

The merchant installs SlimPay EPT on its web server. The module integrates as easily as a credit card EPT with the merchant systems. 

SlimPay EPT will handle the debiting of customers holding a bank account in Europe. Once a mandate has been signed, SlimPay debits the customer upon request of the merchant. The debited amounts can be paid directly to the merchant's account in the bank of his choice. 

The figure below summarizes the signature process and the relations between Customer/Merchant/SlimPay:

![Screenshot](img/slimpay-flow.png)



## Where do I start?

### Guides

### API

We strongly encourage you to use our official libraries for navigating and using the Slimpay REST API.

#### PHP

Install from source:

    git clone git@github.com:SlimPay/client-api-rest-php.git

#### Node.js

Install with npm:

    npm install xxx

Check out our [Node docs](#) or [view source on Github](https://github.com/SlimPay/client-api-rest-node).

#### Java

Install with Maven:

    <dependency>
      <groupId>com.slimpay</groupId>
      <artifactId>client-api-rest-java</artifactId>
      <version>0.0.1</version>
    </dependency>

Check out our [Java docs](#) or [view source on Github](https://github.com/SlimPay/client-api-rest-java).

## Need help?

Please have a look at our [FAQ](support/faq.md) and [Troubleshooting](support/troubleshooting.md) pages.

