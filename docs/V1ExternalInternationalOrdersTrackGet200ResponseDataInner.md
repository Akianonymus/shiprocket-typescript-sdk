# V1ExternalInternationalOrdersTrackGet200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **number** |  | [default to undefined]
**channel_id** | **number** |  | [default to undefined]
**channel_name** | **string** |  | [default to undefined]
**base_channel_code** | **string** |  | [default to undefined]
**channel_order_id** | **string** |  | [default to undefined]
**customer_name** | **string** |  | [default to undefined]
**customer_email** | **string** |  | [default to undefined]
**customer_phone** | **string** |  | [default to undefined]
**customer_address** | **string** |  | [default to undefined]
**customer_address_2** | **string** |  | [default to undefined]
**customer_city** | **string** |  | [default to undefined]
**customer_state** | **string** |  | [default to undefined]
**customer_pincode** | **string** |  | [default to undefined]
**customer_country** | **string** |  | [default to undefined]
**customer_latitude** | **any** |  | [default to undefined]
**customer_longitude** | **any** |  | [default to undefined]
**customer_alternate_phone** | **string** |  | [default to undefined]
**pickup_location** | **string** |  | [default to undefined]
**package_instructions** | **any** |  | [default to undefined]
**order_type** | **number** |  | [default to undefined]
**payment_status** | **string** |  | [default to undefined]
**total** | **string** |  | [default to undefined]
**tax** | **string** |  | [default to undefined]
**sla** | **string** |  | [default to undefined]
**shipping_method** | **string** |  | [default to undefined]
**expedited** | **number** |  | [default to undefined]
**status** | **string** |  | [default to undefined]
**status_code** | **number** |  | [default to undefined]
**awd_etds** | **any** |  | [default to undefined]
**master_status** | **string** |  | [default to undefined]
**payment_method** | **string** |  | [default to undefined]
**change_payment_mode** | **boolean** |  | [default to undefined]
**is_international** | **number** |  | [default to undefined]
**purpose_of_shipment** | **number** |  | [default to undefined]
**channel_created_at** | **string** |  | [default to undefined]
**created_at** | **string** |  | [default to undefined]
**updated_at** | **string** |  | [default to undefined]
**pickup_boy_name** | **string** |  | [default to undefined]
**pickup_boy_contact_no** | **string** |  | [default to undefined]
**products** | [**Array&lt;V1ExternalInternationalOrdersTrackGet200ResponseDataInnerProductsInner&gt;**](V1ExternalInternationalOrdersTrackGet200ResponseDataInnerProductsInner.md) |  | [default to undefined]
**shipments** | [**Array&lt;V1ExternalInternationalOrdersTrackGet200ResponseDataInnerShipmentsInner&gt;**](V1ExternalInternationalOrdersTrackGet200ResponseDataInnerShipmentsInner.md) |  | [default to undefined]
**cod** | **number** |  | [default to undefined]
**activities** | **Array&lt;string&gt;** |  | [default to undefined]
**allow_return** | **number** |  | [default to undefined]
**is_incomplete** | **number** |  | [default to undefined]
**errors** | **Array&lt;string&gt;** |  | [default to undefined]
**pickup_exception_reason** | **string** |  | [default to undefined]
**rto_prediction** | **string** |  | [default to undefined]
**show_escalation_btn** | **number** |  | [default to undefined]
**escalation_status** | **string** |  | [default to undefined]
**pii_removed** | **number** |  | [default to undefined]
**allow_multiship** | **boolean** |  | [default to undefined]
**others** | [**V1ExternalInternationalOrdersTrackGet200ResponseDataInnerOthers**](V1ExternalInternationalOrdersTrackGet200ResponseDataInnerOthers.md) |  | [default to undefined]
**package_list** | [**V1ExternalInternationalOrdersTrackGet200ResponseDataInnerPackageList**](V1ExternalInternationalOrdersTrackGet200ResponseDataInnerPackageList.md) |  | [default to undefined]
**pickup_address_detail** | [**V1ExternalInternationalOrdersTrackGet200ResponseDataInnerPickupAddressDetail**](V1ExternalInternationalOrdersTrackGet200ResponseDataInnerPickupAddressDetail.md) |  | [default to undefined]
**rto_address** | **Array&lt;string&gt;** |  | [default to undefined]
**re_escalate** | **number** |  | [default to undefined]
**seller_request** | [**V1ExternalInternationalOrdersTrackGet200ResponseDataInnerSellerRequest**](V1ExternalInternationalOrdersTrackGet200ResponseDataInnerSellerRequest.md) |  | [default to undefined]
**engage** | **string** |  | [default to undefined]
**total_dead_weight** | **any** |  | [default to undefined]
**total_volumetric_weight** | **any** |  | [default to undefined]
**total_order_value** | **any** |  | [default to undefined]
**boxes** | **any** |  | [default to undefined]
**order_tag** | **Array&lt;string&gt;** |  | [default to undefined]
**is_return** | **number** |  | [default to undefined]
**is_b2b** | **boolean** |  | [default to undefined]
**is_insurance_opt** | **boolean** |  | [default to undefined]
**manifest_id** | **string** |  | [default to undefined]
**manifest_generated** | **boolean** |  | [default to undefined]
**awb_data** | [**V1ExternalInternationalOrdersTrackGet200ResponseDataInnerAwbData**](V1ExternalInternationalOrdersTrackGet200ResponseDataInnerAwbData.md) |  | [default to undefined]
**escalation_history** | **Array&lt;string&gt;** |  | [default to undefined]

## Example

```typescript
import { V1ExternalInternationalOrdersTrackGet200ResponseDataInner } from './api';

const instance: V1ExternalInternationalOrdersTrackGet200ResponseDataInner = {
    id,
    channel_id,
    channel_name,
    base_channel_code,
    channel_order_id,
    customer_name,
    customer_email,
    customer_phone,
    customer_address,
    customer_address_2,
    customer_city,
    customer_state,
    customer_pincode,
    customer_country,
    customer_latitude,
    customer_longitude,
    customer_alternate_phone,
    pickup_location,
    package_instructions,
    order_type,
    payment_status,
    total,
    tax,
    sla,
    shipping_method,
    expedited,
    status,
    status_code,
    awd_etds,
    master_status,
    payment_method,
    change_payment_mode,
    is_international,
    purpose_of_shipment,
    channel_created_at,
    created_at,
    updated_at,
    pickup_boy_name,
    pickup_boy_contact_no,
    products,
    shipments,
    cod,
    activities,
    allow_return,
    is_incomplete,
    errors,
    pickup_exception_reason,
    rto_prediction,
    show_escalation_btn,
    escalation_status,
    pii_removed,
    allow_multiship,
    others,
    package_list,
    pickup_address_detail,
    rto_address,
    re_escalate,
    seller_request,
    engage,
    total_dead_weight,
    total_volumetric_weight,
    total_order_value,
    boxes,
    order_tag,
    is_return,
    is_b2b,
    is_insurance_opt,
    manifest_id,
    manifest_generated,
    awb_data,
    escalation_history,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
