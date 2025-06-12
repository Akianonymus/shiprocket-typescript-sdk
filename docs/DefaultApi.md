# DefaultApi

All URIs are relative to *https://apiv2.shiprocket.in*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**createCustomerOrder**](#createcustomerorder) | **POST** /v1/external/orders/create/adhoc | Create Custom Order |
|[**generateToken**](#generatetoken) | **POST** /v1/external/auth/login | Generate Token|
|[**getAllOrders**](#getallorders) | **GET** /v1/external/orders | Get all Orders|
|[**getAllReturnOrders**](#getallreturnorders) | **GET** /v1/external/orders/processing/return | Get All Return Orders|
|[**getRemittanceInfo**](#getremittanceinfo) | **GET** /v1/external/account/details/remittance | Get Remittence Info|
|[**getSpecificOrderDetails**](#getspecificorderdetails) | **GET** /v1/external/orders/show/{id} | Get Specific Order Details|
|[**getSpecificShipmentDetails**](#getspecificshipmentdetails) | **GET** /v1/external/shipments | Get Details of Specific Shipment|
|[**getWalletBalance**](#getwalletbalance) | **GET** /v1/external/account/details/wallet-balance | Get Wallet Balance|
|[**logout**](#logout) | **POST** /v1/external/auth/logout | Token Logout|
|[**search**](#search) | **GET** /v1/global/search | Global Search|
|[**v1ExternalAccountDetailsStatementGet**](#v1externalaccountdetailsstatementget) | **GET** /v1/external/account/details/statement | Get Statement Details|
|[**v1ExternalBillingDiscrepancyGet**](#v1externalbillingdiscrepancyget) | **GET** /v1/external/billing/discrepancy | Get Dicrepancy Data|
|[**v1ExternalChannelsGet**](#v1externalchannelsget) | **GET** /v1/external/channels | Get Integrated Channel Details|
|[**v1ExternalCountriesGet**](#v1externalcountriesget) | **GET** /v1/external/countries | Get Country Codes|
|[**v1ExternalCountriesShowCountryIdGet**](#v1externalcountriesshowcountryidget) | **GET** /v1/external/countries/show/{country_id} | Get All Zones|
|[**v1ExternalCourierAssignAwbPost**](#v1externalcourierassignawbpost) | **POST** /v1/external/courier/assign/awb | Generate AWB for Return Shipment|
|[**v1ExternalCourierCourierListWithCountsGet**](#v1externalcouriercourierlistwithcountsget) | **GET** /v1/external/courier/courierListWithCounts | List of Couriers|
|[**v1ExternalCourierGenerateLabelPost**](#v1externalcouriergeneratelabelpost) | **POST** /v1/external/courier/generate/label | Generate Label|
|[**v1ExternalCourierGeneratePickupPost**](#v1externalcouriergeneratepickuppost) | **POST** /v1/external/courier/generate/pickup | Generate Pickup|
|[**v1ExternalCourierServiceabilityGet**](#v1externalcourierserviceabilityget) | **GET** /v1/external/courier/serviceability/ | Check Courier Serviceability|
|[**v1ExternalCourierTrackAwbAwbCodeGet**](#v1externalcouriertrackawbawbcodeget) | **GET** /v1/external/courier/track/awb/{awb_code} | Get Tracking through AWB|
|[**v1ExternalCourierTrackAwbsPost**](#v1externalcouriertrackawbspost) | **POST** /v1/external/courier/track/awbs | Get Tracking Data for Multiple AWBS|
|[**v1ExternalCourierTrackGet**](#v1externalcouriertrackget) | **GET** /v1/external/courier/track | Get Tracking Data through Order iD|
|[**v1ExternalCourierTrackShipmentShipmentIdGet**](#v1externalcouriertrackshipmentshipmentidget) | **GET** /v1/external/courier/track/shipment/{shipment_id} | Get Tracking through Shipment ID|
|[**v1ExternalErrorsImportIdCheckGet**](#v1externalerrorsimportidcheckget) | **GET** /v1/external/errors/{import_id}/check | Get File import Results|
|[**v1ExternalInternationalCourierAssignAwbPost**](#v1externalinternationalcourierassignawbpost) | **POST** /v1/external/international/courier/assign/awb | AWB Assignment|
|[**v1ExternalInternationalCourierServiceabilityGet**](#v1externalinternationalcourierserviceabilityget) | **GET** /v1/external/international/courier/serviceability | Serviceability|
|[**v1ExternalInternationalManifestsGeneratePost**](#v1externalinternationalmanifestsgeneratepost) | **POST** /v1/external/international/manifests/generate | Manifest Generation|
|[**v1ExternalInternationalOrdersCreateAdhocPost**](#v1externalinternationalorderscreateadhocpost) | **POST** /v1/external/international/orders/create/adhoc | Create order|
|[**v1ExternalInternationalOrdersTrackGet**](#v1externalinternationalorderstrackget) | **GET** /v1/external/international/orders/track | Tracking|
|[**v1ExternalInternationalOrdersUpdateAdhocPost**](#v1externalinternationalordersupdateadhocpost) | **POST** /v1/external/international/orders/update/adhoc | Update order|
|[**v1ExternalInternationalSettingsAddBankDetailsPost**](#v1externalinternationalsettingsaddbankdetailspost) | **POST** /v1/external/international/settings/add-bank-details | Add Bank Details|
|[**v1ExternalInternationalSettingsInternationalKycPost**](#v1externalinternationalsettingsinternationalkycpost) | **POST** /v1/external/international/settings/international_kyc | International KYC|
|[**v1ExternalInternationalShipmentsCreateForwardShipmentPost**](#v1externalinternationalshipmentscreateforwardshipmentpost) | **POST** /v1/external/international/shipments/create/forward-shipment | International Wrapper API|
|[**v1ExternalInventoryGet**](#v1externalinventoryget) | **GET** /v1/external/inventory | Get Inventory Details|
|[**v1ExternalInventoryProductIdUpdatePut**](#v1externalinventoryproductidupdateput) | **PUT** /v1/external/inventory/{product_id}/update | Update Your Inventory |
|[**v1ExternalListingsExportMappedGet**](#v1externallistingsexportmappedget) | **GET** /v1/external/listings/export/mapped | Export Mapped Products|
|[**v1ExternalListingsExportUnmappedGet**](#v1externallistingsexportunmappedget) | **GET** /v1/external/listings/export/unmapped | Export Unmapped Products|
|[**v1ExternalListingsGet**](#v1externallistingsget) | **GET** /v1/external/listings | Get All  Listings|
|[**v1ExternalListingsImportPost**](#v1externallistingsimportpost) | **POST** /v1/external/listings/import | Import Catalog Mappings|
|[**v1ExternalListingsLinkPost**](#v1externallistingslinkpost) | **POST** /v1/external/listings/link | Map Channel Product|
|[**v1ExternalListingsSampleGet**](#v1externallistingssampleget) | **GET** /v1/external/listings/sample | Export Catalog Sample|
|[**v1ExternalManifestsGeneratePost**](#v1externalmanifestsgeneratepost) | **POST** /v1/external/manifests/generate | Generate Manifest|
|[**v1ExternalManifestsPrintPost**](#v1externalmanifestsprintpost) | **POST** /v1/external/manifests/print | Print Manifest|
|[**v1ExternalNdrAWBGet**](#v1externalndrawbget) | **GET** /v1/external/ndr/{AWB} | Get Specific NDR Shipment Details|
|[**v1ExternalNdrAllGet**](#v1externalndrallget) | **GET** /v1/external/ndr/all | Get All NDR Shipments|
|[**v1ExternalNdrAwbActionPost**](#v1externalndrawbactionpost) | **POST** /v1/external/ndr/{awb}/action | Action NDR|
|[**v1ExternalOpenPostcodeDetailsGet**](#v1externalopenpostcodedetailsget) | **GET** /v1/external/open/postcode/details | Get Locality Details|
|[**v1ExternalOrdersAddressPickupPatch**](#v1externalordersaddresspickuppatch) | **PATCH** /v1/external/orders/address/pickup | Change/Update Pickup Location of Created Orders|
|[**v1ExternalOrdersAddressUpdatePost**](#v1externalordersaddressupdatepost) | **POST** /v1/external/orders/address/update | Update Customer Delivery Address|
|[**v1ExternalOrdersCancelPost**](#v1externalorderscancelpost) | **POST** /v1/external/orders/cancel | Cancel an Order|
|[**v1ExternalOrdersCancelShipmentAwbsPost**](#v1externalorderscancelshipmentawbspost) | **POST** /v1/external/orders/cancel/shipment/awbs | Cancel a Shipment|
|[**v1ExternalOrdersCreateExchangePost**](#v1externalorderscreateexchangepost) | **POST** /v1/external/orders/create/exchange | Create Exchange Order|
|[**v1ExternalOrdersCreatePost**](#v1externalorderscreatepost) | **POST** /v1/external/orders/create | Create Channel Specific Order|
|[**v1ExternalOrdersCreateReturnPost**](#v1externalorderscreatereturnpost) | **POST** /v1/external/orders/create/return | Create a Return Order|
|[**v1ExternalOrdersEditPost**](#v1externalorderseditpost) | **POST** /v1/external/orders/edit | Update Return Order|
|[**v1ExternalOrdersExportPost**](#v1externalordersexportpost) | **POST** /v1/external/orders/export | Export your orders|
|[**v1ExternalOrdersFulfillPatch**](#v1externalordersfulfillpatch) | **PATCH** /v1/external/orders/fulfill | Add Inventory for Ordered Product|
|[**v1ExternalOrdersImportPost**](#v1externalordersimportpost) | **POST** /v1/external/orders/import | Import Orders in Bulk|
|[**v1ExternalOrdersMappingPatch**](#v1externalordersmappingpatch) | **PATCH** /v1/external/orders/mapping | Map Unmapped Products|
|[**v1ExternalOrdersPrintInvoicePost**](#v1externalordersprintinvoicepost) | **POST** /v1/external/orders/print/invoice | Generate Invoice|
|[**v1ExternalOrdersUpdateAdhocPost**](#v1externalordersupdateadhocpost) | **POST** /v1/external/orders/update/adhoc | Update Order|
|[**v1ExternalProductsGet**](#v1externalproductsget) | **GET** /v1/external/products | Get All Products|
|[**v1ExternalProductsImportPost**](#v1externalproductsimportpost) | **POST** /v1/external/products/import | Bulk Import Products|
|[**v1ExternalProductsPost**](#v1externalproductspost) | **POST** /v1/external/products | Add New Products|
|[**v1ExternalProductsQcProductUpdateProductIDPost**](#v1externalproductsqcproductupdateproductidpost) | **POST** /v1/external/products/qc-product-update/{productID} | Convert to QC Product|
|[**v1ExternalProductsSampleGet**](#v1externalproductssampleget) | **GET** /v1/external/products/sample | Get Sample .csv Format|
|[**v1ExternalProductsShowProductIdGet**](#v1externalproductsshowproductidget) | **GET** /v1/external/products/show/{product_id} | Get Specific Product Details|
|[**v1ExternalSettingsCompanyAddpickupPost**](#v1externalsettingscompanyaddpickuppost) | **POST** /v1/external/settings/company/addpickup | Add a New Pickup Location|
|[**v1ExternalSettingsCompanyPickupGet**](#v1externalsettingscompanypickupget) | **GET** /v1/external/settings/company/pickup | Get All Pickup  Locations|
|[**v1ExternalShipmentsCreateForwardShipmentPost**](#v1externalshipmentscreateforwardshipmentpost) | **POST** /v1/external/shipments/create/forward-shipment | Forward|
|[**v1ExternalShipmentsCreateReturnShipmentPost**](#v1externalshipmentscreatereturnshipmentpost) | **POST** /v1/external/shipments/create/return-shipment | Return|

# **createCustomerOrder**
> CreateCustomerOrder200Response createCustomerOrder()

Use this API to create a quick custom order. Quick orders are the ones where we do not store the product details in the master catalogue.  You have to pass all the required params at the minimum to create a quick custom order. You can add additional parameters as per your preference.  **Note:**  - In case the \'shipping_is_billing\' field is false, further shipping detail fields are required.       If no channel id is passed, the order will be assigned to the default custom channel. If the channel id is not known, use the \'Get All Channels\' API to get the list of all integrated channels in your Shiprocket account.  - order_id field cannot be equal to an already existing id. Doing so does not change or affect the existing order.      - New orders cannot be created with order id\'s same as that of cancelled orders. If error 422 shows up despite filling in the correct details, consider changing the order_id.      - Be sure to input the correct calculated sub_total amount. The total is not calculated automatically through the API.      - The \'order_id\' returned in the response is the Shiprocket order_id. Please save this order ID as we will use this in future API calls.       #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `order_id` | YES | _string_ | The order id you want to specify to the order. Max char: 50. (Avoid passing character values as this contradicts some other API calls). | 224477 or 224-477 | | `order_date` | YES | _string_ | The date of order creation in yyyy-mm-dd format. Time is additional. | 2019-07-24 11:11 | | `pickup_location` | YES | _string_ | The name of the pickup location added in your Shiprocket account. This cannot be a new location. | Jammu | | `channel_id` | NO | _integer_ | Mention this in case you need to assign the order to a particular channel. Default is \'Custom\'. | 27022 | | `comment` | NO | _string_ | Option to add \'From\' field to the shipment. To do this, enter the name in the following format: \'Reseller: \\[name\\]\'. | Reseller: Divine | | `reseller_name` | NO | _string_ | The \'from\' name if you want to print. Use \'Reseller: \\[name\\]\' | Reseller: Divine | | `company_name` | NO | _string_ | Name of the company. | Amazon | | `billing_customer_name` | YES | _string_ | First name of the billed customer. | John | | `billing_last_name` | NO | _string_ | Last name of the billed customer. | Doe | | `billing_address` | YES | _string_ | address details of the billed customer. | Civil line, House 20 | | `billing_address_2` | NO | _string_ | Further address details of the billed customer. | Near Hokage House | | `billing_city` | YES | _string_ | Billing address city. Max char: 30. | New Delhi | | `billing_pincode` | YES | _integer_ | Pincode of the billing address. | 110002 | | `billing_state` | YES | _string_ | Billing address state. | Delhi | | `billing_country` | YES | _string_ | Billing address country. | India | | `billing_email` | YES | _string_ | Email address of the billed customer. | [John@doe.com](https://mailto:John@doe.com) | | `billing_phone` | YES | _integer_ | The phone number of the billing customer. | 9856321472 | | `billing_alternate_phone` | NO | _integer_ | Alternate phone number of the billing customer. | 8604690454 | | `shipping_is_billing` | YES | _boolean_ | Whether the shipping address is the same as billing address. 1 or \'true\' for yes and 0 or \'false\' for no. | true | | `shipping_customer_name` | CONDITIONAL YES | _string_ | Name of the customer the order is shipped to. Required in case billing is not same as shipping. | Jane | | `shipping_last_name` | NO | _string_ | Last name of the shipping customer. | Doe | | `shipping_address` | CONDITIONAL YES | _string_ | Address of the Shipping customer. Required in case billing is not same as shipping. | Lane number 69 | | `shipping_address_2` | NO | _string_ | Further address details of shipping customer. | Andheri | | `billing_isd_code` | NO | _string_ | ISD code of the billing address. | +91 | | `shipping_city` | CONDITIONAL YES | _string_ | Shipping address city. | Mumbai | | `shipping_pincode` | CONDITIONAL YES | _integer_ | Shipping address pincode. | 200912 | | `shipping_country` | CONDITIONAL YES | _string_ | Shipping address country. | India | | `shipping_state` | CONDITIONAL YES | _string_ | Shipping address state. | Maharashtra | | `shipping_email` | NO | _string_ | Email of the shipping customer. | [Jane@doe.com](https://mailto:Jane@doe.com) | | `shipping_phone` | CONDITIONAL YES | _integer_ | Phone no. of the shipping customer. |  | | `longitude` | NO | _float_ | Destination (Shipping address) Longitude. | 69.0747 | | `latitude` | NO | _float_ | Destination (Shipping address) Latitude | 22.4064 | | `order_items` | YES | / | List of items and their relevant fields in the form of Array. | / | | `name` | YES | _string_ | Name of the product. | Jeans | | `sku` | YES | _string_ | The sku id of the product. | cbs123 | | `units` | YES | _integer_ | No of units that are to be shipped. | 10 | | `selling_price` | YES | _integer_ | The selling price per unit in Rupee. Inclusive of GST. | 900 | | `discount` | NO | _integer_ | The discount amount in Rupee. Inclusive of tax. | 10 | | `tax` | NO | _integer_ | The tax percentage on the item. | 5 | | `hsn` | NO | _integer_ | Harmonised System Nomenclature code. Used to determine the category of taxation the goods fall under. | 44122 | | `payment_method` | YES | _string_ | The method of payment. Can be either COD (Cash on delivery) Or Prepaid. | COD | | `shipping_charges` | NO | _integer_ | Shipping charges if any in Rupee. | 5 | | `giftwrap_charges` | NO | _integer_ | Giftwrap charges if any in Rupee. | 5 | | `transaction_charges` | NO | _integer_ | Transaction charges if any in Rupee. | 5 | | `total_discount` | NO | _integer_ | The total discount amount in Rupee. | 15 | | `sub_total` | YES | _integer_ | Calculated sub total amount in Rupee after deductions. | 9010 | | `length` | YES | _float_ | The length of the item in cms. Must be more than 0.5. | 10 | | `breadth` | YES | _float_ | The breadth of the item in cms. Must be more than 0.5. | 10 | | `height` | YES | _float_ | The height of the item in cms. Must be more than 0.5. | 10 | | `weight` | YES | _float_ | The weight of the item in kgs. Must be more than 0. | 2.5 | | `ewaybill_no` | NO | _string_ | Details relating to the shipment of goods. . | K92373490 | | `customer_gstin` | NO | _string_ | Goods and Services Tax Identification Number. | 29ABCDE1234F2Z5 | | `invoice_number` | NO | _string_ |  |  | | `order_type` | NO | _string_ | Key to differentiate between Essentials or Non Essentials Shipments. Order type can only be ESSENTIALS or NON ESSENTIALS. Please note it is case sensitive and blank values are allowed. | ESSENTIALS | | `checkout_shipping_method` | NO | _string_ | Only for SRF users. | a. SR_RUSH: SDD, NDD  <br>b. SR_STANDARD: Surface Delivery  <br>c. SR_EXPRESS: Air Delivery  <br>d. SR_QUICK: 3 hrs delivery | | `what3words_address` | NO | _string_ | What3words is a proprietary geocode system designed to identify any location on the surface of Earth with a resolution of about 3 meters. The system encodes geographic coordinates into three permanently fixed dictionary words. | toddler.geologist.animated | | `is_insurance_opt` | NO | _boolean_ | To secure shipments above the order value of Rs 2500 | true | | `is_document` | NO | _integer_ | To create a document order | 1 or 0 | | `order_tag` | NO | _string_ | To add tags to your orders | abc, xyz | | `is_insurance_opt` | NO | _boolean_ | To opt in or out of insurance | true or false |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.createCustomerOrder(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**CreateCustomerOrder200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |
|**422** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **generateToken**
> GenerateToken200Response generateToken()



### Example

```typescript
import {
    DefaultApi,
    Configuration,
    GenerateTokenRequest
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let generateTokenRequest: GenerateTokenRequest; // (optional)

const { status, data } = await apiInstance.generateToken(
    generateTokenRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **generateTokenRequest** | **GenerateTokenRequest**|  | |


### Return type

**GenerateToken200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**403** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getAllOrders**
> GetAllOrders200Response getAllOrders()

This API call will display a list of all created and available orders in your Shiprocket account. The product and shipment details are displayed as sub-arrays within each order detail.  You can also sort and filter the data according to your needs by passing the optional parameters. Not passing anything will display the data in the default format.  You can also fetch the data based on the order update date. PFB the validations:  ``` 1. if updated_to => passed and updated_from not passed =>, error will come => Please send update_from date along with update_to date 2. if updated_from => passed and updated_to => paased => and from-to > 30 then error => Difference between updated_from and update_to date should not be greater than 30 days. 3. if updated_From < 30 then error => Updated_from date should not be less than 30 days from current date   ```  #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `page` | NO | _integer_ | The page number to display. | 5 | | `per_page` | NO | _integer_ | The number of entries per page. | 5 | | `sort` | NO | _string_ | Sort conditions: ASC or DESC | ASC | | `sort_by` | NO | _string_ | The Field to sort by: id or status | id | | `to` | NO | _string_ | The end date. | 2018-07-24 | | `from` | NO | _string_ | The start date. | 2019-07-24 | | `filter_by` | NO | _string_ | Field to filter by. | status, payment_method, delivery_country, channel_order_id | | `filter` | NO | _string_ | Value of the field |  | | `search` | NO | _string_ | Search for AWB or by Channel order_id (order id specified by you). | 224477 | | `pickup_location` | NO | _string_ | Search Orders on the basis of pickup location. | xyz | | `channel_id` | NO | _integer_ | Channel ID Returned in Get Integrated Channels API | 123 | | `fbs` | NO | _integer_ | Use this filter if you want to view and filter the SRF orders | 0 or 1 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let sort: string; //Sort conditions. (optional) (default to undefined)
let sortBy: string; //The field to sort by. (optional) (default to undefined)
let to: string; //The end date. (optional) (default to undefined)
let from: string; //The start date. (optional) (default to undefined)
let filterBy: string; //Field to filter by. (optional) (default to undefined)
let filter: string; //(Used with filter_by) — value to filter by. (optional) (default to undefined)
let search: string; //Search by AWB or channel_order_id (your order ID). (optional) (default to undefined)
let pickupLocation: string; //Search orders based on pickup location. (optional) (default to undefined)
let channelId: number; //Channel ID returned from Get Integrated Channels API. (optional) (default to undefined)
let page: number; //Page Number (optional) (default to undefined)
let perPage: number; //No of records in a single requests (optional) (default to undefined)

const { status, data } = await apiInstance.getAllOrders(
    sort,
    sortBy,
    to,
    from,
    filterBy,
    filter,
    search,
    pickupLocation,
    channelId,
    page,
    perPage
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **sort** | [**string**] | Sort conditions. | (optional) defaults to undefined|
| **sortBy** | [**string**] | The field to sort by. | (optional) defaults to undefined|
| **to** | [**string**] | The end date. | (optional) defaults to undefined|
| **from** | [**string**] | The start date. | (optional) defaults to undefined|
| **filterBy** | [**string**] | Field to filter by. | (optional) defaults to undefined|
| **filter** | [**string**] | (Used with filter_by) — value to filter by. | (optional) defaults to undefined|
| **search** | [**string**] | Search by AWB or channel_order_id (your order ID). | (optional) defaults to undefined|
| **pickupLocation** | [**string**] | Search orders based on pickup location. | (optional) defaults to undefined|
| **channelId** | [**number**] | Channel ID returned from Get Integrated Channels API. | (optional) defaults to undefined|
| **page** | [**number**] | Page Number | (optional) defaults to undefined|
| **perPage** | [**number**] | No of records in a single requests | (optional) defaults to undefined|


### Return type

**GetAllOrders200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getAllReturnOrders**
> GetAllReturnOrders200Response getAllReturnOrders()

Using this API, you can get a list of all created return orders in your Shiprocket account, along with their details.  No parameters are required to use the API. However, further parameters can be defined to sort and filter the data.  #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `page` | NO | _integer_ | The page number to display. | 1 | | `per_page` | NO | _integer_ | The number of orders per page. | 2 | | `to` | NO | _string_ | Ending date of search. | 2019-08-04 | | `from` | NO | _string_ | Starting date of search. | 2019-08-05 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let authorization: string; // (default to undefined)
let sort: string; //Sort conditions. (optional) (default to undefined)
let sortBy: string; //The field to sort by. (optional) (default to undefined)
let to: string; //The end date. (optional) (default to undefined)
let from: string; //The start date. (optional) (default to undefined)
let filterBy: string; //Field to filter by. (optional) (default to undefined)
let filter: string; //(Used with filter_by) — value to filter by. (optional) (default to undefined)
let search: string; //Search by AWB or channel_order_id (your order ID). (optional) (default to undefined)
let pickupLocation: string; //Search orders based on pickup location. (optional) (default to undefined)
let channelId: number; //Channel ID returned from Get Integrated Channels API. (optional) (default to undefined)
let page: number; //Page Number (optional) (default to undefined)
let perPage: number; //No of records in a single requests (optional) (default to undefined)

const { status, data } = await apiInstance.getAllReturnOrders(
    authorization,
    sort,
    sortBy,
    to,
    from,
    filterBy,
    filter,
    search,
    pickupLocation,
    channelId,
    page,
    perPage
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **authorization** | [**string**] |  | defaults to undefined|
| **sort** | [**string**] | Sort conditions. | (optional) defaults to undefined|
| **sortBy** | [**string**] | The field to sort by. | (optional) defaults to undefined|
| **to** | [**string**] | The end date. | (optional) defaults to undefined|
| **from** | [**string**] | The start date. | (optional) defaults to undefined|
| **filterBy** | [**string**] | Field to filter by. | (optional) defaults to undefined|
| **filter** | [**string**] | (Used with filter_by) — value to filter by. | (optional) defaults to undefined|
| **search** | [**string**] | Search by AWB or channel_order_id (your order ID). | (optional) defaults to undefined|
| **pickupLocation** | [**string**] | Search orders based on pickup location. | (optional) defaults to undefined|
| **channelId** | [**number**] | Channel ID returned from Get Integrated Channels API. | (optional) defaults to undefined|
| **page** | [**number**] | Page Number | (optional) defaults to undefined|
| **perPage** | [**number**] | No of records in a single requests | (optional) defaults to undefined|


### Return type

**GetAllReturnOrders200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRemittanceInfo**
> GetRemittanceInfo200Response getRemittanceInfo()

Use this API to get the Remittance details of your Shiprocket account.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let from: string; // (optional) (default to undefined)
let to: string; // (optional) (default to undefined)
let page: number; //Page Number (optional) (default to undefined)
let perPage: number; //No of records in a single requests (optional) (default to undefined)

const { status, data } = await apiInstance.getRemittanceInfo(
    from,
    to,
    page,
    perPage
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **from** | [**string**] |  | (optional) defaults to undefined|
| **to** | [**string**] |  | (optional) defaults to undefined|
| **page** | [**number**] | Page Number | (optional) defaults to undefined|
| **perPage** | [**number**] | No of records in a single requests | (optional) defaults to undefined|


### Return type

**GetRemittanceInfo200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getSpecificOrderDetails**
> GetSpecificOrderDetails200Response getSpecificOrderDetails()

Get the order and shipment details of a particular order through this API by passing the Shiprocket order_id in the endpoint URL itself — type in your order_id in place of {id}.  No other body parameters are required.  **Note:**  For SRF orders, you\'ll receive an extra parameter viz., fulfillment_status. This key will have four values:  *   Ready to Pack,  *   Packed *   Added to Picklist *   Picked up         #### Path:  | **EXAMPLE** | | --- | | [https://apiv2.shiprocket.in/v1/external/orders/show/16167171](https://apiv2.shiprocket.in/v1/external/orders/show/16167171) |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: string; // (default to undefined)

const { status, data } = await apiInstance.getSpecificOrderDetails(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**string**] |  | defaults to undefined|


### Return type

**GetSpecificOrderDetails200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getSpecificShipmentDetails**
> GetSpecificShipmentDetails200Response getSpecificShipmentDetails()

Get the details of a specific Shipment by passing the value of shipment_id in the endpoint URL. No other body parameters are required.  #### Path:  |          **EXAMPLE**          | |:----------------------------: | |  https://apiv2.shiprocket.in/v1/external/shipments/16016920  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.getSpecificShipmentDetails(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**GetSpecificShipmentDetails200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getWalletBalance**
> GetWalletBalance200Response getWalletBalance()

Use this API to get the Wallet balance details of your Shiprocket account. No parameters are required to access this API.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.getWalletBalance(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**GetWalletBalance200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **logout**
> object logout()

[https://apiv2.shiprocket.in/v1/external/auth/logout](https://apiv2.shiprocket.in/v1/external/auth/logout)

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.logout();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**object**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **search**
> Search200Response search()



### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let queryString: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.search(
    queryString
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **queryString** | [**string**] |  | (optional) defaults to undefined|


### Return type

**Search200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalAccountDetailsStatementGet**
> V1ExternalAccountDetailsStatementGet200Response v1ExternalAccountDetailsStatementGet()

Use this API to get the account statement details of your Shiprocket account. No parameters are required to access this API. However, you sort and filter the data displayed using the optional parameters.  #### Parameters:  | **PARAMS**  | **REQUIRED**  |  **DATA TYPE**  |              **DESCRIPTION**              | **EXAMPLE**  | |:----------: |:------------: |:--------------: |:----------------------------------------: |:-----------: | |   ` page`     |      NO       |    *integer*    |   The page number you want to display.    |      5       | | `per_page`  |      NO       |    *integer*    | The number of orders to get per request.  |      2       | |    `from`     |      NO       |    *string*     |           From a specific date.           |  2017-08-12  | |     `to`      |      NO       |    *string*     |            To a specific date.            |  2017-09-12  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalAccountDetailsStatementGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalAccountDetailsStatementGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalBillingDiscrepancyGet**
> V1ExternalBillingDiscrepancyGet200Response v1ExternalBillingDiscrepancyGet()

Get the discrepancy data associated with your account, if any. No parameters are required to use this API.  The data is displayed in JSON format.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalBillingDiscrepancyGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalBillingDiscrepancyGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalChannelsGet**
> V1ExternalChannelsGet200Response v1ExternalChannelsGet()

This API shows a list of all the channels that have already been integrated with your Shiprocket account.  No parameters are required to access this API.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalChannelsGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalChannelsGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalCountriesGet**
> object v1ExternalCountriesGet()

This API lists all the countries present in the Shiprocket database and the respective country ids, ISO 2 and ISO 3 codes.  There are a total of 44 available countries in the database. You can use these codes to check the serviceability and use them in your dropdown menu.  No parameters are required to access this API.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalCountriesGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**object**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalCountriesShowCountryIdGet**
> V1ExternalCountriesShowCountryIdGet200Response v1ExternalCountriesShowCountryIdGet()

Use this API to get a further list of all the available zones within a country, along with their ids and details.  The country ID must be passed as a path parameter to access this API. No other body parameters are required.  #### Path:   |                 **EXAMPLE**                 | |:------------------------------------------: | | https://apiv2.shiprocket.in/v1/external/countries/show/4  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let countryId: string; // (default to undefined)
let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalCountriesShowCountryIdGet(
    countryId,
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **countryId** | [**string**] |  | defaults to undefined|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalCountriesShowCountryIdGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalCourierAssignAwbPost**
> object v1ExternalCourierAssignAwbPost()

This API can be used to assign the AWB (Air Waybill Number) to your shipment. The AWB is a unique number that helps you track the shipment and get details about it.  #### Parameters:  |  **PARAMS**  | **REQUIRED**  |  **DATA TYPE**  |                                                     **DESCRIPTION**                                                     | **EXAMPLE**  | |:-----------: |:------------: |:--------------: |:----------------------------------------------------------------------------------------------------------------------: |:-----------: | | `shipment_id`  |      YES      |    *integer*    |                              The shipment id of the order you want to create the AWB of.                                |   16016920   | |  `courier_id`  |      NO       |    *integer*    |  The courier id of the courier service you want to select. The default courier is selected in case no id is specified.  |      10      | |    `status`    |      NO       |    *string*     |     Use this to change the courier of a shipment. Value: reassign  Note that this can be done only once in 24 hours.    |   reassign   | | `is_return`  |    YES  |  *integer*  | Whether the order is return order or not. 1 in case of Yes and 0 for No.            |  1  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalCourierAssignAwbPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**object**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalCourierCourierListWithCountsGet**
> V1ExternalCourierCourierListWithCountsGet200Response v1ExternalCourierCourierListWithCountsGet()

Use this API to check the list of couriers and the related information with Shiprocket based on the search criteria.   **Note:**  *   This API will work on a company level. *   You can use filters to sort your data. By default, all the couriers are shown if no filter is used. *   total_courier_count will change based on the filter used.       #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `type` | NO | *string* | Use this as a parameter. Possible values are : active/inactive/all | [https://apiv2.shiprocket.in/v1/external/courier/courierListWithCounts?type=active](https://apiv2.shiprocket.in/v1/external/courier/courierListWithCounts?type=active\') |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalCourierCourierListWithCountsGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalCourierCourierListWithCountsGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalCourierGenerateLabelPost**
> V1ExternalCourierGenerateLabelPost200Response v1ExternalCourierGenerateLabelPost()

Generate the label of order by passing the shipment id in the form of an array. This API displays the URL of the generated label.  **Note:** - The AWB must be assigned to the shipment to generate the label. - \'shipment_id\' must be passed as an array.  #### Parameters:  |  **PARAMS**  | **REQUIRED**  |  **DATA TYPE**  |                                                  **DESCRIPTION**                                                  |     **EXAMPLE**      | |:-----------: |:------------: |:--------------: |:----------------------------------------------------------------------------------------------------------------: |:-------------------: | | `shipment_id`  |      YES      |    *integer*    |  The shipment id of the order whose label is to be generated.   Multiple ids can be passed together as an array.  | [16104408,16104409]  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalCourierGenerateLabelPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalCourierGenerateLabelPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**422** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalCourierGeneratePickupPost**
> v1ExternalCourierGeneratePickupPost()

Use this API to create a pickup request for your order shipment. The API returns the pickup status along with the estimated pickup time.   You will have to call the \'Generate Manifest\' API after the successful response of this API.  **Note:**  *   The AWB must be already generated for the shipment id to generate the pickup request. *   Only one shipment_id can be passed at a time.       | PARAMS | REQUIRED | DATA TYPE | DESCRIPTION | EXAMPLE | | --- | --- | --- | --- | --- | | shipment_id | yes | integer | The shipment id of the shipment which is requested for pickup. | 1603434 | | status | no | string | Use this field to retry if the pickup request fails. Value: retry | retry |

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    V1ExternalCourierGeneratePickupPostRequest
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let accept: string; // (default to undefined)
let v1ExternalCourierGeneratePickupPostRequest: V1ExternalCourierGeneratePickupPostRequest; // (optional)

const { status, data } = await apiInstance.v1ExternalCourierGeneratePickupPost(
    accept,
    v1ExternalCourierGeneratePickupPostRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **v1ExternalCourierGeneratePickupPostRequest** | **V1ExternalCourierGeneratePickupPostRequest**|  | |
| **accept** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**400** |  |  -  |
|**500** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalCourierServiceabilityGet**
> object v1ExternalCourierServiceabilityGet()

Use this API to check the availability of couriers between the pickup and delivery postal codes.   Further details like the estimated time of delivery, the rates along with the ids are also shown.  **Note:**  - One of either the \'order_id\' or \'cod\' and \'weight\' is required. If you specify the order id, the cod and weight fields are not required and vice versa.      - You can add further fields to add the shipment details and filter the search.       #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `pickup_postcode` | YES | _integer_ | The shipment id of the order you want to create the AWB of. | 16016920 | | `delivery_postcode` | YES | _integer_ | The courier id of the courier service you want to select. The default courier is selected in case no id is specified. | 10 | | `order_id` | CONDITIONAL YES | _integer_ | Use this to change the courier of a shipment. Value: reassign Note that this can be done only once in 24 hours. | reassign | | `cod` | CONDITIONAL YES | _boolean_ | 1 for Cash on Delivery and 0 for Prepaid orders. | 1 | | `weight` | CONDITIONAL YES | _string_ | The weight of shipment in kgs. | 2 | | `length` | NO | _integer_ | The length of the shipment in cms. | 15 | | `breadth` | NO | _integer_ | The breadth of the shipment in cms. | 10 | | `height` | NO | _integer_ | The height of the shipment in cms. | 5 | | `declared_value` | NO | _integer_ | The price of the order shipment rupee. | 50 | | `mode` | NO | _string_ | The mode of travel. Either: Surface or Air | Air | | `is_return` | YES | _integer_ | Whether the order is return order or not. 1 in case of Yes and 0 for No | 1 | | `qc_check` | NO | _integer_ | Filter out QC couriers from the serviceability list | 1 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalCourierServiceabilityGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**object**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalCourierTrackAwbAwbCodeGet**
> V1ExternalCourierTrackAwbAwbCodeGet200Response v1ExternalCourierTrackAwbAwbCodeGet()

Get the tracking details of your shipment by entering the AWB code of the same in the endpoint URL itself. No other body parameters are required to access this API.  The response is displayed in JSON format.  #### Path:  |                 **EXAMPLE**                 | |:------------------------------------------: | | https://apiv2.shiprocket.in/v1/external/courier/track/awb/788830567028  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let awbCode: string; // (default to undefined)
let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalCourierTrackAwbAwbCodeGet(
    awbCode,
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **awbCode** | [**string**] |  | defaults to undefined|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalCourierTrackAwbAwbCodeGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalCourierTrackAwbsPost**
> V1ExternalCourierTrackAwbsPost200Response v1ExternalCourierTrackAwbsPost()

Get the tracking details of multiple shipments by entering their AWB codes together as an array.  The response is displayed in JSON format.  **Notes:** - Data must be passed as a string array. - Maximum of 50 AWB codes is supported at a time.  #### Parameters:  | **PARAMS**  | **REQUIRED**  | **DATA TYPE**  | **DESCRIPTION**                                              | **EXAMPLE**                      | |:----------: |-------------- |--------------- |------------------------------------------------------------- |--------------------------------- | |   `awbs`    | YES           | *string*       | The AWB codes of the shipments. Must be passed as an array.  | [\"788830567028\",\"788829354408\"]  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalCourierTrackAwbsPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalCourierTrackAwbsPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**500** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalCourierTrackGet**
> Array<V1ExternalCourierTrackGet200ResponseInner> v1ExternalCourierTrackGet()

Get the tracking details of your shipment by entering the Order ID of the same in the endpoint URL itself. If you have the same order ID in more than one channel, then use the param channel_id.  The response is displayed in JSON format.  #### Parameters: | **PARAMS**    | **REQUIRED**  |  **DATA TYPE**  |                           **DESCRIPTION**                            | **EXAMPLE**  | |:----------:   |:------------: |:--------------: |:-------------------------------------------------------------------: |:-----------: | |    `order_id`   |      YES      |   *string*     |                     The order ID/number of your store.                |      NO-123   | |    `channel_id` |    NO      | *integer*  |       Channel ID corresponding to the store    |    12345 |  #### Path:  |                 **EXAMPLE**                 | |:------------------------------------------: | | https://apiv2.shiprocket.in/v1/external/courier/track?order_id=123&channel_id=12345  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let orderId: string; // (default to undefined)
let channelId: string; // (default to undefined)
let authorization: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalCourierTrackGet(
    orderId,
    channelId,
    authorization
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orderId** | [**string**] |  | defaults to undefined|
| **channelId** | [**string**] |  | defaults to undefined|
| **authorization** | [**string**] |  | defaults to undefined|


### Return type

**Array<V1ExternalCourierTrackGet200ResponseInner>**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalCourierTrackShipmentShipmentIdGet**
> V1ExternalCourierTrackShipmentShipmentIdGet200Response v1ExternalCourierTrackShipmentShipmentIdGet()

Get the tracking details of your shipment by entering the shipment_id of the same in the endpoint URL. No other body parameters are required to access this API.  The response is displayed in JSON format.  #### Path:  |                 **EXAMPLE**                 | |:------------------------------------------: | | https://apiv2.shiprocket.in/v1/external/courier/track/shipment/16104408  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let shipmentId: string; // (default to undefined)
let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalCourierTrackShipmentShipmentIdGet(
    shipmentId,
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **shipmentId** | [**string**] |  | defaults to undefined|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalCourierTrackShipmentShipmentIdGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalErrorsImportIdCheckGet**
> V1ExternalErrorsImportIdCheckGet200Response v1ExternalErrorsImportIdCheckGet()

Check the import response of various file imports for any error, including bulk order imports, products and product listings.  You will have to pass the file import id as a path parameter in the endpoint URL. This id is provided at the time of importing the file. No other body parameters are required.   #### Path:  |                 **EXAMPLE**                 | |:------------------------------------------: | | https://apiv2.shiprocket.in/v1/external/errors/20212061/check  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let importId: string; // (default to undefined)
let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalErrorsImportIdCheckGet(
    importId,
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **importId** | [**string**] |  | defaults to undefined|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalErrorsImportIdCheckGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |
|**500** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalInternationalCourierAssignAwbPost**
> V1ExternalInternationalCourierAssignAwbPost200Response v1ExternalInternationalCourierAssignAwbPost()

This API can be used to assign the AWB (Air Waybill Number) to your shipment. The AWB is a unique number that helps you track the shipment and get details about it.  | PARAMS | REQUIRED | DATA TYPE | DESCRIPTION | EXAMPLE | | --- | --- | --- | --- | --- | | shipment_id | yes | integer | The shipment id of the order you want to create the AWB for. | 1603434 | | courier_id | no | integer | The courier id of the courier service you want to select. The default courier is selected in case no id is specified. | 35 | | status | no | string | Use this to change the courier of a shipment. Value: reassign. Note that this can be done only once in 24 hours. | reassign | |  |  |  |  |  |

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    V1ExternalInternationalCourierAssignAwbPostRequest
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let accept: string; // (default to undefined)
let v1ExternalInternationalCourierAssignAwbPostRequest: V1ExternalInternationalCourierAssignAwbPostRequest; // (optional)

const { status, data } = await apiInstance.v1ExternalInternationalCourierAssignAwbPost(
    accept,
    v1ExternalInternationalCourierAssignAwbPostRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **v1ExternalInternationalCourierAssignAwbPostRequest** | **V1ExternalInternationalCourierAssignAwbPostRequest**|  | |
| **accept** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalInternationalCourierAssignAwbPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalInternationalCourierServiceabilityGet**
> V1ExternalInternationalCourierServiceabilityGet200Response v1ExternalInternationalCourierServiceabilityGet()

This API checks courier serviceability for international orders and displays them as a list.  **Notes:**  - \'cod\' field must be 0 as COD is not available for international orders.       #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `weight` | YES | _integer_ | The weight of the shipment. | 10 | | `cod` | YES | _integer_ | Cash on delivery status. Must be 0. | 0 | | `delivery_country` | YES | _string_ | The destination country ISO Alpha 2 code. | US | | `order_id` | NO | _integer_ | The Shiprocket order_id of the shipment if available. | 1 | | `pickup_postcode` | NO | _integer_ | Use this field to select a different pickup postcode other than the primary pickup address. | 2 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let orderId: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalInternationalCourierServiceabilityGet(
    orderId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orderId** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalInternationalCourierServiceabilityGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalInternationalManifestsGeneratePost**
> V1ExternalManifestsGeneratePost200Response v1ExternalInternationalManifestsGeneratePost()

Use this API to create a pickup request for your order shipment. The API returns the pickup status along with the estimated pickup time.   You will have to call the \'Generate Manifest\' API after the successful response of this API.  **Note:**  *   The AWB must be already generated for the shipment id to generate the pickup request. *   Only one shipment_id can be passed at a time.       | PARAMS | REQUIRED | DATA TYPE | DESCRIPTION | EXAMPLE | | --- | --- | --- | --- | --- | | shipment_id | yes | integer | The shipment id of the shipment which is requested for pickup. | 1603434 | | status | no | string | Use this field to retry if the pickup request fails. Value: retry | retry |

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    V1ExternalCourierGeneratePickupPostRequest
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let v1ExternalCourierGeneratePickupPostRequest: V1ExternalCourierGeneratePickupPostRequest; // (optional)

const { status, data } = await apiInstance.v1ExternalInternationalManifestsGeneratePost(
    v1ExternalCourierGeneratePickupPostRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **v1ExternalCourierGeneratePickupPostRequest** | **V1ExternalCourierGeneratePickupPostRequest**|  | |


### Return type

**V1ExternalManifestsGeneratePost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalInternationalOrdersCreateAdhocPost**
> V1ExternalInternationalOrdersCreateAdhocPost200Response v1ExternalInternationalOrdersCreateAdhocPost()

Use this API to create a quick custom order. Quick orders are the ones where we do not store the product details in the master catalogue.  You have to pass all the required params at the minimum to create a quick custom order. You can add additional parameters as per your preference.  **Note:**  - In case the \'shipping_is_billing\' field is false, further shipping detail fields are required.       If no channel id is passed, the order will be assigned to the default custom channel. If the channel id is not known, use the \'Get All Channels\' API to get the list of all integrated channels in your Shiprocket account.  - order_id field cannot be equal to an already existing id. Doing so does not change or affect the existing order. - New orders cannot be created with order id\'s same as that of cancelled orders. If error 422 shows up despite filling in the correct details, consider changing the order_id. - Be sure to input the correct calculated sub_total amount. The total is not calculated automatically through the API. - The \'order_id\' returned in the response is the Shiprocket order_id. Please save this order ID as we will use this in future API calls.       #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `order_id` | YES | _string_ | The order id you want to specify to the order. Max char: 50. (Avoid passing character values as this contradicts some other API calls). | 224477 or 224-477 | | `order_date` | YES | _string_ | The date of order creation in yyyy-mm-dd format. Time is additional. | 2019-07-24 11:11 | | `pickup_location` | YES | _string_ | The name of the pickup location added in your Shiprocket account. This cannot be a new location. | Jammu | | `channel_id` | NO | _integer_ | Mention this in case you need to assign the order to a particular channel. Deafult is \'Custom\'. | 27022 | | `comment` | NO | _string_ | Option to add \'From\' field to the shipment. To do this, enter the name in the following format: \'Reseller: \\[name\\]\'. | Reseller: Divine | | `reseller_name` | NO | _string_ | The \'from\' name if you want to print. Use \'Reseller: \\[name\\]\' | Reseller: Divine | | `company_name` | NO | _string_ | Name of the company. | Amazon | | `billing_customer_name` | YES | _string_ | First name of the billed customer. | John | | `billing_last_name` | NO | _string_ | Last name of the billed customer. | Doe | | `billing_address` | NO | _string_ | address details of the billed customer. | Civil line, House 20 | | `billing_address_2` | NO | _string_ | Further address details of the billed customer. | Near Hokage House | | `billing_city` | YES | _string_ | Billing address city. Max char: 30. | New Delhi | | `billing_pincode` | YES | _integer_ | Pincode of the billing address. | 110002 | | `billing_state` | YES | _string_ | Billing address state. | Delhi | | `billing_country` | YES | _string_ | Billing address country. | India | | `billing_email` | YES | _string_ | Email address of the billed customer. | [John@doe.com](mailto:John@doe.com) | | `billing_phone` | YES | _integer_ | The phone number of the billing customer. | 9856321472 | | `billing_alternate_phone` | NO | _integer_ | Alternate phone number of the billing customer. | 8604690454 | | `shipping_is_billing` | YES | _boolean_ | Whether the shipping address is the same as billing address. 1 or \'true\' for yes and 0 or \'false\' for no. | true | | `shipping_customer_name` | CONDITIONAL YES | _string_ | Name of the customer the order is shipped to. Required in case billing is not same as shipping. | Jane | | `shipping_last_name` | NO | _string_ | Last name of the shipping customer. | Doe | | `shipping_address` | CONDITIONAL YES | _string_ | Address of the Shipping customer. Required in case billing is not same as shipping. | Lane number 69 | | `shipping_address_2` | NO | _string_ | Further address details of shipping customer. | Andheri | | `billing_isd_code` | NO | _string_ | ISD code of the billing address. | +91 | | `shipping_city` | CONDITIONAL YES | _string_ | Shipping address city. | Mumbai | | `shipping_pincode` | CONDITIONAL YES | _integer_ | Shipping address pincode. | 200912 | | `shipping_country` | CONDITIONAL YES | _string_ | Shipping address country. | India | | `shipping_state` | CONDITIONAL YES | _string_ | Shipping address state. | Maharashtra | | `shipping_email` | CONDITIONAL YES | _string_ | Email of the shipping customer. | [Jane@doe.com](mailto:Jane@doe.com) | | `shipping_phone` | CONDITIONAL YES | _integer_ | Phone no. of the shipping customer. |  | | `longitude` | NO | _float_ | Destination (Shipping address) Longitude. | 69.0747 | | `latitude` | NO | _float_ | Destination (Shipping address) Latitude | 22.4064 | | `order_items` | YES | / | List of items and their relevant fields in the form of Array. | / | | `name` | YES | _string_ | Name of the product. | Jeans | | `sku` | YES | _string_ | The sku id of the product. | cbs123 | | `units` | YES | _integer_ | No of units that are to be shipped. | 10 | | `selling_price` | YES | _integer_ | The selling price per unit in Rupee. Inclusive of GST. | 900 | | `discount` | NO | _integer_ | The discount amount in Rupee. Inclusive of tax. | 10 | | `tax` | NO | _integer_ | The tax percentage on the item. | 5 | | `hsn` | NO | _integer_ | Harmonised System Nomenclature code. Used to determine the category of taxation the goods fall under. | 44122 | | `payment_method` | YES | _string_ | The method of payment. Can be either COD (Cash on delivery) Or Prepaid. | COD | | `shipping_charges` | NO | _integer_ | Shipping charges if any in Rupee. | 5 | | `giftwrap_charges` | NO | _integer_ | Giftwrap charges if any in Rupee. | 5 | | `transaction_charges` | NO | _integer_ | Transaction charges if any in Rupee. | 5 | | `total_discount` | NO | _integer_ | The total discount amount in Rupee. | 15 | | `sub_total` | YES | _integer_ | Calculated sub total amount in Rupee after deductions. | 9010 | | `length` | YES | _float_ | The length of the item in cms. Must be more than 0.5. | 10 | | `breadth` | YES | _float_ | The breadth of the item in cms. Must be more than 0.5. | 10 | | `height` | YES | _float_ | The height of the item in cms. Must be more than 0.5. | 10 | | `weight` | YES | _float_ | The weight of the item in kgs. Must be more than 0. | 2.5 | | `ewaybill_no` | NO | _string_ | Details relating to the shipment of goods. . | K92373490 | | `customer_gstin` | NO | _string_ | Goods and Services Tax Identification Number. | 29ABCDE1234F2Z5 | | `invoice_number` | NO | _string_ |  |  | | `order_type` | NO | _string_ | Key to differentiate between Essentials or Non Essentials Shipments. Order type can only be ESSENTIALS or NON ESSENTIALS. Please note it is case sensitive and blank values are allowed. | ESSENTIALS | | `checkout_shipping_method` | NO | _string_ | Only for SRF users.  <br> | a. SR_RUSH: SDD, NDD  <br>b. SR_STANDARD: Surface Delivery  <br>c. SR_EXPRESS: Air Delivery  <br>d. SR_QUICK: 3 hrs delivery | | `what3words_address` | NO | _string_ | What3words is a proprietary geocode system designed to identify any location on the surface of Earth with a resolution of about 3 meters. The system encodes geographic coordinates into three permanently fixed dictionary words. | toddler.geologist.animated | | purpose_of_shipment | NO | interger | The purpose of the shipment. values are 0 - gift, 1- sample, commercial - 2. | 1 | | currency | YES | string | The currency of the order. Possible values are INR,USD,GBP, EUR, AUD, CAD, SAR, AED,SGD | USD | | reasonOfExport | YES | integer | The reason for the export. Possible values are 0 - BONAFIDE_SAMPLE, 1 - SAMPLE, 2 - GIFT, 3 - COMMERCIAL | 2 | | commodity | NO | boolean | Indicates if the order is a commodity or not | true | | mies | NO |  |  | true | | igstPaymentStatus | NO | char | possible values are \'A\'- not applicable, \'B\'- LUT or Export under Bond, \'C\'- Export Against Payment of IGST | A | | Terms_Of_Invoice | YES | string | FOB and CIF | FOB | | ioss | YES | string |  |  | | eori | YES | string |  |  |

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    V1ExternalInternationalOrdersCreateAdhocPostRequest
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let v1ExternalInternationalOrdersCreateAdhocPostRequest: V1ExternalInternationalOrdersCreateAdhocPostRequest; // (optional)

const { status, data } = await apiInstance.v1ExternalInternationalOrdersCreateAdhocPost(
    v1ExternalInternationalOrdersCreateAdhocPostRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **v1ExternalInternationalOrdersCreateAdhocPostRequest** | **V1ExternalInternationalOrdersCreateAdhocPostRequest**|  | |


### Return type

**V1ExternalInternationalOrdersCreateAdhocPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**422** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalInternationalOrdersTrackGet**
> V1ExternalInternationalOrdersTrackGet200Response v1ExternalInternationalOrdersTrackGet()

Get the tracking details of your shipments. No other body parameters are required to access this API.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.v1ExternalInternationalOrdersTrackGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**V1ExternalInternationalOrdersTrackGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalInternationalOrdersUpdateAdhocPost**
> V1ExternalOrdersUpdateAdhocPost200Response v1ExternalInternationalOrdersUpdateAdhocPost()

Use this API to update your orders. You have to pass all the required params at the minimum to create a quick custom order. You can add additional parameters as per your preference.  You can update only the order_items details before assigning the AWB (before Ready to Ship status). You can only update these key-value pairs i.e increase/decrease the quantity, update tax/discount, add/remove product items. Some params specific to international order are.  | PARAMS | REQUIRED | DATA TYPE | DESCRIPTION | EXAMPLE | | --- | --- | --- | --- | --- | | purpose_of_shipment | NO | interger | The purpose of the shipment. values are 0 - gift, 1- sample, commercial - 2. | 1 | | currency | YES | string | The currency of the order. Possible values are INR,USD,GBP, EUR, AUD, CAD, SAR, AED,SGD | USD | | reasonOfExport | No | integer | The reason for the export. Possible values are 0 - BONAFIDE_SAMPLE, 1 - SAMPLE, 2 - GIFT, 3 - COMMERCIAL | 2 | | commodity | NO | boolean | Indicates if the order is a commodity or not | true | | mies | No | boolean |  | true | | igstPaymentStatus | YES | char | possible values are \'A\'- not applicable, \'B\'- LUT or Export under Bond, \'C\'- Export Against Payment of IGST | A | | Terms_Of_Invoice | no | string | The term of invoice either FOB and CIF | FOB |

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    V1ExternalInternationalOrdersUpdateAdhocPostRequest
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let v1ExternalInternationalOrdersUpdateAdhocPostRequest: V1ExternalInternationalOrdersUpdateAdhocPostRequest; // (optional)

const { status, data } = await apiInstance.v1ExternalInternationalOrdersUpdateAdhocPost(
    v1ExternalInternationalOrdersUpdateAdhocPostRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **v1ExternalInternationalOrdersUpdateAdhocPostRequest** | **V1ExternalInternationalOrdersUpdateAdhocPostRequest**|  | |


### Return type

**V1ExternalOrdersUpdateAdhocPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalInternationalSettingsAddBankDetailsPost**
> V1ExternalInternationalSettingsAddBankDetailsPost200Response v1ExternalInternationalSettingsAddBankDetailsPost()

ThisdocumentationprovidesinformationabouttheBankDetailsAPI,whichallowsyouto   addbankdetailsforinternationalsettings.TheAPIendpoint, parameters, request sample   data, success response , and failed response are outlined below.  | PARAMS | REQUIRED | DATA TYPE | DESCRIPTION | EXAMPLE | | --- | --- | --- | --- | --- | | bank_account_type | YES | string | ankaccounttype.Mustbe  <br>either\"saving\"or\"current\". | \"saving\" | | beneficiary_name | YES | string | Beneficiaryname.  <br>Alphabetsandspacesonly | \"JohnDoe\" | | bank_ifsc_code | YES | string | BankIFSCcode.Must  <br>followaspecificpattern | \"ABCD0123456\" | | bank_account_number | YES | integer | Bankaccountnumber.  <br>Shouldbebetween9and  <br>18digits. | 1234567890 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalInternationalSettingsAddBankDetailsPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalInternationalSettingsAddBankDetailsPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalInternationalSettingsInternationalKycPost**
> V1ExternalInternationalSettingsInternationalKycPost200Response v1ExternalInternationalSettingsInternationalKycPost()

Use this API for your international KYC. This API return your KYC status.   Please check the documentation for the documents for KYC.  | PARAMS | REQUIRED DATA | DATA TYPE | DESCRIPTION | EXAMPLE | | --- | --- | --- | --- | --- | | organization_type | Yes | string | Seller organization | company | | ip_address | Yes | int unsigned | Seller\'s ip_address | 192.168.1.1.0 | | documents | Yes | array | Documentaion for organization type  <br>(document size is not greater than 3 MB) | Please check request |

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    V1ExternalInternationalSettingsInternationalKycPostRequest
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let v1ExternalInternationalSettingsInternationalKycPostRequest: V1ExternalInternationalSettingsInternationalKycPostRequest; // (optional)

const { status, data } = await apiInstance.v1ExternalInternationalSettingsInternationalKycPost(
    v1ExternalInternationalSettingsInternationalKycPostRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **v1ExternalInternationalSettingsInternationalKycPostRequest** | **V1ExternalInternationalSettingsInternationalKycPostRequest**|  | |


### Return type

**V1ExternalInternationalSettingsInternationalKycPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalInternationalShipmentsCreateForwardShipmentPost**
> V1ExternalInternationalShipmentsCreateForwardShipmentPost200Response v1ExternalInternationalShipmentsCreateForwardShipmentPost()

Use this API to do multiple tasks in one go, namely creating a quick order, requesting its shipment, pickup generation generating the label and the manifest for the same order.  This API integrates several other APIs to perform all these tasks together.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalInternationalShipmentsCreateForwardShipmentPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalInternationalShipmentsCreateForwardShipmentPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalInventoryGet**
> V1ExternalInventoryGet200Response v1ExternalInventoryGet()

This API can be used to check the inventory details of a product sku. There are no required parameters for this API, but additional parameters can be used to sort and filter the data.   In case no filter conditions are passed, the details are displayed in the default JSON format.  #### Parameters:  | **PARAMS**  | **REQUIRED**  |  **DATA TYPE**  |                                                    **DESCRIPTION**                                                    | **EXAMPLE**  | |:----------: |:------------: |:--------------: |:--------------------------------------------------------------------------------------------------------------------: |:-----------: | |    `page`     |      NO       |    *integer*    |                                           The page number to be displayed.                                            |      4       | |  `per_page`   |      NO       |    *integer*    |                                  The total products you want to diplay in each page.                                  |      2       | |    `sort`     |      NO       |    *string*     |                                      Sort conditions if any. Value: ASC or DESC                                       |     ASC      | |   `sort_by`   |      NO       |    *integer*    |  Allows you to choose the field by which the data will be sorted.   Could be sorted by id, by sku, time created etc.  |     sku      |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalInventoryGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalInventoryGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalInventoryProductIdUpdatePut**
> V1ExternalInventoryProductIdUpdatePut200Response v1ExternalInventoryProductIdUpdatePut()

This API is used to update your product inventory details.  First, you need to pass the product_id of the product in the endpoint URL. You can then set the quantity and action you want to perform on the existing inventory of the specified product.  **Note:** - The product_id can be found using the \'Get Inventory Details\' API. - The id is to be passed in the endpoint URL itself.  #### Path:   |                 **EXAMPLE**                 | |:------------------------------------------: | | https://apiv2.shiprocket.in/v1/external/inventory/17454637/update |    #### Parameters:  | **PARAMS**  | **REQUIRED**  |  **DATA TYPE**  |                                                                                                                      **DESCRIPTION**                                                                                                                      | **EXAMPLE**  | |:----------: |:------------: |:--------------: |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |:-----------: | |  `quantity`   |      YES      |    *integer*    |                                                                                                           The quantity of the product you want.                                                                                                           |      2       | |   `action`    |      YES      |    *integer*    |  The action you want to perform. *Value*:    - **add** : Adds the specific quantity to the product inventory.   - **replace** : Replaces the existing quantity with the specified number. - **remove** : Removes the specific number from the product inventory.  |     add      |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let productId: string; // (default to undefined)
let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalInventoryProductIdUpdatePut(
    productId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |
| **productId** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalInventoryProductIdUpdatePut200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalListingsExportMappedGet**
> V1ExternalListingsExportMappedGet200Response v1ExternalListingsExportMappedGet()

This API downloads the list of mapped items in your channel catalogue sheet. After mapping the items, you can see the number of products in one channel present in the Master Catalogue.  The downloaded CSV file URL is shared as the response. No other body parameters are required.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalListingsExportMappedGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalListingsExportMappedGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalListingsExportUnmappedGet**
> V1ExternalListingsExportMappedGet200Response v1ExternalListingsExportUnmappedGet()

Get a list of all the unmapped products in your channel catalogue using this API.  The list is downloaded into a CSV file, and the download URL is displayed as the response. No other body parameters are required.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalListingsExportUnmappedGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalListingsExportMappedGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalListingsGet**
> V1ExternalListingsGet200Response v1ExternalListingsGet()

This API can be used to get a JSON representation of all the product listings in your Shiprocket account, i.e., all the products associated with a specific channel.  No parameters are required to access this API. However, the displayed data can be filtered and sorted using further parameters. If no sort parameter is used, the data is displayed in the default format.  #### Parameters:  | **PARAMS**  | **REQUIRED**  |  **DATA TYPE**  |                                                       **DESCRIPTION**                                                       | **EXAMPLE**  | |:----------: |:------------: |:--------------: |:--------------------------------------------------------------------------------------------------------------------------: |:-----------: | |    `page`     |      NO       |    *integer*    |                                            The page number you want to display.                                             |      5       | |  `per_page`   |      NO       |    *integer*    |                                           The number of listings to get per page.                                           |      2       | |    `sort`     |      NO       |    *string*     |                                        The order to sort by. *Value*: **ASC** or **DESC**                                         |     ASC      | |   `sort_by`   |      NO       |    *string*     |  Allows you to choose the value field by which the listings will be sorted.  Could be sorted by id, by sku, time created etc.  |     sku      | |   `filter`    |      NO       |    *string*     |                                        The data to be matched for the filter value.                                         |   11223344   | |  `filter_by`  |      NO       |    *string*     |                                        The filter value field . Can be id, sku, etc.                                        |      id      |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalListingsGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalListingsGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalListingsImportPost**
> V1ExternalOrdersImportPost200Response v1ExternalListingsImportPost()

Use this API to import a CSV file containing channel catalogue to the master catalogue mappings.  No other body parameters are required.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let file: File; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalListingsImportPost(
    file
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **file** | [**File**] |  | defaults to undefined|


### Return type

**V1ExternalOrdersImportPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json, */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalListingsLinkPost**
> GenerateToken403Response v1ExternalListingsLinkPost()

Use this API to map a product present in the channel catalogue to a product present in the master catalogue.  Pass the product and listing id for the successful call of the API  #### Parameters:  | **PARAMS**  | **REQUIRED**  | **DATA TYPE**  | **DESCRIPTION**  | **EXAMPLE**  | |:------------: |-------------- |--------------- |----------------------------------------------- |------------- | | `product_id`  | YES  | *integer*  | The id of item in the master catalog.  | 17908342  | | `listing_id`  | YES  | *integer*  | The id of the product in the channel catalog.  | 15897064  | | `ID`  | NO  | *integer*  | The id placed in the respective \'GET\' codes.  | 15897064  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalListingsLinkPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**GenerateToken403Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalListingsSampleGet**
> V1ExternalListingsExportMappedGet200Response v1ExternalListingsSampleGet()

This API displays the download link of a sample catalogue sheet for reference purposes.  No additional parameters are required.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalListingsSampleGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalListingsExportMappedGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalManifestsGeneratePost**
> V1ExternalManifestsGeneratePost200Response v1ExternalManifestsGeneratePost()

Using this API, you can generate the manifest for your order. This API generates the manifest and displays the download URL of the same.  **Note:** - Multiple ids can also be passed as an array for bulk generation of manifests. - AWB must be assigned and pickup requested on the shipment id to generate manifest.  #### Parameters:  |  **PARAMS**  | **REQUIRED**  |  **DATA TYPE**  |                                       **DESCRIPTION**                                       | **EXAMPLE**  | |:-----------: |:------------: |:--------------: |:------------------------------------------------------------------------------------------: |:-----------: | | `shipment_id`  |      YES      |    *integer*    | The shipment id of the order. Multiple ids can be passed as an array, separated by commas.  |  [16090109]  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalManifestsGeneratePost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalManifestsGeneratePost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalManifestsPrintPost**
> V1ExternalManifestsPrintPost200Response v1ExternalManifestsPrintPost()

Use this API to print the generated manifest of orders at an individual level.  **Note** - Manifest needs to be generated first for this API to print it. Use the \'Generate Manifest\' API to do the same. - Multiple order ids can be passed together.  #### Parameters:  | **PARAMS**  | **REQUIRED**  |  **DATA TYPE**  |                                                 **DESCRIPTION**                                                 | **EXAMPLE**  | |:----------: |:------------: |:--------------: |:--------------------------------------------------------------------------------------------------------------: |:-----------: | |  `order_ids`  |      YES      |    *integer*    | The Shiprocket order id of whose manifest is to be generated. Multiple ids can be passed together as an array.  |  [16090109]  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalManifestsPrintPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalManifestsPrintPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**500** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalNdrAWBGet**
> V1ExternalNdrAWBGet200Response v1ExternalNdrAWBGet()

Get the shipment details of a particular order through this API by passing the AWB number in the endpoint URL itself. You can get the details like AWB, NDR Attempt, NDR Reason, Customer Details, Product Details, Courier.  Type in your AWB code in place of {AWB}. No other body parameters are required.  #### Path:  |       **EXAMPLE**        | |:-----------------------: | | https://apiv2.shiprocket.in/v1/external/ndr/94711332  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let aWB: string; // (default to undefined)
let contentType: string; // (default to undefined)
let authorization: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalNdrAWBGet(
    aWB,
    contentType,
    authorization
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **aWB** | [**string**] |  | defaults to undefined|
| **contentType** | [**string**] |  | defaults to undefined|
| **authorization** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalNdrAWBGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalNdrAllGet**
> object v1ExternalNdrAllGet()

This API call will display a list of all the shipments that are in NDR in your Shiprocket account.   You can also sort and filter the data according to your needs by passing the optional parameters. Not passing anything will display the data in the default format.  #### Parameters:  | **PARAMS**  | **REQUIRED**  |  **DATA TYPE**  |                           **DESCRIPTION**                            | **EXAMPLE**  | |:----------: |:------------: |:--------------: |:-------------------------------------------------------------------: |:-----------: | |    `page`     |      NO       |   *integer*     |                     The page number to display.                      |      5       | |  `per_page`   |      NO       |    *integer*    |                   The number of entries per page.                    |      5       | |     `to`      |      NO       |    *string*     |                            The end date.                             |  2021-08-02  | |    `from`     |      NO       |    *string*     |                           The start date.                            |  2021-08-02  |                        |   `search`    |      NO       |    *string*     | Search for AWB.  |    224477    |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)
let authorization: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalNdrAllGet(
    contentType,
    authorization
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|
| **authorization** | [**string**] |  | defaults to undefined|


### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalNdrAwbActionPost**
> V1ExternalNdrAwbActionPost202Response v1ExternalNdrAwbActionPost()

This API will let you take actions like Reattempt and RTO on the shipments that are in NDR.  #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `action` | YES | *string* | The action needs to be specified | ‘fake-attempt’ or ‘re-attempt’ or \'return\' | | `comments` | YES | *string* | Any comment can be mentioned | The Byer does not want the product | | `phone` | NO | *string* | The phone number will be updated at the time of re-attempt and fake-attempt | 9999988888 | | `proof_audio` | CONDITIONAL YES | *string* | URL of the audio which will be updated at the time of the fake attempt | [https://s3-ap-southeast-1.amazonaws.com/kr-multichannel/imports/ndr/1655100133_file_example_MP3_700KB.mp3](https://s3-ap-southeast-1.amazonaws.com/kr-multichannel/imports/ndr/1655100133_file_example_MP3_700KB.mp3) | | `proof_image` | CONDITIONAL YES | *string* | URL of the image which will be updated at the time of the fake attempt | [https://s3-ap-southeast-1.amazonaws.com/kr-multichannel/imports/ndr/img_7687678678.jpg](https://s3-ap-southeast-1.amazonaws.com/kr-multichannel/imports/ndr/img_7687678678.jpg) | | `remarks` | CONDITIONAL YES | *string* | Remarks will be updated at the time of a fake attempt | Delivery Requested | | `address1` | NO | *string* | address1 will be updated at the time of re-attempt and fake-attempt | U-56, sector-23, Noida, India | | `address2` | NO | *string* | addres2 will be updated at the time of re-attempt and fake-attempt | U-56, sector-23, Noida, India | | `deferred_date` | NO | *date(string)* | Deferred date will be updated as preferred_date at the time of fake-attempt and re-attempt | 2022-08-10 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let awb: string; // (default to undefined)
let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalNdrAwbActionPost(
    awb,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |
| **awb** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalNdrAwbActionPost202Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**202** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOpenPostcodeDetailsGet**
> V1ExternalOpenPostcodeDetailsGet200Response v1ExternalOpenPostcodeDetailsGet()

Use this API to get further locality details of any given postcode. Just pass the valid locality Pincode, and the details will be displayed in JSON format.  #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | |:----------:|:------------:|:-------------:|:---------------------------------------------------:|:-----------:| | `postcode` | YES | *integer* | The Pincode you want to get the locality details. | 110077 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalOpenPostcodeDetailsGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalOpenPostcodeDetailsGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**403** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersAddressPickupPatch**
> V1ExternalOrdersAddressPickupPatch200Response v1ExternalOrdersAddressPickupPatch()

Using this API, you can modify the pickup location of an already created order. Multiple order ids can be passed to update their pickup location together.  **Note:** - Pickup location can only be changed/updated to an already existing pickup location in your account.  - The \'order_id\' to be passed is the Shiprocket order_id received at the time of order creation. - Multiple order ids can be passed as an array, separated by commas. eg: [\"141414,142424,143434\"]  #### Parameters:  |    **PARAMS**    | **REQUIRED**  |  **DATA TYPE**  |                             **DESCRIPTION**                              | **EXAMPLE**  | |:---------------: |:------------: |:--------------: |:-----------------------------------------------------------------------: |:-----------: | |     `order_id`     |      YES      |    *integer*    |             The Shiprocket order_id specified to the order.              |   16167171   | | `pickup_location`  |      YES      |    *string*     | The pickup location you want to change your current pickup location to.  |    Delhi     |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersAddressPickupPatch(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalOrdersAddressPickupPatch200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |
|**500** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersAddressUpdatePost**
> object v1ExternalOrdersAddressUpdatePost()

You can update the customer\'s name and delivery address through this API by passing the Shiprocket order id and the necessary customer details.  #### Parameters:  |       **PARAMS**        | **REQUIRED**  |  **DATA TYPE**  |                 **DESCRIPTION**                  |   **EXAMPLE**    | |:----------------------: |:------------: |:--------------: |:-----------------------------------------------: |:---------------: | |        `order_id`         |      YES      |    *integer*    | The Shiprocket order_id specified to the order.  |     16178831     | | `shipping_customer_name`  |      YES      |    *string*     |            The name of the customer.             |     John Doe     | |     `shipping_phone`      |      YES      |    *integer*    |          Phone number of the customer.           |    9988998899    | |    `shipping_address`     |      YES      |    *string*     |         Primary address of the customer.         |   House no 123   | |   `shipping_address_2`    |      NO       |    *string*     |     Further address details of the customer.     | Beside CM house  | |      `shipping_city`      |      YES      |    *string*     |               Shipping city name.                |       Pune       | |     `shipping_state`      |      YES      |    *string*     |               Shipping state name.               |   Maharashtra    | |    `shipping_country`     |      YES      |    *string*     |              Shipping country name.              |      India       | |    `shipping_pincode`     |      YES      |    *integer*    |            Shipping address pincode.             |      120023      | |     `shipping_email`      |      NO       |    *string*     |            Customer\'s email address.             |   john@doe.com   | |     `billing_alternate_phone`      |      NO       |    *string*     |          The customer alternate phone.             |   8604690454   |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersAddressUpdatePost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**object**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: */*, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**202** |  |  -  |
|**422** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersCancelPost**
> object v1ExternalOrdersCancelPost()

Use this API to cancel a created order. Multiple order_ids can be passed together as an array to cancel them simultaneously.  #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `ids` | YES | *integer* | The Shiprocket order id/ids of the orders that need to be canceled. | 16178831 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersCancelPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**object**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: */*, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** |  |  -  |
|**422** |  |  -  |
|**500** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersCancelShipmentAwbsPost**
> V1ExternalOrdersAddressPickupPatch200Response v1ExternalOrdersCancelShipmentAwbsPost()

Use this API to cancel a created shipment before the \"Out for Pickup\" state. Multiple AWBs can be passed together as an array to cancel them simultaneously.  **Limit: 2000 AWBs**  #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `awbs` | YES | *string* | The AWB/List of AWBs that need to be canceled. | 19041211125783 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersCancelShipmentAwbsPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalOrdersAddressPickupPatch200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersCreateExchangePost**
> V1ExternalOrdersCreateExchangePost200Response v1ExternalOrdersCreateExchangePost()

Use this API to create a new exchange order in your Shiprocket panel. Exchange orders are created in case the buyer needs to replace an item due to reasons such as size mismatch, wrong product received, or defective product. This API helps sellers seamlessly process exchange requests while ensuring the correct quality checks and logistics handling  #### Parameters:  | PARAMS | REQUIRED | DATA TYPE | DESCRIPTION | EXAMPLE | | --- | --- | --- | --- | --- | | `exchange_order_id` | YES | _String_ | Unique ID for the exchange order | EX_TEST002 | | `seller_pickup_location_id` | YES | _String_ | Pickup location ID of the seller | 5723898 | | `seller_shipping_location_id` | YES | _String_ | Shipping location ID of the seller | 5723898 | | `return_order_id` | YES | _String_ | Unique ID for the return order | R_TEST002 | | `order_date` | YES | _Date_ | Date of order placement (YYYY-MM-DD) | 2024-12-10 | | `payment_method` | YES | _String_ | Payment method used for the order | prepaid | | `buyer_shipping_first_name` | YES | _String_ | First name of the shipping buyer | Test | | `buyer_shipping_last_name` | NO | _String_ | Last name of the shipping buyer | Test | | `buyer_shipping_email` | NO | _String_ | Email of the shipping buyer (valid email format) | [test@gmail.com](https://null) | | `buyer_shipping_address` | YES | _String_ | Full address of the shipping buyer | dkalsd | | `buyer_shipping_address_2` | NO | _String_ | Additional address details |  | | `buyer_shipping_city` | YES | _String_ | City of the shipping buyer | South West Delhi | | `buyer_shipping_state` | YES | _String_ | State of the shipping buyer | Delhi | | `buyer_shipping_country` | YES | _String_ | Country of the shipping buyer | India | | `buyer_shipping_pincode` | YES | _String_ | Pincode of the shipping address | 110045 | | `buyer_shipping_phone` | YES | _String_ | Contact number of the shipping buyer (10 digits) | 9716414139 | | `buyer_pickup_first_name` | YES | _String_ | First name of the pickup buyer | Test | | `buyer_pickup_last_name` | NO | _String_ | Last name of the pickup buyer | Test | | `buyer_pickup_email` | NO | _String_ | Email of the pickup buyer | [test@gmail.com](https://null) | | `buyer_pickup_address` | YES | _String_ | Full address of the pickup buyer | Test | | `buyer_pickup_address_2` | NO | _String_ | Additional pickup address details |  | | `buyer_pickup_city` | YES | _String_ | City of the pickup buyer | South West Delhi | | `buyer_pickup_state` | YES | _String_ | State of the pickup buyer | Delhi | | `buyer_pickup_country` | YES | _String_ | Country of the pickup buyer | India | | `buyer_pickup_pincode` | YES | _String_ | Pincode of the pickup address | 110045 | | `buyer_pickup_phone` | YES | _String_ | Contact number of the pickup buyer (10 digits) | 9716414139 | | `order_items` | YES | _Array_ | List of items in the order |  | | `order_items[].name` | YES | _String_ | Name of the product | Black tshirt XL | | `order_items[].selling_price` | YES | _Float_ | Price of the product | 500.00 | | `order_items[].units` | YES | _Integer_ | Quantity of the product | 1 | | `order_items[].hsn` | YES | _String_ | HSN code of the product | 1733808730720 | | `order_items[].sku` | YES | _String_ | SKU of the product | mackbook | | `order_items[].tax` | NO | _Float_ | Tax amount |  | | `order_items[].discount` | NO | _Float_ | Discount on the product |  | | `order_items[].exchange_item_id` | NO | _String_ | Exchange item ID | 193658024 | | `order_items[].exchange_item_name` | YES | _String_ | Exchange item name | Black tshirt XL | | `order_items[].exchange_item_sku` | YES | _String_ | Exchange item SKU | mackbook | | `sub_total` | YES | _Float_ | Subtotal amount | 500.00 | | `shipping_charges` | NO | _Float_ | Shipping charges |  | | `giftwrap_charges` | NO | _Float_ | Gift wrapping charges |  | | `total_discount` | NO | _Float_ | Total discount on the order | 0 | | `transaction_charges` | NO | _Float_ | Transaction charges |  | | `return_length` | YES | _Float_ | Return package length (cm) | 10.00 | | `return_breadth` | YES | _Float_ | Return package breadth (cm) | 10.00 | | `return_height` | YES | _Float_ | Return package height (cm) | 10.00 | | `return_weight` | YES | _Float_ | Return package weight (kg) | 0.500 | | `exchange_length` | YES | _Float_ | Exchange package length (cm) | 11.00 | | `exchange_breadth` | YES | _Float_ | Exchange package breadth (cm) | 11.00 | | `exchange_height` | YES | _Float_ | Exchange package height (cm) | 11.00 | | `exchange_weight` | YES | _Float_ | Exchange package weight (kg) | 11.00 | | `return_reason` | YES | _String_ | Reason for return | 29 |

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    V1ExternalOrdersCreateExchangePostRequest
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)
let authorization: string; // (default to undefined)
let v1ExternalOrdersCreateExchangePostRequest: V1ExternalOrdersCreateExchangePostRequest; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersCreateExchangePost(
    contentType,
    authorization,
    v1ExternalOrdersCreateExchangePostRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **v1ExternalOrdersCreateExchangePostRequest** | **V1ExternalOrdersCreateExchangePostRequest**|  | |
| **contentType** | [**string**] |  | defaults to undefined|
| **authorization** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalOrdersCreateExchangePost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersCreatePost**
> V1ExternalOrdersCreatePost200Response v1ExternalOrdersCreatePost()

This API can be used to create a custom order, the same as the Custom order API, except that you have to specify and select a custom channel to create the order.   The order created will be added under the specified channel. All the other parameters are the same.  **Note:** - Channel_id field is required. - Order_id cannot be the same as the already existing order id. - Inventory Sync must be turned on to use this API. This can be done under the \'Channels\' portion on the left-hand panel of your Shiprocket account. - Inventory details of your Shiprocket account can be accessed using the \'Get Inventory Details\' API.  #### Parameters:  |       **PARAMS**        |   **REQUIRED**   |  **DATA TYPE**  |                                                                         **DESCRIPTION**                                                                          |        **EXAMPLE**        | |:----------------------: |:---------------: |:--------------: |:---------------------------------------------------------------------------------------------------------------------------------------------------------------: |:------------------------: | |        `order_id`         |       YES        |    *string*     |               The order id you want to specify to the order. Max char: 20.  (Avoid passing character values as this contradicts some other API calls).              |     224477 or 224-477     | |       `order_date`        |       YES        |    *string*     |                                         The date of order creation in yyyy-mm-dd format. Time is an additional option.                                         |     2019-07-24 11:11      | |     `pickup_location`     |        NO        |    *string*     |  The name of the pickup location added in your Shiprocket account. This cannot be a new location. Default Pickup location is selected in case the parameter is not filled.  |           Jammu           | |       `channel_id`        |       YES        |    *integer*    |                                                          The id of the specific channel to be selected.                                                          |           27022           | |         `comment`         |        NO        |    *string*     |                       Option to add \'From\' field to the shipment.   To do this, enter the name in the following format: \'Reseller: [name].\'                       |     Reseller: Divine      | |  `billing_customer_name`  |       YES        |    *string*     |                                                            First name of the customer who is billed.                                                             |          John           | |   ` billing_last_name`    |        NO        |    *string*     |                                                                Last name of the billed customer.                                                                 |          Doe          | |     `billing_address`     |       YES        |    *string*     |                                                       Primary address of the billed customer.  Min char: 3.                                                       | House 221B, Leaf Village  | |    `billing_address_2`    |        NO        |    *string*     |                                                         Further address details of the billed customer.                                                          |     Near Hokage House     | |      `billing_city`       |       YES        |    *string*     |                                                               Billing address city.  Max char: 30.                                                                |         New Delhi         | |     `billing_pincode`     |       YES        |    *integer*    |                                                                 Pincode of the billing address.                                                                  |          110002           | |      `billing_state`      |       YES        |    *string*     |                                                                      Billing address state.                                                                      |           Delhi           | |    ` billing_country`     |       YES        |    *string*     |                                                                     Billing address country.                                                                     |           India           | |      `billing_email`      |       YES        |    *string*     |                                                              Email address of the billed customer.                                                               |    John@doe.com     | |      `billing_phone`      |       YES        |    *integer*    |                                                               Phone number of the billed customer.                                                               |        9876543210         | |   `shipping_is_billing`   |       YES        |    *boolean*    |                            Whether the shipping address is the same as billing address.   1 or \'true\' for yes and 0 or \'false\' for no.                           |           true            | | `shipping_customer_name`  | CONDITIONAL YES  |    *string*     |                                 Name of the customer the order is shipped to.   Required in case billing is not same as shipping.                                |          Jane           | |   `shipping_last_name`    |        NO        |    *string*     |                                                               Last name of the shipping customer.                                                                |          Doe          | |    `shipping_address`     | CONDITIONAL YES  |    *string*     |                                        Address of the Shipping customer. Required in case billing is not same as shipping.                                       |       Lane 69       | |   `shipping_address_2`    |        NO        |    *string*     |                                                          Further address details of shipping customer.                                                           |       Andheri        | |      `shipping_city`      | CONDITIONAL YES  |    *string*     |                                                                      Shipping address city.                                                                      |          Mumbai           | |    `shipping_pincode`     | CONDITIONAL YES  |    *integer*    |                                                                    Shipping address pincode.                                                                     |          200912           | |    `shipping_country`     | CONDITIONAL YES  |    *string*     |                                                                    Shipping address country.                                                                     |           India           | |     `shipping_state`      | CONDITIONAL YES  |    *string*     |                                                                    Shipping address state.                                                                     |        Maharashtra        | |     `shipping_email`      | CONDITIONAL YES  |    *string*     |                                                                 Email of the shipping customer.                                                                  |    jane@doe.com     | |     `shipping_phone`      | CONDITIONAL YES  |    *integer*    |                                                                Phone no. of the shipping customer                                                                |        9887655432         | |       `order_items`       |       YES        |        /        |                                                                 Array containing further fields.                                                                 |             /             | |          `name`           |       YES        |    *string*     |                                                                       Name of the product.                                                                       |           Jeans           | |           `sku`           |       YES        |    *string*     |                                                                    The sku id of the product.                                                                    |         cbs123         | |          `units`          |       YES        |    *integer*    |                                                               No. of units that are to be shipped.                                                                |            10             | |      `selling_price`      |       YES        |    *integer*    |                                                      The selling price per unit in Rupee. Inclusive of GST.                                                      |            900            | |        `discount`         |        NO        |    *integer*    |                                                         The discount amount in Rupee. Inclusive of tax.                                                          |            10             | |           `tax`           |        NO        |    *integer*    |                                                                 The tax percentage on the item.                                                                  |             5             | |           `hsn`           |        NO        |    *integer*    |                              Harmonised System Nomenclature code.   Used to determine the category of taxation the goods fall under.                             |           44122           | |    ` payment_method`      |       YES        |    *string*     |                                             The method of payment. Can be either COD (Cash on delivery) Or Prepaid.                                              |            COD            | |    `shipping_charges`     |        NO        |    *integer*    |                                                                Shipping charges if any in Rupee.                                                                 |             5             | |    `giftwrap_charges`     |        NO        |    *integer*    |                                                                Giftwrap charges if any in Rupee.                                                                 |             5             | |   `transaction_charges`   |        NO        |    *integer*    |                                                               Transaction charges if any in Rupee.                                                               |             5             | |     `total_discount`      |        NO        |    *integer*    |                                                               The total discount amount in Rupee.                                                                |            15             | |        `sub_total`        |       YES        |    *integer*    |                                                              Calculated sub total amount in Rupee.                                                               |           9010            | |         `length`          |       YES        |    *integer*    |                                                      The length of the item in cms. Must be more than 0.5.                                                       |            10             | |         `breadth`         |       YES        |    *integer*    |                                                      The breadth of the item in cms. Must be more than 0.5.                                                      |            10             | |         `height`          |       YES        |    *integer*    |                                                      The height of the item in cms. Must be more than 0.5.                                                       |            10             | |         `weight`          |       YES        |    *integer*    |                                                       The weight of the item in kgs. Must be more than 0.                                                        |            2.5            |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersCreatePost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalOrdersCreatePost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |
|**422** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersCreateReturnPost**
> V1ExternalOrdersCreateReturnPost200Response v1ExternalOrdersCreateReturnPost()

Use this API to create a new return order in your Shiprocket panel. Return orders are created in case the buyer refuses/rejects/returns a specific order.   The parameter specifications are the same as the custom order API, with a few exceptions.  #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `order_id` | YES | _string_ | The order id you want to specify to the order. Max char: 50. (Avoid passing character values as this contradicts some other API calls) | 99711997 | | `order_date` | YES | _string_ | The date of order creation in yyyy-mm-dd format. Time is an additional option. | 2019-08-05 | | `channel_id` | NO | _integer_ | Id of the desired channel where the order is to be placed. \'Custom\' channel id is selected in case parameter is not filled. | 768903 | | `pickup_customer_name` | YES | _string_ | The customer’s first name. | John | | `pickup_last_name` | NO | _string_ | The customer’s last name. | Doe | | `pickup_address` | YES | _string_ | The customer\'s primary address. | 416, Udyog Vihar III, Sector 20 | | `pickup_address_2` | NO | _string_ | Additional customer address details. | DDA | | `pickup_city` | YES | _string_ | The customer\'s city name. | Delhi | | `pickup_state` | YES | _string_ | The customer\'s state. | New Delhi | | `pickup_country` | YES | _string_ | Customer\'s country name. | India | | `pickup_pincode` | YES | _integer_ | Pincode of the customer address. | 110002 | | `pickup_email` | YES | _string_ | Customer\'s email address. | [john@doe.com](https://mailto:john@doe.com) | | `pickup_phone` | YES | _string_ | Customer\'s phone number. | 9999999999 | | `pickup_isd_code` | NO | _string_ | ISD code. | 91 | | `shipping_customer_name` | YES | _string_ | The name of the seller the package is shipped back to. | Jane | | `shipping_last_name` | NO | _string_ | The last name of the seller. | Doe | | `shipping_address` | YES | _string_ | The address the package is shipped to. | Castle | | `shipping_address_2` | NO | _string_ | Further shipping address details. | Bridge | | `shipping_city` | YES | _string_ | The shipping address city. | Mumbai | | `shipping_country` | YES | _string_ | The shipping address country. | India | | `shipping_pincode` | YES | _integer_ | The shipping pincode. | 220022 | | `shipping_state` | YES | _string_ | Shipping address state. | Maharashtra | | `shipping_email` | NO | _string_ | The email of the seller the package is shipped to. | [jane@doe.com](https://mailto:jane@doe.com) | | `shipping_isd_code` | NO | _string_ | The shipping isd code. | 91 | | `shipping_phone` | YES | _integer_ | Phone no. of the shipping customer | 8888888888 | | `order_items` | YES | / | Array containing further fields. | / | | `name` | YES | _string_ | Name of the product. | ball123 | | `sku` | YES | _string_ | The sku id of the product. | Tennis Ball | | `units` | YES | _integer_ | No of units that are to be shipped. | 1 | | `selling_price` | YES | _integer_ | The selling price per unit in Rupee. Inclusive of GST. | 10 | | `discount` | NO | _integer_ | The discount amount in Rupee. Inclusive of tax. | 0 | | `hsn` | NO | _string_ | Harmonised System Nomenclature code. Used to determine the category of taxation the goods fall under. | 4412 | | `return_reason` | NO | _string_ | Bought by Mistake, Both product and shipping box damaged | Please refer to the \"Possible return_reason values\" section | | `qc_enable` | CONDITIONAL YES | _string_ | If True, QC will be performed for that product and QC will be performed only for a single SKU per order | true/false | | `qc_color` | NO | _varchar(180)_ | The color of the product can be passed in this parameter | Red | | `qc_brand` | NO | _varchar(255)_ | The brand of the product can be passed in this parameter | 768903 | | `qc_serial_no` | NO | _varchar(255)_ | The serial number of the product can be passed in this parameter | T13123124 | | `qc_ean_barcode` | NO | _varchar(255)_ | EAN/Barcode of the product can be passed in this parameter | QWRE123 | | `qc_size` | NO | _varchar(180)_ | The size of the product can be passed in this parameter | 8 | | `qc_product_name` | CONDITIONAL YES | _varchar(255)_ | If qc_enable set True, then Product name should be passed in this parameter | Shoes | | `qc_product_image` | CONDITIONAL YES | _varchar(255)_ | If qc_enable set True, then Product image should be passed in this parameter (only png/jpg format supported) | [https://s3-ap-southeast-1.amazonaws.com/kr-multichannel/1636713733zxja.png](https://s3-ap-southeast-1.amazonaws.com/kr-multichannel/1636713733zxja.png) | | `qc_product_imei` | NO | _varchar(255)_ | IMEI of the device | 398612387501872509 | | `qc_brand_tag` | NO | _boolean_ | Eligible Categories : Selective like Footwear, Apparels  <br>The pickup agent will cross-check the provided brand name, which should match the brand tag affixed to the item(s) upon delivery. Can be either 0 or 1 | 1 | | `qc_used_check` | NO | _boolean_ | Eligible Product Categories : All  <br>The pickup agent will check the product being handed over for clear signs of usage. Can be either 0 or 1 | 0 | | `qc_sealtag_check` | NO | _boolean_ | Eligible Product Categories : All  <br>The pickup agent will check if the seal tag is intact in the products received from the buyer. Can be either 0 or 1 | 1 | | `qc_check_damaged_product` | NO | _string_ | Eligible Product Categories : All  <br>The pickup agent will check the product for any signs of damages. Can be either yes or no | yes | | `payment_method` | YES | _string_ | The method of payment. This should always be prepaid. | Prepaid | | `total_discount` | NO | _string_ | The total discount amount in Rupee. | 0 | | `sub_total` | YES | _integer_ | Calculated sub total amount in Rupee after deductions. | 10 | | `length` | YES | _float_ | The length of the shipment in cms. | 10 | | `breadth` | YES | _float_ | The breadth of the shipment in cms. | 15 | | `height` | YES | _float_ | The height of the shipment in cms. | 20 | | `weight` | YES | _float_ | The shipment weight in kgs. | 1 |  #### <u><b>Possible return_reason values</b></u><u>:</u>  ``` 1. Bought by Mistake 2. Better price available 3. Performance or quality not adequate 4. Incompatible or not useful 5. Product damaged, but shipping box OK 6. Item arrived too late 7. Missing parts or accessories 8. Both product and shipping box damaged 9. Wrong item was sent 10. Item defective or doesn\'t work 11. No longer needed 12. Didn\'t approve purchase 13. Inaccurate website description 14. Return against replacement 15. Delay Refund 16. Delivered Late 17. Product does not Match Description on Website 18. Both Product & Outer Box Damaged 19. Defective or does not work 20. Product damaged, but outer Box OK 21. Missing Parts or Accessories 22. Incorrect Item Delivered 23. Product Defective or Doesn\'t Work 24. Product performance/quality is not up to my expectations 25. Other 26. Changed my mind 27. Does not fit 28. Size not as expected 29. Item is damaged 30. Received wrong item 31. Parcel damaged on arrival 32. Quality not as expected 33. Missing Item or accessories 34. Performance not adequate 35. Not as described 36. Arrived too late 37. Order Not Received 38. Empty Package 39. Wrong item or Wrong colour was sent 40. Item defective, expired, spoilt or does not work 41. Items or parts missing 42. Size or Quantity issues 43. Status as delivered but order not received 44. N/A   ```

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersCreateReturnPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalOrdersCreateReturnPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**422** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersEditPost**
> V1ExternalOrdersEditPost200Response v1ExternalOrdersEditPost()

Use this API to update your return orders. Please specify the parameters based on the \"action\" key.  #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `order_id` | YES | _string_ | Your return order ID | R_1231234 | | `action` | YES | _string_ | Pass array of action. Allowed actions:  <br>`1. product_details: Allows you to edit the weight and dimensions`  <br>`2. warehouse_address: Allows you to change the return address` | \"action\": \\[\"product_details\"\\] | | `length` | CONDITIONAL YES | _float_ | The length of the item in cms. Must be more than 0.5 | 12 | | `breadth` | CONDITIONAL YES | _float_ | The breadth of the item in cms. Must be more than 0.5 | 23 | | `height` | CONDITIONAL YES | _float_ | The height of the item in cms. Must be more than 0.5 | 30 | | `weight` | CONDITIONAL YES | _float_ | The weight of the item in kgs. Must be more than 0. | 10 | | `return_warehouse_id` | CONDITIONAL YES | _integer_ | Id of pickup location | 213443 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersEditPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalOrdersEditPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersExportPost**
> V1ExternalOrdersExportPost200Response v1ExternalOrdersExportPost()

This API downloads and creates a CSV file of all the orders in your Shiprocket account and sends the download URL to the linked email account of the API user.  The CSV file containing is accessible via this URL. No parameters are required to access this API.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)
let body: object; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersExportPost(
    contentType,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalOrdersExportPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json, */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**502** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersFulfillPatch**
> Array<V1ExternalOrdersFulfillPatch200ResponseInner> v1ExternalOrdersFulfillPatch()

Use this API to add inventory for ordered products that are out of stock or low on quantity. You have to pass the order id and order product id. You can also specify the number of items.  **Notes:** - Inventory sync of your account must be turned on to use this API. - The order_id to be passed is the shiprocket order id. If you don\'t know the product id, Use the \'Get Product Details\' API to get details about all the existing products.  #### Parameters:  |    **PARAMS**     | **REQUIRED**  |  **DATA TYPE**  |                 **DESCRIPTION**                  | **EXAMPLE**  | |:----------------: |:------------: |:--------------: |:-----------------------------------------------: |:-----------: | |     `order_id`      |      YES      |    *integer*    | The Shiprocket order_id specified to the order.  |   16167171   | | `order_product_id`  |      YES      |    *integer*    |    The product id of the product to be added.    |   17171717   | |     `quantity`      |      YES      | *string*        | The number of items you want to add.             | 10           | |      `action`       |      YES      | *string*        | The action you want to carry out. Is \'add\'.      | add          |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersFulfillPatch(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**Array<V1ExternalOrdersFulfillPatch200ResponseInner>**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersImportPost**
> V1ExternalOrdersImportPost200Response v1ExternalOrdersImportPost()

Use this API to import orders in bulk to your Shiprocket account from an existing \'.csv\' file. The imported orders are automatically added to your panel.  

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)
let file: File; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalOrdersImportPost(
    contentType,
    file
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|
| **file** | [**File**] |  | defaults to undefined|


### Return type

**V1ExternalOrdersImportPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |
|**422** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersMappingPatch**
> Array<V1ExternalOrdersMappingPatch200ResponseInner> v1ExternalOrdersMappingPatch()

This API maps your unmapped inventory products.   **Note:** - Products must be unmapped to run this API successfully. - Inventory sync must be turned on to use this API.  #### Parameters:  |    **PARAMS**     | **REQUIRED**  |  **DATA TYPE**  |                                                                            **DESCRIPTION**                                                                            | **EXAMPLE**  | |:----------------: |:------------: |:--------------: |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------: |:-----------: | |     `order_id`      |      YES      |    *integer*    |                                                            The Shiprocket order_id specified to the order.                                                            |   16167171   | | `order_product_id`  |      YES      |    *integer*    |                                                              The product id of the product to be mapped.                                                              |   17171717   | |    `master_sku`     |      YES      |    *string*     |  The sku id of the product. In the case of a single integrated channel, master sku is the same as channel_sku; Otherwise, it can be found using the \'Get All Products\' API.  |  chakra123   |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersMappingPatch(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**Array<V1ExternalOrdersMappingPatch200ResponseInner>**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersPrintInvoicePost**
> V1ExternalOrdersPrintInvoicePost200Response v1ExternalOrdersPrintInvoicePost()

Use this API to generate the invoice for your order by passing the respective Shiprocket order ids.  The generated invoice URL is displayed as a response. Multiple ids can be passed together as an array.  **Note** - Order ids must be passed as an array.  #### Parameters:  | **PARAMS**  | **REQUIRED**  |  **DATA TYPE**  |                                                      **DESCRIPTION**                                                       |     **EXAMPLE**      | |:----------: |:------------: |:--------------: |:-------------------------------------------------------------------------------------------------------------------------: |:-------------------: | |     `ids`     |      YES      |    *integer*    |  The Shiprocket order id of the orders whose invoices are to be created. Multiple ids can be passed together as an array.  | [16255275,16255276]  |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersPrintInvoicePost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalOrdersPrintInvoicePost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |
|**500** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalOrdersUpdateAdhocPost**
> V1ExternalOrdersUpdateAdhocPost200Response v1ExternalOrdersUpdateAdhocPost()

Use this API to update your orders. You have to pass all the required params at the minimum to create a quick custom order. You can add additional parameters as per your preference.  You can update only the order_items details before assigning the AWB (before Ready to Ship status). You can only update these key-value pairs i.e., increase/decrease the quantity, update tax/discount, add/remove product items. We\'ve also enabled changing the nature of the order from a non-document to a document. You jus t need to pass the is_document key with the value of 1 in the payload.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalOrdersUpdateAdhocPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalOrdersUpdateAdhocPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalProductsGet**
> V1ExternalProductsGet200Response v1ExternalProductsGet()

This API can be used to display a detailed list of all the products that you have in your Shiprocket account.  There are no required parameters to access this API. However, the displayed result can be filtered or sorted using additional parameters.  #### Parameters:  | **PARAMS**  | **REQUIRED**  |  **DATA TYPE**  |                                                       **DESCRIPTION**                                                       | **EXAMPLE**  | |:----------: |:------------: |:--------------: |:--------------------------------------------------------------------------------------------------------------------------: |:-----------: | |    `page`     |      NO       |    *integer*    |                                            The page number you want to display.                                             |      5       | |  `per_page`   |      NO       |    *integer*    |                                           The number of products to get per page.                                           |      2       | |    `sort`     |      NO       |    *string*     |                                        The order to sort by. Value: *ASC* or *DESC*                                         |     ASC      | |  ` sort_by`   |      NO       |    *string*     |  Allows you to choose the value field by which the items will be sorted.  Could be sorted by id, by sku, time created etc.  |     sku      | |   `filter`    |      NO       |    *string*     |                                        The data to be matched for the filter value.                                         |   11223344   | |  `filter_by`  |      NO       |    *string*     |                                        The filter value field . Can be id, sku, etc.                                        |      id      |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalProductsGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalProductsGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalProductsImportPost**
> V1ExternalOrdersImportPost200Response v1ExternalProductsImportPost()

Use this API to import your products in bulk from a .csv file.   No parameters are required. Choose the target file as required. You will receive an import id upon successful import operation.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)
let file: File; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalProductsImportPost(
    contentType,
    file
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|
| **file** | [**File**] |  | defaults to undefined|


### Return type

**V1ExternalOrdersImportPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**422** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalProductsPost**
> object v1ExternalProductsPost()

Use this API to add a new product to your Shiprocket account.   Provide the required product details and any additional info to successfully add a new product to your product list.  **Notes:**  - \'sku\' Id has to be unique. It cannot be the same as an existing sku.      - In case no category code is added, the code should be default.      - \'type\' field should be either \'single\' or \'multiple.\'       #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `sku` | YES | _string_ | Stock Keeping Unit or the identification unit of an individual product (generally alphanumeric). | bat123 | | `HSN` | NO | _string_ | Harmonised System Nomenclature. A code number is used to classify goods for taxation purposes. Done to determine which category of taxes do the goods come under. | 4412 | | `name` | YES | _string_ | Name of the product. | Batman Toy | | `tax_code` | NO | _string_ | The percentage of tax that is to be imposed. | 10 | | `type` | YES | _string_ | If there is only one product or multiple types of products. **Single** or **Multiple** | Single. | | `qty` | YES | _integer_ | Total Quantity of the products to be shipped. | 5 | | `low_stock` | NO | _string_ | Specifies when the low stock notification should come on | / | | `category_code` | YES | _string_ | You can add a category code to your ShipRocket account from “add category” | default | | `description` | NO | _string_ | Gives a description of the product. | Batman plastic toy. | | `brand` | NO | _string_ | The product brand name. | Bat | | `size` | NO | _integer_ | The size of the product. | 25 | | `weight` | NO | _integer_ | The weight of the product in kgs. | 0.5 | | `length` | NO | _integer_ | The length of the product in cms. | 10 | | `width` | NO | _integer_ | The width of the product in cms. | 5 | | `height` | NO | _integer_ | The height of the product in cms. | 15 | | `ean` | NO | _string_ | European Article Number - A barcode for product identification (which helps manufacturers identify how many products have been sold once a sale is made). It is 13 digits long and required for international selling. | / | | `upc` | NO | _string_ | Universal Product Code – Barcode for product identification which is used across the world. It is 12 digits long. | / | | `isbn` | NO | _string_ | International Standard Book Number – Identification barcode for books, magazines, e-books and other published media. It is 10 digits long. | / | | `color` | NO | _string_ | The colour of the product. | Black | | `imei_serialnumber` | NO | _string_ | The International Mobile Equipment Identity Number, which is used by a network to identify valid devices. E.g. if two iPhones have to be shipped, they will have 2 IMEI numbers | / | | `cost_price` | NO | _integer_ | The manufacture cost price of the product. | 500 | | `mrp` | NO | _string_ | Maximum Retail Price. How much is the maximum price which the product can be sold at. | 1000 | | `status` | NO | _boolean_ | In Boolean, if the product details have been successfully or unsuccessfully added. | 1 | | `image_url` | NO | _string_ | Shows the URL of the product images which have been uploaded. | / | | `qc_details` | NO | / | List of items and their relevant fields in the form of Array. | / | | `product_image` | CONDITIONAL YES | _string_ | Pickup agent will cross check theshared product with the actual product received from the buyer. Mandatory for all QC Products | [https://abc/xyz.jpg](https://abc/xyz.jpg) | | `brand` | CONDITIONAL YES | _string_ | The pickup agent will cross check the provided brand name visible on the item(s) or its packaging. | shiprocket | | `brand_tag` | CONDITIONAL YES | _string_ | The pickup agent will cross-check the provided brand name, which should match the brand tag affixed to the item(s) upon delivery. | shiprocket | | `color` | CONDITIONAL YES | _string_ | Pickup agent will cross check shared product color with the actual product received from the buyer. | green | | `size` | CONDITIONAL YES | _string_ | Pickup agent will cross check shared product size with the size on the label/tag. | L | | `product_imei` | CONDITIONAL YES | _string_ | It is a 15 digit unique number. It is displayed on the screen, on the box, or at the back of the appliance. This can be used to check production & garauntee of the appliance. | 0123456781234 | | `serial_no` | CONDITIONAL YES | _string_ | A serial number (SN) is a unique alphanumeric value assigned to each individual product. | 123456 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalProductsPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**object**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: */*, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** |  |  -  |
|**422** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalProductsQcProductUpdateProductIDPost**
> V1ExternalProductsQcProductUpdateProductIDPost200Response v1ExternalProductsQcProductUpdateProductIDPost()

Use this API to convert an existing product to a QC product. The {productID} will be the \"id\" from the \"[Get all products](https://apidocs.shiprocket.in/#0b8d1f26-3abd-4f4e-9cd8-3928bcfcf30b)\" or \"[Get specific product details](https://apidocs.shiprocket.in/#134f7710-660c-464f-b579-6da46ba9402f)\" API.  #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `sku` | YES | _string_ | Stock Keeping Unit or the identification unit of an individual product (generally alphanumeric). | bat123 | | `product_image` | YES | _string_ | Pickup agent will cross check shared product color with the actual product received from the buyer. Mandatory for all QC Products | [https://abc/xyz.jpg](https://abc/xyz.jpg) | | `serial_no` | NO | _string_ | A serial number (SN) is a unique alphanumeric value assigned to each individual product. | 12345 | | `size` | NO | _string_ | Pickup agent will cross check shared product size with the size on the label/tag. | L | | `color` | NO | _string_ | Pickup agent will cross check shared product color with the actual product received from the buyer. | Green | | `brand` | NO | _integer_ | The pickup agent will cross-check the provided brand name visible on the item(s) or its packaging. | shiprocket | | `brand_box` | NO | _string_ | The pickup agent will cross-check the provided brand name, which should match the brand tag affixed to the item(s) upon delivery | shiprocket | | `product_imei` | NO | _string_ | \"It is a 15-digit unique number. It is displayed on the screen, on the box, or at the back of the appliance. This can be used to check production & guarantee of the appliance. | 1234567890 |

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    V1ExternalProductsQcProductUpdateProductIDPostRequest
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let productID: string; // (default to undefined)
let contentType: string; // (default to undefined)
let authorization: string; // (optional) (default to undefined)
let v1ExternalProductsQcProductUpdateProductIDPostRequest: V1ExternalProductsQcProductUpdateProductIDPostRequest; // (optional)

const { status, data } = await apiInstance.v1ExternalProductsQcProductUpdateProductIDPost(
    productID,
    contentType,
    authorization,
    v1ExternalProductsQcProductUpdateProductIDPostRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **v1ExternalProductsQcProductUpdateProductIDPostRequest** | **V1ExternalProductsQcProductUpdateProductIDPostRequest**|  | |
| **productID** | [**string**] |  | defaults to undefined|
| **contentType** | [**string**] |  | defaults to undefined|
| **authorization** | [**string**] |  | (optional) defaults to undefined|


### Return type

**V1ExternalProductsQcProductUpdateProductIDPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalProductsSampleGet**
> object v1ExternalProductsSampleGet()

This API will provide a sample format for a CSV file that can be used for importing orders. You can use this format to create your CSV file, which you want to use to import products into your Shiprocket account.  No additional parameters are required.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalProductsSampleGet(
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**object**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalProductsShowProductIdGet**
> V1ExternalProductsShowProductIdGet200Response v1ExternalProductsShowProductIdGet()

Use this API to get the details of a specific product. The product details will be displayed in JSON format.  You need to pass the product id in the endpoint URL for the successful call of the API. No other body parameters are required.  #### Path:   |                 **EXAMPLE**                 | |:------------------------------------------: | | https://apiv2.shiprocket.in/v1/external/products/show/17484610            |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let productId: string; // (default to undefined)
let contentType: string; // (default to undefined)

const { status, data } = await apiInstance.v1ExternalProductsShowProductIdGet(
    productId,
    contentType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **productId** | [**string**] |  | defaults to undefined|
| **contentType** | [**string**] |  | defaults to undefined|


### Return type

**V1ExternalProductsShowProductIdGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**400** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalSettingsCompanyAddpickupPost**
> V1ExternalSettingsCompanyAddpickupPost200Response v1ExternalSettingsCompanyAddpickupPost()

This API can be used to add a new pickup location to your account.   Pass the minimum required parameters to add the location.   Further details to the address can be added if required.  #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `pickup_location` | YES | _string_ | The nickname of the new pickup location. Max 36 characters. | Home | | `name` | YES | _string_ | The shipper\'s name. | Deadpool | | `email` | YES | _string_ | The shipper\'s email address. | [deadpool@chimichanga.com](mailto:deadpool@chimichanga.com) | | `phone` | YES | _integer_ | Shipper\'s phone number. | 9777777779 | | `address` | YES | _string_ | Shipper\'s primary address. Max 80 characters. | Mutant Facility, Sector 3 | | `address_2` | NO | _string_ | Additional address details. | House number 34 | | `city` | YES | _string_ | Pickup location city name. | Pune | | `state` | YES | _string_ | Pickup location state name. | Maharashtra | | `country` | YES | _string_ | Pickup location country. | India | | `pin_code` | YES | _integer_ | Pickup location pincode. | 110022 | | `lat` | NO | _float_ | Pickup location Latitude. | 22.4064 | | `long` | NO | _float_ | Pickup location Longitude. | 69.0747 | | `address_type` | NO | _string_ | To be given if address of different vendor is to be provided with pickup address | vendor | | `vendor_name` | NO | _string_ | Name of vendor if address_type is vendor | John | | `gstin` | NO | _string_ | gstin of vendor | 09XXXCH7409R1XXX  <br> |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalSettingsCompanyAddpickupPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalSettingsCompanyAddpickupPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**422** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalSettingsCompanyPickupGet**
> V1ExternalSettingsCompanyPickupGet200Response v1ExternalSettingsCompanyPickupGet()

Get a list of all pickup locations that have been added to your Shiprocket account through this API.  No parameters are required to use this API.

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.v1ExternalSettingsCompanyPickupGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**V1ExternalSettingsCompanyPickupGet200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**404** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalShipmentsCreateForwardShipmentPost**
> V1ExternalShipmentsCreateForwardShipmentPost200Response v1ExternalShipmentsCreateForwardShipmentPost()

Use this API to do multiple tasks in one go, namely creating a quick order, requesting its shipment, and finally generating the label and the manifest for the same order.  This API integrates several other APIs to perform all these tasks together.  **Notes:**  - Use the \'vendor_details\' array to add a new pickup location to your account and assign it to your order.      - The \'pickup_location\' field must contain a new pickup location name for adding a new pickup location to your Shiprocket account.      - In case of multiple items per order, please pass the final weight (sum total weight of items) of the shipment.       #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `mode` | NO | _string_ | The mode of shipment, either surface or air. _Value_: **Surface** or **Air** | Air | | `request_pickup` | NO | _boolean_ | Use false if you dont want to request pickup. Default value is true. | true | | `print_label` | NO | _boolean_ | Use false if you dont want to print label. Default value is true. | true | | `generate_manifest` | NO | _boolean_ | Use false if you dont want to generate manifest. Default value is true. | true | | `ewaybill_no` | NO | _string_ | Details relating to the shipment of goods. | K92373490 | | `courier_id` | NO | _integer_ | The courier id of the courier you want to assign. Refer to the servicability API to get id. | 10 | | `reseller_name` | NO | _string_ | The \'from\' name if you want to print. Use \'Reseller: \\[name\\]\' | Reseller: Divine | | `order_id` | YES | _string_ | The custom reference id you want to assign to the order. | 2477 | | `isd_code` | NO | _string_ | The isd code | 91 | | `billing_isd_code` | NO | _string_ | The billing isd code. | 91 | | `order_date` | YES | _string_ | The date of the creation of order. | 2019-08-04 | | `channel_id` | NO | _string_ | The channel id of the specific channel. Use the Channels API to get id. | 72505 | | `company_name` | NO | _string_ | Name of the company. | Amazon | | `billing_customer_name` | YES | _string_ | The first name of customer to be billed. | John | | `billing_last_name` | NO | _string_ | The last name of the billing customer. | Doe | | `billing_address` | YES | _string_ | The primary billing address. | House no 21 | | `billing_address_2` | NO | _string_ | Additional billing address details. | Street 2, Dwarka | | `billing_city` | YES | _string_ | The billing city. | Delhi | | `billing_state` | YES | _string_ | The billing address state. | New Delhi | | `billing_country` | YES | _string_ | The billing address country. | India | | `billing_pincode` | YES | _integer_ | The pincode of the billing address. | 110002 | | `billing_email` | YES | _string_ | The billing customer email. | [john@doe.com](https://mailto:john@doe.com) | | `billing_phone` | YES | _integer_ | The billing customer phone. | 9999998899 | | `billing_alternate_phone` | NO | _integer_ | The billing customer alternate phone. | 8404690454 | | `shipping_is_billing` | YES | _boolean_ | Whether shipping details are the same as billing details. **true** for yes **false** for no. | true | | `shipping_customer_name` | CONDITIONAL YES | _string_ | Shipping customer\'s first name. | Jane | | `shipping_last_name` | NO | _string_ | Shipping customer\'s last name. | Doe | | `shipping_address` | CONDITIONAL YES | _string_ | The shipping address. | House no X | | `shipping_address_2` | NO | _string_ | Additional shipping address details. | Street X | | `shipping_city` | CONDITIONAL YES | _string_ | The shipping city. | Mumbai | | `shipping_state` | CONDITIONAL YES | _string_ | The state of the shipping address. | Maharashtra | | `shipping_country` | CONDITIONAL YES | _string_ | The shipping address country. | India | | `shipping_pincode` | CONDITIONAL YES | _integer_ | Shipping pincode. | 230023 | | `shipping_email` | CONDITIONAL YES | _string_ | The email of the shipping customer. | [Jane@Doe.com](https://mailto:Jane@Doe.com) | | `shipping_phone` | CONDITIONAL YES | _integer_ | The phone number of the shipping customer. | 8877997799 | | `order_items` | YES | / | Array containing further parameters. | / | | `name` | YES | _string_ | The name of the product. | Jeans | | `sku` | YES | _string_ | sku Code of the product. | Bat | | `units` | YES | _integer_ | Number of units. | 10 | | `hsn` | NO | _integer_ | HSN code if available. | 4412 | | `selling_price` | YES | _integer_ | The selling price of each unit inclusive of GST. | 200 | | `tax` | NO | _integer_ | The tax applied in percent. | 20 | | `discount` | NO | _integer_ | The discount amount inclusive of tax. | 20 | | `payment_method` | YES | _string_ | If the payment method is Cash on delivery (**COD**) or **Prepaid**. | COD | | `shipping_charges` | NO | _integer_ | The shipping charges if any in rupees. | 5 | | `giftwrap_charges` | NO | _integer_ | The gift-wrap charges if any in rupees. | 5 | | `transaction_charges` | NO | _integer_ | The transaction charges if any in rupees. | 10 | | `total_discount` | NO | _integer_ | The discount amount in rupees. | 15 | | `sub_total` | YES | _integer_ | The sub total amount in rupees. | 1800 | | `weight` | YES | _string_ | The weight of the shipment in kgs. | 2 | | `length` | YES | _integer_ | The length of the shipment in cms. Must be more than 0.5 | 10 | | `breadth` | YES | _integer_ | The breadth of the shipment in cms. Must be more than 0.5 | 15 | | `height` | YES | _integer_ | The height of the shipment in cms. Must be more than 0.5 | 20 | | `pickup_location` | YES | _string_ | The pickup location name. Equal to an existing pickup location. If you use \'vendor details\' to add a new location, it must be equal to the new pickup location name. | Office | | `customer_gstin` | NO | _string_ | Goods and Services Tax Identification Number. | 29ABCDE1234F2Z5 | | `vendor_details` | NO | / | Array containing further parameters. Use to assign/add a new pickup location to your account. | / | | `email` | CONDITIONAL YES | _string_ | The shipper\'s email address. | [john@doe.com](https://mailto:john@doe.com) | | `phone` | CONDITIONAL YES | _integer_ | The shipper\'s phone number. | 8888999888 | | `name` | CONDITIONAL YES | _string_ | The shipper\'s name. | John Doe | | `address` | CONDITIONAL YES | _string_ | The pickup location address. Min 10 characters. | Office Building | | `address_2` | NO | _string_ | Additional address details. Min 10 characters. | Street 2 house 4 | | `city` | CONDITIONAL YES | _string_ | The pickup location city. | Pune | | `state` | CONDITIONAL YES | _string_ | The pickup state. | Maharashtra | | `country` | CONDITIONAL YES | _string_ | The pickup location country. | India | | `pin_code` | CONDITIONAL YES | _integer_ | The pickup pincode. | 200099 | | `pickup_location` | CONDITIONAL YES | _string_ | New pickup location name. Max: 36 char. Alphanumeric only. | New Office | | `order_type` | NO | _string_ | Key to differentiate between Essentials or Non Essentials Shipments. Order type can only be ESSENTIALS or NON ESSENTIALS. Please note it is case sensitive and blank values are allowed | ESSENTIALS | | `longitude` | NO | _float_ | Destination (Shipping address) Longitude. | 69.0747 | | `latitude` | NO | _float_ | Destination (Shipping address) Latitude | 22.4064 | | `what3words_address` | NO | _string_ | What3words is a proprietary geocode system designed to identify any location on the surface of Earth with a resolution of about 3 meters. The system encodes geographic coordinates into three permanently fixed dictionary words. | toddler.geologist.animated | | `is_document` | NO | _integer_ | To create a document order | 1 or 0 |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalShipmentsCreateForwardShipmentPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**V1ExternalShipmentsCreateForwardShipmentPost200Response**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |
|**422** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **v1ExternalShipmentsCreateReturnShipmentPost**
> object v1ExternalShipmentsCreateReturnShipmentPost()

Use this API to perform multiple tasks like Create, AWB generation & scheduling reverse pickups for your Returns.   The specifications are the same as the custom return order API, with a few exceptions.  **Notes:**  - pickup_location field is not required.      - Label and Manifest are not required in case of returns.       #### Parameters:  | **PARAMS** | **REQUIRED** | **DATA TYPE** | **DESCRIPTION** | **EXAMPLE** | | --- | --- | --- | --- | --- | | `order_id` | YES | _string_ | The order id you want to specify to the order. Max char: 50. (Avoid passing character values as this contradicts some other API calls) | 99711997 | | `order_date` | YES | _string_ | The date of order creation in yyyy-mm-dd format. Time is an additional option. | 2019-08-05 | | `channel_id` | NO | _integer_ | Id of the desired channel where the order is to be placed. \'Custom\' channel id is selected in case parameter is not filled. | 768903 | | `pickup_customer_name` | YES | _string_ | The customer’s first name. | John | | `pickup_last_name` | NO | _string_ | The customer’s last name. | Doe | | `company_name` | NO | _string_ | Name of the company | Amazon | | `pickup_address` | YES | _string_ | The customer\'s primary address. | Home | | `pickup_address_2` | NO | _string_ | Additional customer address details. | DDA | | `pickup_city` | YES | _string_ | The customer\'s city name. | Delhi | | `pickup_state` | YES | _string_ | The customer\'s state. | New Delhi | | `pickup_country` | YES | _string_ | Customer\'s country name. | India | | `pickup_pincode` | YES | _integer_ | Pincode of the customer address. | 110002 | | `pickup_email` | YES | _string_ | Customer\'s email address. | [john@doe.com](https://mailto:john@doe.com) | | `pickup_phone` | YES | _string_ | Customer\'s phone number. | 9999999999 | | `pickup_isd_code` | NO | _string_ | ISD code. | 91 | | `shipping_customer_name` | YES | _string_ | The name of the seller the package is shipped back to. | Jane | | `shipping_last_name` | NO | _string_ | The last name of the seller. | Doe | | `shipping_address` | YES | _string_ | The address the package is shipped to. | Castle | | `shipping_address_2` | NO | _string_ | Further shipping address details. | Bridge | | `shipping_city` | YES | _string_ | The shipping address city. | Mumbai | | `shipping_country` | YES | _string_ | The shipping address country. | India | | `shipping_pincode` | YES | _integer_ | The shipping pincode. | 220022 | | `shipping_state` | YES | _string_ | Shipping address state. | Maharashtra | | `shipping_email` | YES | _string_ | The email of the seller the package is shipped to. | [jane@doe.com](https://mailto:jane@doe.com) | | `shipping_isd_code` | NO | _string_ | The shipping isd code. | 91 | | `shipping_phone` | YES | _integer_ | Phone no. of the shipping customer | 8888888888 | | `order_items` | YES | / | Array containing further fields. | / | | `name` | YES | _string_ | Name of the product. | ball123 | | `sku` | YES | _string_ | The sku id of the product. | Tennis Ball | | `units` | YES | _integer_ | No of units that are to be shipped. | 1 | | `selling_price` | YES | _integer_ | The selling price per unit in Rupee. Inclusive of GST. | 10 | | `discount` | NO | _integer_ | The discount amount in Rupee. Inclusive of tax. | 0 | | `hsn` | NO | _string_ | Harmonised System Nomenclature code. Used to determine the category of taxation the goods fall under. | 4412 | | `qc_enable` | CONDITIONAL YES | _string_ | If True, QC will be performed for that product and QC will be performed only for a single SKU per order | TRUE/FALSE | | `qc_color` | NO | _varchar(180)_ | The color of the product can be passed in this parameter | Red | | `qc_brand` | NO | _varchar(255)_ | The brand of the product can be passed in this parameter | 768903 | | `qc_serial_no` | NO | _varchar(255)_ | The serial number of the product can be passed in this parameter | T13123124 | | `qc_ean_barcode` | NO | _varchar(255)_ | EAN/Barcode of the product can be passed in this parameter | QWRE123 | | `qc_size` | NO | _varchar(180)_ | The size of the product can be passed in this parameter | 8 | | `qc_product_name` | CONDITIONAL YES | _varchar(255)_ | If qc_enable set True, then Product name should be passed in this parameter | Shoes | | `qc_product_image` | CONDITIONAL YES | _varchar(255)_ | If qc_enable set True, then Product image should be passed in this parameter (only png/jpg format supported) | [https://s3-ap-southeast-1.amazonaws.com/kr-multichannel/1636713733zxja.png](https://s3-ap-southeast-1.amazonaws.com/kr-multichannel/1636713733zxja.png) | | `qc_product_imei` | NO | _varchar(255)_ | IMEI of the device | 86532976457823 | | `payment_method` | YES | _string_ | The method of payment. Can be either COD (Cash on delivery) Or Prepaid. | Prepaid | | `total_discount` | NO | _string_ | The total discount amount in Rupee. | 0 | | `sub_total` | YES | _integer_ | Calculated sub total amount in Rupee after deductions. | 10 | | `length` | YES | _integer_ | The length of the shipment in cms. | 10 | | `breadth` | YES | _integer_ | The breadth of the shipment in cms. | 15 | | `height` | YES | _integer_ | The height of the shipment in cms. | 20 | | `weight` | YES | _integer_ | The shipment weight in kgs. | 1 | | `request_pickup` | NO | _boolean_ | Use false if you dont want to request pickup. Default value is true. | true |

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let body: string; // (optional)

const { status, data } = await apiInstance.v1ExternalShipmentsCreateReturnShipmentPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **string**|  | |


### Return type

**object**

### Authorization

[bearer](../README.md#bearer)

### HTTP request headers

 - **Content-Type**: text/plain
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** |  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

