# GetAllOrders200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **number** |  | [optional] [default to undefined]
**channel_id** | **number** |  | [optional] [default to undefined]
**channel_name** | **string** |  | [optional] [default to undefined]
**base_channel_code** | **string** |  | [optional] [default to undefined]
**channel_order_id** | **string** |  | [optional] [default to undefined]
**customer_name** | **string** |  | [optional] [default to undefined]
**customer_email** | **string** |  | [optional] [default to undefined]
**customer_phone** | **string** |  | [optional] [default to undefined]
**pickup_location** | **string** |  | [optional] [default to undefined]
**payment_status** | **string** |  | [optional] [default to undefined]
**total** | **string** |  | [optional] [default to undefined]
**tax** | **string** |  | [optional] [default to undefined]
**sla** | **string** |  | [optional] [default to undefined]
**shipping_method** | **string** |  | [optional] [default to undefined]
**expedited** | **number** |  | [optional] [default to undefined]
**status** | **string** |  | [optional] [default to undefined]
**status_code** | **number** |  | [optional] [default to undefined]
**payment_method** | **string** |  | [optional] [default to undefined]
**is_international** | **number** |  | [optional] [default to undefined]
**purpose_of_shipment** | **number** |  | [optional] [default to undefined]
**channel_created_at** | **string** |  | [optional] [default to undefined]
**created_at** | **string** |  | [optional] [default to undefined]
**products** | [**Array&lt;GetAllOrders200ResponseDataInnerProductsInner&gt;**](GetAllOrders200ResponseDataInnerProductsInner.md) |  | [optional] [default to undefined]
**shipments** | [**Array&lt;GetAllOrders200ResponseDataInnerShipmentsInner&gt;**](GetAllOrders200ResponseDataInnerShipmentsInner.md) |  | [optional] [default to undefined]
**activities** | **Array&lt;string&gt;** |  | [optional] [default to undefined]
**allow_return** | **number** |  | [optional] [default to undefined]
**is_incomplete** | **number** |  | [optional] [default to undefined]
**errors** | **Array&lt;string&gt;** |  | [optional] [default to undefined]
**show_escalation_btn** | **number** |  | [optional] [default to undefined]
**escalation_status** | **string** |  | [optional] [default to undefined]
**escalation_history** | **Array&lt;string&gt;** |  | [optional] [default to undefined]

## Example

```typescript
import { GetAllOrders200ResponseDataInner } from './api';

const instance: GetAllOrders200ResponseDataInner = {
    id,
    channel_id,
    channel_name,
    base_channel_code,
    channel_order_id,
    customer_name,
    customer_email,
    customer_phone,
    pickup_location,
    payment_status,
    total,
    tax,
    sla,
    shipping_method,
    expedited,
    status,
    status_code,
    payment_method,
    is_international,
    purpose_of_shipment,
    channel_created_at,
    created_at,
    products,
    shipments,
    activities,
    allow_return,
    is_incomplete,
    errors,
    show_escalation_btn,
    escalation_status,
    escalation_history,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
