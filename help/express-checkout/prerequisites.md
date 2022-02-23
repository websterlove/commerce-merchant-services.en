---
title: [!DNL Express Checkout] prerequisites
description: Verify that your system meets the requirements necessary to use the [!DNL Express Checkout] for Adobe Commerce extension. 
---

# [!DNL Express Checkout] prerequisites

>[!IMPORTANT]
>
> This feature is for Early Adopter Program (EAP) users only and is not yet accessible for all customers. Currently limited to US customers. Contact Adobe Commerce Support for assistance and questions.

The minimum requirements to use the [!DNL Express Checkout] are:

| **Requirements** | **Constraints** |
|----------------|-----------------|
| PHP version| Depending on the Adobe Commerce instance version >=2.4.3 |
| Composer | Depending on the Adobe Commerce instance version >=2.4.3 |
| Magento Open Source or Adobe Commerce 2.4.3. | none |

Refer to the [onboarding](../express-checkout/onboarding.md) topic for more information.

## Compatibility issues

The [!DNL Express Checkout] has existing compatibility issues for the EAP program (EAP):

| **Issue** | **Constraints** |
|----------------|-----------------|
| US only| This feature is only available for US customers |
| USD only| USD is the only compatible currency |
| Amazon Pay | Amazon Pay is not compatible with Adobe Commerce versions >=2.4.3 |
| PWA Studio and headless deployments | Customers MUST use the Luma-based coupled storefront. PWA Studio and headless deployments are not supported during |
| 3D Secure | 3D Secure is not supported |
| B2B | B2B Secure is not supported |
| ISPU | In-Store Pickup (ISPU) functionality is not supported |
| Multishipping | Multishipping is not supported |