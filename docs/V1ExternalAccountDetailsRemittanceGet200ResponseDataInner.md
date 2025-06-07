# V1ExternalAccountDetailsRemittanceGet200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_at** | **number** |  | [default to undefined]
**crf_id** | **number** |  | [default to undefined]
**utr** | **string** |  | [default to undefined]
**utr_icod** | **any** |  | [default to undefined]
**recharge_value** | **string** |  | [default to undefined]
**reversal_value** | **string** |  | [default to undefined]
**remitted_value** | **string** |  | [default to undefined]
**deduction_value** | **string** |  | [default to undefined]
**cod_payble** | **string** |  | [default to undefined]
**account_type** | **string** |  | [default to undefined]
**maintained_balance_limit** | **any** |  | [default to undefined]
**status** | **string** |  | [default to undefined]
**remarks** | **string** |  | [default to undefined]
**adjustment_data** | [**V1ExternalAccountDetailsRemittanceGet200ResponseDataInnerAdjustmentData**](V1ExternalAccountDetailsRemittanceGet200ResponseDataInnerAdjustmentData.md) |  | [default to undefined]
**legal_penal_amount** | **string** |  | [default to undefined]
**legal_penal_invoices** | **Array&lt;string&gt;** |  | [default to undefined]
**remitted_value_icod** | **string** |  | [default to undefined]
**remitted_value_std** | **number** |  | [default to undefined]
**icod_vrf_id** | **any** |  | [default to undefined]
**vrf_ids** | **string** |  | [default to undefined]
**vrf_utr** | **string** |  | [default to undefined]
**remittance_amount** | [**Array&lt;V1ExternalAccountDetailsRemittanceGet200ResponseDataInnerRemittanceAmountInner&gt;**](V1ExternalAccountDetailsRemittanceGet200ResponseDataInnerRemittanceAmountInner.md) |  | [default to undefined]

## Example

```typescript
import { V1ExternalAccountDetailsRemittanceGet200ResponseDataInner } from './api';

const instance: V1ExternalAccountDetailsRemittanceGet200ResponseDataInner = {
    created_at,
    crf_id,
    utr,
    utr_icod,
    recharge_value,
    reversal_value,
    remitted_value,
    deduction_value,
    cod_payble,
    account_type,
    maintained_balance_limit,
    status,
    remarks,
    adjustment_data,
    legal_penal_amount,
    legal_penal_invoices,
    remitted_value_icod,
    remitted_value_std,
    icod_vrf_id,
    vrf_ids,
    vrf_utr,
    remittance_amount,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
