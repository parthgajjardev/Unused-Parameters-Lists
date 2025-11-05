# Unused-Parameters-Lists


## **`1️⃣ RFQ (Request for Quotation)`**

# Unused Parameters

> List of Unused Parameters from this API (Pagination Table API) - **`customer/requestQuotation/getRFQlist`**
 

| **Parameter** | **Used / Unused** |
| --- | --- |
| `vendor_email_ids` | `Unused` |
| `rfq_type` | `Unused` |
| `purchase_group_id` | `Unused` |
| `category_ids` | `Unused` |
| `currency_detail` | `Unused` |
| `technical_emp_id` | `Unused` |
| `mail_text` | `Unused` |
| `technical_emp_detail` | `Unused` |
| `comparitive_reports` | `Unused` |
| `po_attachments` | `Unused` |

---

> List of Unused Parameters from this API **- `customer/requestQuotation/getDeleteRequestQuotation`**


| **Parameter** | **Used / Unused** |
| --- | --- |
| `rfq_type` | `Unused` |
| `purchase_group_id` | `Unused` |
| `created_by` | `Unused` |
| `currency_detail` | `Unused` |
| `category_ids` | `Unused` |
| `negotiation_deadlinedate` | `Unused` |

### Vendor Portal PDF API’s

`vendor/requestQuotation/listRfq`

`vendor/requestQuotation/listRfqVendorDetails`

`vendor/arcContractOrder/getVendorPurchaseOrderLists`

`vendor/arcQuotation/listRfq`

`vendor/purchaseRequestOrder/getVendorPurchaseOrderLists`

`vendor/invoices/getVendorInvoiceList`

`vendor/rev-auc/list_auctions`

`vendor/rev-auc/details`

`vendor/tender/list_tender`

### Customer Portal PDF API’s

`customer/purchaseRequest/getPurchaseRequestLists`

`customer/purchaseRequest/getPurchaseRequestDetails`

`customer/purchaseRequest/getDeletedPurchaseRequestLists`

`customer/requestQuotation/getWorkflowRequestQuotationRecords`

`customer/requestQuotation/getRFQlist`

`customer/purchaseRequestOrder/getWorkflowGRNPORecords`

`customer/purchaseRequestOrder/ComparisionPOApproverHistory`

`customer/arcQuotation/getWorkflowRequestQuotationRecords`

`customer/arcQuotation/getRFQlist`

`customer/arcContractOrder/getWorkflowPORecords`

`customer/arcContractOrder/ComparisionPOApproverHistory`

`customer/tender/tender_approval_records`

`customer/tender/list_tender_flow`

`customer/rev-auc/auction_approval_records`

`customer/dmsdocument/getDocumentWorkflowRelease`

`customer/dmsdocument/getDocumentWorkflowRelease`

`customer/requests_master/getRequestWorkflowRelease`

`customer/purchaseRequestOrder/getWorkflowPORecords`

`customer/purchaseRequestOrder/ComparisionPOApproverHistory`

customer/tender/list_tender

customer/tender/list_tender_flow

customer/tender/tender_details
---

> **List of unused parameters in the API (which is called when opening a specific RFQ List drawer) `customer/requestQuotation/getRFQlist`**

| **Parameter** | **Used / Unused** |
| --- | --- |
| `pr_rfq_id` | `Used` |
| `rfq_number` | `Unused` |
| `rfq_deadline` | `Used` |
| `rfq_status` | `Used` |
| `is_deleted` | `Used` |
| `vendors_id` | `Used` |
| `special_vendor_ids` | `Unused` |
| `vendor_email_ids` | `Unused` |
| `collective_rfq_number` | `Used` |
| `tendor_type` | `Used` |
| `rfq_type` | `Unused` |
| `rfq_date` | `Used` |
| `purchase_group_id` | `Unused` |
| `created_by` | `Used` |
| `category_ids` | `Unused` |
| `rfq_oc` | `Used` |
| `rfq_extend_status` | `Used` |
| `negotiation_deadlinedate` | `Used` |
| `is_show_negotiate` | `Used` |
| `extend_count` | `Unused` |
| `currency_detail` | `Unused` |
| `technical_emp_id` | `Unused` |
| `mail_text` | `Unused` |
| `technical_emp_detail` | `Unused` |
| `cust_emp_fname` | `Used` |
| `cust_emp_lname` | `Used` |
| `approved_date` | `Unused` |
| `rfq_title` | `Used` |
| `pr_number` | `Unused` |
| `requisitioner_names` | `Unused` |
| `total_queries` | `Unused` |
| `unread_queries` | `Unused` |
| `quotationlists` | `Used` |
| `comparitive_reports` | `Used` |
| `updated_comparision_report` | `Used` |
| `po_attachments` | `Unused` |
| `oem_vendor_count` | `Used` |
| `bidder_vendor_count` | `Used` |

---

> **List of unused parameters in the API `customer/requestQuotation/listVendorQuotation`**

| **No.** | **Parameter** | **Used / Unused** |
| --- | --- | --- |
| `1` | `rfq_vendor_master_id` | `✅ Used` |
| `2` | `pr_rfq_id` | `❌ Unused` |
| `3` | `customer_id` | `❌ Unused` |
| `4` | `vendor_id` | `✅ Used` |
| `5` | `vendor_rfq_document` | `❌ Unused` |
| `6` | `vendor_rfq_quotation_document` | `✅ Used` |
| `7` | `is_deleted` | `❌ Unused` |
| `8` | `created_at` | `❌ Unused` |
| `9` | `updated_at` | `❌ Unused` |
| `10` | `cust_emp_id` | `❌ Unused` |
| `11` | `rfq_number` | `❌ Unused` |
| `12` | `rfq_status` | `❌ Unused` |
| `13` | `f_and_o_dec` | `❌ Unused` |
| `14` | `f_and_o` | `❌ Unused` |
| `15` | `payment_terms_dec` | `❌ Unused` |
| `16` | `payment_terms` | `❌ Unused` |
| `17` | `total_amount` | `✅ Used` |
| `18` | `regret_remarks` | `❌ Unused` |
| `19` | `vendor_remarks` | `❌ Unused` |
| `20` | `supplier_remarks` | `❌ Unused` |
| `21` | `delivery_terms_dec` | `❌ Unused` |
| `22` | `delivery_terms` | `❌ Unused` |
| `23` | `quantity_terms` | `❌ Unused` |
| `24` | `reference_number` | `❌ Unused` |
| `25` | `contact_person_name` | `❌ Unused` |
| `26` | `contact_person_number` | `❌ Unused` |
| `27` | `contact_person_email` | `❌ Unused` |
| `28` | `vendor_po_status` | `❌ Unused` |
| `29` | `pro_id` | `❌ Unused` |
| `30` | `vendor_code` | `✅ Used` |
| `31` | `vendor_name` | `✅ Used` |
| `32` | `vendor_rfq_quotation_history` | `✅ Used` |
| `33` | `unit` | `❌ Unused` |
| `34` | `currency` | `✅ Used` |
| `35` | `plant_id` | `❌ Unused` |
| `36` | `quantity` | `❌ Unused` |
| `37` | `gst_price` | `❌ Unused` |
| `38` | `unit_price` | `❌ Unused` |
| `39` | `discount_type` | `❌ Unused` |
| `40` | `vendor_emp_id` | `❌ Unused` |
| `41` | `discount_value` | `❌ Unused` |
| `42` | `insurance_type` | `❌ Unused` |
| `43` | `po_total_price` | `❌ Unused` |
| `44` | `quotation_text` | `❌ Unused` |
| `45` | `service_detail` | `❌ Unused` |
| `46` | `insurance_value` | `❌ Unused` |
| `47` | `quotation_price` | `❌ Unused` |
| `48` | `discount_cn_type` | `❌ Unused` |
| `49` | `gst_charge_value` | `❌ Unused` |
| `50` | `invoice_delivery` | `❌ Unused` |
| `51` | `quotation_status` | `❌ Unused` |
| `52` | `cess_charge_value` | `❌ Unused` |
| `53` | `insurance_cn_type` | `❌ Unused` |
| `54` | `landed_unit_price` | `❌ Unused` |
| `55` | `material_quantity` | `❌ Unused` |
| `56` | `local_charges_type` | `❌ Unused` |
| `57` | `local_charges_value` | `❌ Unused` |
| `58` | `transportation_type` | `❌ Unused` |
| `59` | `negotiate_unit_price` | `❌ Unused` |
| `60` | `transportation_value` | `❌ Unused` |
| `61` | `local_charges_cn_type` | `❌ Unused` |
| `62` | `comparison_total_price` | `❌ Unused` |
| `63` | `discount_lumpsum_value` | `❌ Unused` |
| `64` | `loading_unloading_type` | `❌ Unused` |
| `65` | `transportation_cn_type` | `❌ Unused` |
| `66` | `insurance_lumpsum_value` | `❌ Unused` |
| `67` | `loading_unloading_value` | `❌ Unused` |
| `68` | `rfq_vendor_quotation_id` | `❌ Unused` |
| `69` | `discount_lumpsum_cn_type` | `❌ Unused` |
| `70` | `gst_charge_lumpsum_value` | `❌ Unused` |
| `71` | `insurance_lumpsum_cn_type` | `❌ Unused` |
| `72` | `loading_unloading_cn_type` | `❌ Unused` |
| `73` | `packaging_forwarding_type` | `❌ Unused` |
| `74` | `po_material_deadline_date` | `❌ Unused` |
| `75` | `packaging_forwarding_value` | `❌ Unused` |
| `76` | `local_charges_lumpsum_value` | `❌ Unused` |
| `77` | `negotiate_landed_unit_price` | `❌ Unused` |
| `78` | `packaging_forwarding_cn_type` | `❌ Unused` |
| `79` | `purchase_request_material_id` | `❌ Unused` |
| `80` | `transportation_lumpsum_value` | `❌ Unused` |
| `81` | `local_charges_lumpsum_cn_type` | `❌ Unused` |
| `82` | `transportation_lumpsum_cn_type` | `❌ Unused` |
| `83` | `loading_unloading_lumpsum_value` | `❌ Unused` |
| `84` | `loading_unloading_lumpsum_cn_type` | `❌ Unused` |
| `85` | `packaging_forwarding_lumpsum_value` | `❌ Unused` |
| `86` | `packaging_forwarding_lumpsum_cn_type` | `❌ Unused` |
| `87` | `material_code` | `✅ Used` |
| `88` | `material_group_id` | `❌ Unused` |
| `89` | `material_group_code` | `❌ Unused` |
| `90` | `acc_assets_category_id` | `❌ Unused` |
| `91` | `category` | `❌ Unused` |
| `92` | `item_category_id` | `❌ Unused` |
| `93` | `item` | `❌ Unused` |
| `94` | `material_id` | `❌ Unused` |
| `95` | `quantity_ordered` | `❌ Unused` |
| `96` | `quantity_open` | `❌ Unused` |
| `97` | `request_date` | `❌ Unused` |
| `98` | `release_date` | `❌ Unused` |
| `99` | `pl_delivery_time` | `❌ Unused` |
| `100` | `gr_proc_time` | `❌ Unused` |
| `101` | `delivery_text` | `❌ Unused` |
| `102` | `material_po_text` | `❌ Unused` |
| `103` | `process_status` | `❌ Unused` |
| `104` | `purchase_requisition_status` | `❌ Unused` |
| `105` | `order_qty` | `❌ Unused` |
| `106` | `uploading_point` | `❌ Unused` |
| `107` | `recipient` | `❌ Unused` |
| `108` | `g_l_account` | `❌ Unused` |
| `109` | `assets` | `❌ Unused` |
| `110` | `co_area` | `❌ Unused` |
| `111` | `assignment_order` | `❌ Unused` |
| `112` | `wbs_element` | `❌ Unused` |
| `113` | `funds_center` | `❌ Unused` |
| `114` | `requisitioner` | `❌ Unused` |
| `115` | `requisitioner_name` | `❌ Unused` |
| `116` | `vendor_detail` | `❌ Unused` |
| `117` | `goods_receipt` | `❌ Unused` |
| `118` | `invoice_receipt` | `❌ Unused` |
| `119` | `item_text` | `❌ Unused` |
| `120` | `item_note` | `❌ Unused` |
| `121` | `delivery_date` | `❌ Unused` |
| `122` | `initial_price` | `❌ Unused` |
| `123` | `rfq_delivery_date` | `❌ Unused` |
| `124` | `distribution` | `❌ Unused` |
| `125` | `material_specification` | `❌ Unused` |
| `126` | `ra_id` | `❌ Unused` |
| `127` | `maximum_price` | `❌ Unused` |
| `128` | `po_order_quantity` | `❌ Unused` |
| `129` | `is_materil_po_created` | `❌ Unused` |
| `130` | `sap_item` | `❌ Unused` |
| `131` | `arc_contract_id` | `❌ Unused` |
| `132` | `asking_price` | `❌ Unused` |
| `133` | `asking_quantity` | `❌ Unused` |
| `134` | `unit_price` | `❌ Unused` |
| `135` | `prm_publish_type` | `❌ Unused` |
| `136` | `prm_selected_vendors` | `❌ Unused` |
| `137` | `pending_quantity` | `❌ Unused` |
| `138` | `prm_end_date` | `❌ Unused` |
| `139` | `prm_ra_extenstion_counter` | `❌ Unused` |
| `140` | `fixed_qty` | `❌ Unused` |
| `141` | `material_name` | `✅ Used` |
| `142` | `material_short_description` | `✅ Used` |

---

**All used Parameters:**

**`vendor_rfq_quotation_history`**

**`vendor_code`**

**`vendor_name`**

**`vendor_id`**

**`total_amount`**

**`materials`**

**`material_code`**

**`material_description`**

**`vendor_rfq_quotation_document`**

**`rfq_vendor_master_id`**

**`vendor_quotation_lists`**

**`currency`**

---

> **List of unused parameters in the API `customer/requestQuotation/getRequestQuotationRFQDetails`**
> 

**Date: 14/10/25**

| **Parameter** | **Used / Unused** |
| --- | --- |
| `rfq_number` | `✅used` |
| `rfq_deadline` | `✅used` |
| `rfq_status` |  |
| `is_deleted` | `✅used` |
| `vendors_id` | `✅used` |
| `vendor_email_ids` |  |
| `collective_rfq_number` | `✅used` |
| `tendor_type` | `✅used` |
| `rfq_type` | `✅used` |
| `rfq_date` | `✅used` |
| `purchase_group_id` | `✅used` |
| `created_by` | `✅used` |
| `category_ids` |  |
| `rfq_oc` | `✅used` |
| `rfq_extend_status` | `✅used` |
| `negotiation_deadlinedate` | `✅used` |
| `is_show_negotiate` | `✅used` |
| `extend_count` | `✅used` |
| `currency_detail` |  |
| `cust_emp_fname` | `✅used` |
| `cust_emp_lname` | `✅used` |
| `approved_date` |  |
| `pr_number` | `✅used` |
| `requisitioner_names` | `✅used` |
| `total_queries` | `✅used` |
| `unread_queries` | `✅used` |
| `comparitive_reports` | `✅used` |
| `vendoremaillists` |  |
| `updated_comparision_report` | `✅used` |
| `po_attachments` | `✅used` |
| `materiallists` | `✅used` |
| `vendor_details` | `✅used` |
| `rfq_title` | `✅used` |
| `purchase_organization` | `✅used` |
| `purchase_group_code` | `✅used` |
| `technical_emp_id` | `✅used` |
| `requisitioner_name` | `✅used` |
| `material_id` | `✅used` |
| `material_code` | `✅used` |
| `material_group_id` | `✅used` |
| `material_group_code` | `✅used` |
| `quantity` | `✅used` |
| `unit_id` | `✅used` |
| `unit` | `✅used` |
| `total_price` | `✅used` |
| `plant_id` | `✅used` |
| `plant_code` | `✅used` |
| `process_status` | `✅used` |
| `requisitioner` | `✅used` |
| `item_text` | `✅used` |
| `delivery_date` | `✅used` |
| `rfq_delivery_date` | `✅used` |
| `material_specification` | `✅used` |
| `material_name` | `✅used` |
| `material_short_description` | `✅used` |
| `vendor_id` | `✅used` |
| `vendor_phone` | `✅used` |
| `vendor_email` | `✅used` |
| `vendor_name` | `✅used` |
| `vendor_emp_id` | `✅used` |
| `first_name` |  |
| `last_name` |  |
| `verified` |  |

---

> **List of unused parameters in the API (which is called when opening a specific RFQ Detail drawer) `customer/requestQuotation/get_rfq_details`**


**Date: 14/10/25**

| **No.** | **Parameter** | **Used / Unused** |
| --- | --- | --- |
| `1` | `pr_rfq_id` | `✅ Used` |
| `2` | `rfq_number` |  |
| `3` | `rfq_deadline` | `✅ Used` |
| `4` | `rfq_status` |  |
| `5` | `is_deleted` | `✅ Used` |
| `6` | `vendors_id` | `✅ Used` |
| `7` | `special_vendor_ids` | `✅ Used` |
| `8` | `vendor_email_ids` | `✅ Used` |
| `9` | `collective_rfq_number` | `✅ Used` |
| `10` | `tendor_type` | `✅ Used` |
| `11` | `rfq_type` | `✅ Used` |
| `12` | `rfq_date` | `✅ Used` |
| `13` | `purchase_group_id` | `✅ Used` |
| `14` | `created_by` | `✅ Used` |
| `15` | `category_ids` | `✅ Used` |
| `16` | `rfq_oc` |  |
| `17` | `rfq_extend_status` |  |
| `18` | `negotiation_deadlinedate` |  |
| `19` | `is_show_negotiate` |  |
| `20` | `currency_detail` |  |
| `21` | `technical_emp_id` | `✅ Used` |
| `22` | `mail_text` | `✅ Used` |
| `23` | `technical_emp_detail_cust_emp_email` |  |
| `24` | `technical_emp_detail_cust_emp_fname` |  |
| `25` | `technical_emp_detail_cust_emp_lname` |  |
| `26` | `technical_emp_detail_cust_emp_phone` |  |
| `27` | `technical_emp_detail_cust_emp_dial_code` |  |
| `28` | `extend_count` |  |
| `29` | `cust_emp_fname` | `✅ Used` |
| `30` | `cust_emp_lname` | `✅ Used` |
| `31` | `rfq_title` | `✅ Used` |
| `32` | `pr_number` | `✅ Used` |
| `33` | `requisitioner_names` | `✅ Used` |
| `34` | `total_queries` |  |
| `35` | `unread_queries` |  |
| `36` | `pro_id` |  |
| `37` | `f_and_o` |  |
| `38` | `pr_rfq_id` |  |
| `39` | `vendor_id` | `✅ Used` |
| `40` | `created_at` |  |
| `41` | `is_deleted` |  |
| `42` | `rfq_number` |  |
| `43` | `rfq_status` |  |
| `44` | `updated_at` |  |
| `45` | `cust_emp_id` |  |
| `46` | `customer_id` |  |
| `47` | `f_and_o_dec` |  |
| `48` | `vendor_code` |  |
| `49` | `vendor_name` |  |
| `50` | `total_amount` |  |
| `51` | `vendor_email` |  |
| `52` | `vendor_phone` |  |
| `53` | `payment_terms` |  |
| `54` | `total_queries` |  |
| `55` | `delivery_terms` |  |
| `56` | `quantity_terms` |  |
| `57` | `regret_remarks` |  |
| `58` | `unread_queries` |  |
| `59` | `vendor_remarks` |  |
| `60` | `reference_number` |  |
| `61` | `supplier_remarks` |  |
| `62` | `vendor_po_status` |  |
| `63` | `payment_terms_dec` |  |
| `64` | `delivery_terms_dec` |  |
| `65` | `contact_person_name` |  |
| `66` | `vendor_rfq_document` | `✅ Used` |
| `67` | `contact_person_email` |  |
| `68` | `rfq_vendor_master_id` |  |
| `69` | `contact_person_number` |  |
| `70` | `vendor_rfq_quotation_history` |  |
| `71` | `vendor_rfq_quotation_document` | `✅ Used` |
| `72` | `vendoremaillists` | `✅ Used` |
| `73` | `comparitive_reports` |  |
| `74` | `updated_comparision_report` |  |
| `75` | `po_attachments` |  |
| `76` | `purchase_request_material_id` | `✅ Used` |
| `77` | `pr_id` | `✅ Used` |
| `78` | `material_id` | `✅ Used` |
| `79` | `material_code` | `✅ Used` |
| `80` | `material_group_id` | `✅ Used` |
| `81` | `material_group_code` | `✅ Used` |
| `82` | `acc_assets_category_id` | `✅ Used` |
| `83` | `category` | `✅ Used` |
| `84` | `item` | `✅ Used` |
| `85` | `quantity` | `✅ Used` |
| `86` | `unit_id` | `✅ Used` |
| `87` | `unit` | `✅ Used` |
| `88` | `total_price` | `✅ Used` |
| `89` | `plant_id` | `✅ Used` |
| `90` | `plant_code` | `✅ Used` |
| `91` | `purchase_organization` | `✅ Used` |
| `92` | `purchase_group_id` | `✅ Used` |
| `93` | `purchase_group_code` | `✅ Used` |
| `94` | `tracking_number` | `✅ Used` |
| `95` | `material_revision` |  |
| `96` | `quantity_ordered` |  |
| `97` | `quantity_open` |  |
| `98` | `request_date` |  |
| `99` | `release_date` |  |
| `100` | `pl_delivery_time` |  |
| `101` | `gr_proc_time` |  |
| `102` | `delivery_text` | `✅ Used` |
| `103` | `material_po_text` | `✅ Used` |
| `104` | `process_status` | `✅ Used` |
| `105` | `purchase_requisition_status` | `✅ Used` |
| `106` | `order_qty` | `✅ Used` |
| `107` | `uploading_point` | `✅ Used` |
| `108` | `recipient` | `✅ Used` |
| `109` | `g_l_account` | `✅ Used` |
| `110` | `assets` | `✅ Used` |
| `111` | `co_area` | `✅ Used` |
| `112` | `assignment_order` | `✅ Used` |
| `113` | `wbs_element` | `✅ Used` |
| `114` | `funds_center` | `✅ Used` |
| `115` | `is_deleted` | `✅ Used` |
| `116` | `created_at` |  |
| `117` | `updated_at` |  |
| `118` | `requisitioner` | `✅ Used` |
| `119` | `requisitioner_name` | `✅ Used` |
| `120` | `pr_rfq_id` | `✅ Used` |
| `121` | `vendor_id` | `✅ Used` |
| `122` | `vendor_detail` | `✅ Used` |
| `123` | `goods_receipt` |  |
| `124` | `invoice_receipt` |  |
| `125` | `item_text` | `✅ Used` |
| `126` | `item_note` | `✅ Used` |
| `127` | `delivery_date` | `✅ Used` |
| `128` | `initial_price` |  |
| `129` | `rfq_delivery_date` | `✅ Used` |
| `130` | `distribution` |  |
| `131` | `material_specification` | `✅ Used` |
| `132` | `service_detail` | `✅ Used` |
| `133` | `pro_id` |  |
| `134` | `ra_id` |  |
| `135` | `maximum_price` |  |
| `136` | `po_order_quantity` |  |
| `137` | `is_materil_po_created` |  |
| `138` | `sap_item` | `✅ Used` |
| `139` | `arc_contract_id` |  |
| `140` | `asking_price` |  |
| `141` | `asking_quantity` |  |
| `142` | `unit_price` | `✅ Used` |
| `143` | `prm_publish_type` |  |
| `144` | `prm_selected_vendors` |  |
| `145` | `pending_quantity` |  |
| `146` | `prm_end_date` |  |
| `147` | `prm_ra_extenstion_counter` |  |
| `148` | `fixed_qty` |  |
| `149` | `material_name` |  |
| `150` | `material_short_description` | `✅ Used` |
| `151` | `vendorqueries` | `✅ Used` |
| `152` | `attachments` | `✅ Used` |

---

> **List of unused parameters in the API -  `customer/requestQuotation/comparisionRFQApproverHistory`**


**Date: 14/10/25**

| **#** | **Parameter** | **Used / Unused** |
| --- | --- | --- |
| 1 | `workflow_approval_id` | `✅Used` |
| 2 | `customer_id` |  |
| 3 | `pr_rfq_id` | `✅Used` |
| 4 | `cust_emp_id` | `✅Used` |
| 5 | `remarks` | `✅Used` |
| 6 | `is_delete` |  |
| 7 | `created_at` |  |
| 8 | `updated_at` |  |
| 9 | `deleted_at` |  |
| 10 | `approved_at` | `✅Used` |
| 11 | `approval_status` | `✅Used` |
| 12 | `comparative_link` | `✅Used` |
| 13 | `approval_type` | `✅Used` |
| 14 | `level_name` | `✅Used` |
| 15 | `is_already_used` |  |
| 16 | `remarks_text` |  |
| 17 | `approval_assigne_at` |  |
| 18 | `approval_time` |  |
| 19 | `is_enquiry_important` | `✅Used` |
| 20 | `reminder_cron_run` |  |
| 21 | `is_hold` |  |
| 22 | `is_unread` |  |
| 23 | `approval_hold_at` |  |
| 24 | `is_return` |  |
| 25 | `workflow_assign_at` |  |
| 26 | `cust_emp_fname` | `✅Used` |
| 27 | `cust_emp_lname` | `✅Used` |
| 28 | `ceb_prefix` | `✅Used` |

---

> **List of unused parameters in the API - (called when take reference from PR) -  `customer/purchaseRequest/getPurchaseRequestRFQData`**


**Date: 14/10/25**

| **No.** | **Parameter** | **Used / Unused** |
| --- | --- | --- |
| `1` | `pr_id` | `used` |
| `2` | `pr_number` | `used` |
| `3` | `requisitioner_name` | `used` |
| `4` | `created_at` |  |
| `5` | `pr_deadline` |  |
| `6` | `pr_status` |  |
| `7` | `is_deleted` | `used` |
| `8` | `pr_document` |  |
| `9` | `department_name` |  |
| `10` | `department_id` |  |
| `11` | `assets_number` |  |
| `12` | `purchase_type_id` | `used` |
| `13` | `sap_login_id` |  |
| `14` | `cust_emp_fname` | `used` |
| `15` | `cust_emp_lname` | `used` |
| `16` | `purchase_type_code` | `used` |
| `17` | `purchase_type_name` | `used` |
| `18` | `tracking_number` | `used` |
| `19` | `materiallists` | `used` |
| `20` | `item` | `used` |
| `21` | `unit` | `used` |
| `22` | `ra_id` |  |
| `23` | `assets` |  |
| `24` | `pro_id` |  |
| `25` | `co_area` | `used` |
| `26` | `unit_id` | `used` |
| `27` | `category` | `used` |
| `28` | `plant_id` | `used` |
| `29` | `quantity` | `used` |
| `30` | `sap_item` | `used` |
| `31` | `fixed_qty` |  |
| `32` | `item_note` | `used` |
| `33` | `item_text` | `used` |
| `34` | `order_qty` | `used` |
| `35` | `pr_rfq_id` | `used` |
| `36` | `recipient` | `used` |
| `37` | `vendor_id` | `used` |
| `38` | `plant_code` | `used` |
| `39` | `unit_price` | `used` |
| `40` | `attachments` | `used` |
| `41` | `material_id` | `used` |
| `42` | `total_price` | `used` |
| `43` | `goods_receipt` | `used` |
| `44` | `initial_price` | `used` |
| `45` | `material_code` | `used` |
| `46` | `material_name` | `used` |
| `47` | `requisitioner` | `used` |
| `48` | `vendor_detail` | `used` |
| `49` | `process_status` | `used` |
| `50` | `service_detail` | `used` |
| `51` | `invoice_receipt` | `used` |
| `52` | `material_group_id` | `used` |
| `53` | `purchase_group_id` | `used` |
| `54` | `rfq_delivery_date` | `used` |
| `55` | `requisitioner_name` | `used` |
| `56` | `material_group_code` | `used` |
| `57` | `purchase_group_code` | `used` |
| `58` | `purchase_organization` | `used` |
| `59` | `material_specification` | `used` |
| `60` | `material_short_description` | `used` |
| `61` | `purchase_request_material_id` | `used` |
| `62` | `vendor_code` | `used` |
| `63` | `vendor_name` | `used` |
| `64` | `total_amount` | `used` |
| `65` | `vendor_email` | `used` |
| `66` | `vendor_phone` | `used` |

---

> **List of unused parameters in the API - (called during componentDidMount) -**  `customer/vendor/listPagination`


**Date: 15/10/25**

| **No.** | **Parameter** | **Used / Unused** |
| --- | --- | --- |
| 1 | vendor_id | used |
| 2 | vendor_phone | used |
| 3 | vendor_images |  |
| 4 | vendor_thumbs |  |
| 5 | vendor_cumtomer_ids |  |
| 6 | vendor_emp_ids |  |
| 7 | vendor_active | used |
| 8 | vendor_deleted |  |
| 9 | created_at | used |
| 10 | updated_at |  |
| 11 | vendor_unique_id |  |
| 12 | vendor_street |  |
| 13 | vendor_zipcode |  |
| 14 | vendor_main_employee |  |
| 15 | vendor_contract |  |
| 16 | vendor_email | used |
| 17 | vendor_name | used |
| 18 | vendor_country | used |
| 19 | vendor_country_code |  |
| 20 | vendor_state | used |
| 21 | vendor_city |  |
| 22 | vendor_nickname | used |
| 23 | vendor_status |  |
| 24 | vendor_emp_count |  |
| 25 | vendor_prefix |  |
| 26 | vendor_currency_symbol |  |
| 27 | prefix_change |  |
| 28 | checklist_pref |  |
| 29 | is_pending_comp_service |  |
| 30 | pending_comp_cron_time |  |
| 31 | is_pending_comp_cron |  |
| 32 | deactivated_customers |  |
| 33 | vendor_tz |  |
| 34 | user_profile_show_verndor |  |
| 35 | service_provider_id |  |
| 36 | vendor_category_id |  |
| 37 | vendor_office_tel |  |
| 38 | vendor_field_area |  |
| 39 | vendor_attachement |  |
| 40 | vendor_attachement_thumb |  |
| 41 | vendor_gst |  |
| 42 | vendor_gst_thumb |  |
| 43 | vendor_pan |  |
| 44 | vendor_pan_thumb |  |
| 45 | vendor_cheque |  |
| 46 | vendor_cheque_thumb |  |
| 47 | vandor_bank_acc_no |  |
| 48 | vendor_bank_name |  |
| 49 | vendor_bank_address |  |
| 50 | vendor_bank_city |  |
| 51 | vendor_bank_branch |  |
| 52 | vendor_bank_ifsc |  |
| 53 | vendor_bank_branch_code |  |
| 54 | vendor_code | used |
| 55 | vendor_district |  |
| 56 | vendor_fax |  |
| 57 | vendor_gst_no |  |
| 58 | vendor_pan_no |  |
| 59 | vendor_contact_person |  |
| 60 | utr_ref |  |
| 61 | utr_date |  |
| 62 | utr_amount |  |
| 63 | utr_bank |  |
| 64 | utr_attachments |  |
| 65 | deleted_customers |  |
| 66 | beneficiary_name |  |
| 67 | vendor_product |  |
| 68 | vendor_emp_id |  |
| 69 | first_name | used |
| 70 | last_name | used |
| 71 | verified |  |
| 72 | validity_documents |  |
| 73 | is_vendor_active_for_customer |  |

---

> **List of unused parameters in the API - (called during componentDidMount) -**  `customer/material/getMaterialRecords`


**Date: 15/10/25**

| **No.** | **Parameter** | **Used / Unused** |
| --- | --- | --- |
| `1` | `material_id` | `used` |
| `2` | `material_group_id` | `used` |
| `3` | `material_name` | `used` |
| `4` | `material_code` | `used` |
| `5` | `material_short_description` | `used` |
| `6` | `material_type_id` |  |
| `7` | `material_industry` |  |
| `8` | `material_base_unit` | `used` |
| `9` | `material_gross_weight` |  |
| `10` | `material_net_weight` |  |
| `11` | `material_weight_unit` |  |
| `12` | `material_volume` |  |
| `13` | `material_volume_weight` |  |
| `14` | `material_barcode` |  |
| `15` | `material_old_material_number` |  |
| `16` | `material_size_and_dimension` |  |
| `17` | `material_division` |  |
| `18` | `material_measurement_id` | `used` |
| `19` | `material_purchase_group_id` | `used` |
| `20` | `material_type_code` |  |
| `21` | `material_type_name` |  |
| `22` | `measurement_name` | `used` |
| `23` | `measurement_code` | `used` |
| `24` | `purchase_group_code` | `used` |
| `25` | `purchase_description` | `used` |
| `26` | `material_group_name` | `used` |
| `27` | `material_group_code` | `used` |

-------------------------

## `2️⃣` **`Purchase Request`**


> **List of unused parameters in the API - (called during componentDidMount / Pagination ) -  `customer/purchaseRequest/getPurchaseRequestLists`**


**Date: 15/10/25**

| **#** | **Parameter** | **Used/Unused** |
| --- | --- | --- |
| 1 | pr_id |  |
| 2 | cust_emp_id |  |
| 3 | pr_number | used |
| 4 | requisitioner_name | used |
| 5 | created_at | used |
| 6 | pr_deadline | used |
| 7 | pr_status | used |
| 8 | is_deleted | used |
| 9 | pr_document | used |
| 10 | department_name |  |
| 11 | department_id |  |
| 12 | assets_number |  |
| 13 | purchase_type_id |  |
| 14 | sap_login_id | used |
| 15 | cust_emp_fname |  |
| 16 | pr_delete_remarks |  |
| 17 | release_remarks | used |
| 18 | cust_emp_lname |  |
| 19 | purchase_type_code |  |
| 20 | purchase_type_name |  |
| 21 | tracking_number | used |
| 22 | rfq_details | used |
| 23 | pr_rfq_id |  |
| 24 | rfq_status |  |
| 25 | collective_rfq_number | used |
| 26 | tenders | used |
| 27 | tender_id |  |
| 28 | tender_status |  |
| 29 | tender_type_id |  |
| 30 | tender_bid_type |  |
| 31 | tender_ref_name |  |
| 32 | tender_type_code |  |
| 33 | tender_type_name |  |
| 34 | collective_tender_no |  |

---

> **List of unused parameters in the API - (called during componentDidMount / Pagination ) -** `customer/purchaseRequest/getRFQPurchaseRequestLists`


**Date: 15/10/25**

| # | Parameter | Used/Unused |
| --- | --- | --- |
| 1 | pr_id |  |
| 2 | cust_emp_id |  |
| 3 | pr_number | used |
| 4 | requisitioner_name | used |
| 5 | created_at | used |
| 6 | pr_deadline | used |
| 7 | pr_status | used |
| 8 | is_deleted | used |
| 9 | pr_document | used |
| 10 | department_name |  |
| 11 | department_id |  |
| 12 | assets_number |  |
| 13 | purchase_type_id |  |
| 14 | sap_login_id | used |
| 15 | pr_delete_remarks |  |
| 16 | release_remarks | used |
| 17 | cust_emp_fname |  |
| 18 | cust_emp_lname |  |
| 19 | purchase_type_code |  |
| 20 | purchase_type_name |  |
| 21 | tracking_number | used |
| 22 | materiallists |  |
| 23 | item |  |
| 24 | unit |  |
| 25 | pr_id |  |
| 26 | ra_id |  |
| 27 | assets |  |
| 28 | pro_id |  |
| 29 | co_area |  |
| 30 | unit_id |  |
| 31 | category |  |
| 32 | plant_id |  |
| 33 | quantity |  |
| 34 | sap_item |  |
| 35 | fixed_qty |  |
| 36 | item_note |  |
| 37 | item_text |  |
| 38 | order_qty |  |
| 39 | pr_rfq_id |  |
| 40 | recipient |  |
| 41 | vendor_id |  |
| 42 | created_at | used |
| 43 | is_deleted | used |
| 44 | plant_code |  |
| 45 | unit_price |  |
| 46 | updated_at |  |
| 47 | attachments |  |
| 48 | g_l_account |  |
| 49 | material_id |  |
| 50 | total_price |  |
| 51 | wbs_element |  |
| 52 | asking_price |  |
| 53 | distribution |  |
| 54 | funds_center |  |
| 55 | gr_proc_time |  |
| 56 | prm_end_date |  |
| 57 | release_date |  |
| 58 | request_date |  |
| 59 | delivery_date |  |
| 60 | delivery_text |  |
| 61 | goods_receipt |  |
| 62 | initial_price |  |
| 63 | material_code |  |
| 64 | material_name |  |
| 65 | maximum_price |  |
| 66 | quantity_open |  |
| 67 | requisitioner |  |
| 68 | vendor_detail |  |
| 69 | process_status |  |
| 70 | service_detail |  |
| 71 | arc_contract_id |  |
| 72 | asking_quantity |  |
| 73 | invoice_receipt |  |
| 74 | tracking_number | used |
| 75 | uploading_point |  |
| 76 | assignment_order |  |
| 77 | item_category_id |  |
| 78 | material_po_text |  |
| 79 | pending_quantity |  |
| 80 | pl_delivery_time |  |
| 81 | prm_publish_type |  |
| 82 | quantity_ordered |  |
| 83 | material_group_id |  |
| 84 | material_revision |  |
| 85 | po_order_quantity |  |
| 86 | purchase_group_id |  |
| 87 | rfq_delivery_date |  |
| 88 | requisitioner_name | used |
| 89 | material_group_code |  |
| 90 | purchase_group_code |  |
| 91 | prm_selected_vendors |  |
| 92 | is_materil_po_created |  |
| 93 | purchase_organization |  |
| 94 | acc_assets_category_id |  |
| 95 | material_specification |  |
| 96 | prm_ra_extenstion_counter |  |
| 97 | material_short_description |  |
| 98 | purchase_requisition_status |  |
| 99 | purchase_request_material_id |  |
| 100 | release_records |  |
| 101 | rfq_details | used |
| 102 | pr_rfq_id |  |
| 103 | rfq_status |  |
| 104 | collective_rfq_number | used |
| 105 | tenders | used |

---

> **List of unused parameters in the API - (called during componentDidMount / Pagination ) - `customer/purchaseRequest/getDeletedPurchaseRequestLists`**


**Date: 15/10/25**

| **#** | **Parameter** | **Used/Unused** |
| --- | --- | --- |
| 1 | pr_id |  |
| 2 | pr_number | used |
| 3 | requisitioner_name | used |
| 4 | created_at | used |
| 5 | pr_deadline | used |
| 6 | pr_status | used |
| 7 | is_deleted | used |
| 8 | pr_document |  |
| 9 | department_name |  |
| 10 | department_id |  |
| 11 | assets_number |  |
| 12 | purchase_type_id |  |
| 13 | sap_login_id | used |
| 14 | pr_delete_remarks | used |
| 15 | release_remarks |  |
| 16 | cust_emp_fname |  |
| 17 | cust_emp_lname |  |
| 18 | purchase_type_code |  |
| 19 | purchase_type_name |  |
| 20 | tracking_number | used |
| 21 | rfq_details | used |
| 22 | tenders | used |
| 23 | tender_id |  |
| 24 | tender_status |  |
| 25 | tender_type_id | used |
| 26 | tender_bid_type | used |
| 27 | tender_ref_name | used |
| 28 | tender_type_code | used |
| 29 | tender_type_name |  |
| 30 | collective_tender_no | used |

---

> **List of unused parameters in the API - (called during open specific PR Details ) -** `customer/purchaseRequest/getPurchaseRequestDetails`


**Date: 15/10/25**

| **No** | **Parameter** | **Used/Unused** |
| --- | --- | --- |
| 1 | pr_id | used |
| 2 | cust_emp_id | used |
| 3 | pr_number | used |
| 4 | requisitioner_name | used |
| 5 | created_at | used |
| 6 | pr_deadline |  |
| 7 | pr_status |  |
| 8 | is_deleted | used |
| 9 | pr_document |  |
| 10 | department_name | used |
| 11 | department_id | used |
| 12 | assets_number | used |
| 13 | purchase_type_id | used |
| 14 | sap_login_id |  |
| 15 | cust_emp_fname |  |
| 16 | pr_delete_remarks |  |
| 17 | release_remarks |  |
| 18 | cust_emp_lname |  |
| 19 | purchase_type_code | used |
| 20 | purchase_type_name | used |
| 21 | tracking_number | used |
| 22 | materiallists | used |
| 23 | item | used |
| 24 | unit | used |
| 25 | pr_id | used |
| 26 | ra_id |  |
| 27 | assets | used |
| 28 | pro_id |  |
| 29 | co_area | used |
| 30 | unit_id | used |
| 31 | category | used |
| 32 | plant_id | used |
| 33 | quantity | used |
| 34 | sap_item | used |
| 35 | fixed_qty |  |
| 36 | item_note | used |
| 37 | item_text | used |
| 38 | order_qty | used |
| 39 | pr_rfq_id | used |
| 40 | recipient | used |
| 41 | vendor_id | used |
| 42 | created_at | used |
| 43 | is_deleted | used |
| 44 | plant_code | used |
| 45 | updated_at |  |
| 46 | attachments | used |
| 47 | pr_id | used |
| 48 | pro_id |  |
| 49 | image_id | used |
| 50 | file_name |  |
| 51 | file_type |  |
| 52 | image_url |  |
| 53 | pr_rfq_id | used |
| 54 | thumb_url |  |
| 55 | created_at | used |
| 56 | updated_at |  |
| 57 | purchase_request_material_id | used |
| 58 | g_l_account | used |
| 59 | material_id | used |
| 60 | total_price | used |
| 61 | wbs_element | used |
| 62 | asking_price |  |
| 63 | distribution | used |
| 64 | funds_center | used |
| 65 | gr_proc_time |  |
| 66 | prm_end_date |  |
| 67 | release_date |  |
| 68 | request_date |  |
| 69 | delivery_date | used |
| 70 | delivery_text | used |
| 71 | goods_receipt |  |
| 72 | initial_price |  |
| 73 | material_code | used |
| 74 | material_name |  |
| 75 | maximum_price |  |
| 76 | quantity_open |  |
| 77 | requisitioner | used |
| 78 | vendor_detail | used |
| 79 | process_status | used |
| 80 | service_detail | used |
| 81 | arc_contract_id | used |
| 82 | asking_quantity |  |
| 83 | invoice_receipt |  |
| 84 | tracking_number | used |
| 85 | uploading_point | used |
| 86 | assignment_order | used |
| 87 | item_category_id | used |
| 88 | material_po_text | used |
| 89 | pending_quantity |  |
| 90 | pl_delivery_time |  |
| 91 | prm_publish_type |  |
| 92 | quantity_ordered |  |
| 93 | material_group_id | used |
| 94 | material_revision | used |
| 95 | po_order_quantity |  |
| 96 | purchase_group_id | used |
| 97 | rfq_delivery_date |  |
| 98 | requisitioner_name | used |
| 99 | material_group_code | used |
| 100 | purchase_group_code | used |
| 101 | prm_selected_vendors |  |
| 102 | arc_agreement_details | used |
| 103 | is_materil_po_created |  |
| 104 | purchase_organization | used |
| 105 | acc_assets_category_id | used |
| 106 | material_specification | used |
| 107 | prm_ra_extenstion_counter |  |
| 108 | material_short_description | used |
| 109 | purchase_requisition_status | used |
| 110 | purchase_request_material_id | used |
| 111 | release_records | used |
| 112 | rfq_details |  |
| 113 | pr_rfq_id | used |
| 114 | rfq_status |  |
| 115 | collective_rfq_number |  |

---

> **List of unused parameters in the API - (called during click on Print PR button in Side Drawer) - `customer/purchaseRequest/getPurchaseRequestRecordsLists`**


**Date: 16/10/25**

| **No** | **Parameter** | **Used/Unused** |
| --- | --- | --- |
| `1` | `pr_id` | `✅used` |
| `2` | `pr_number` | `✅used` |
| `3` | `requisitioner_name` | `✅used` |
| `4` | `created_at` |  |
| `5` | `pr_deadline` |  |
| `6` | `pr_status` |  |
| `7` | `is_deleted` | `✅used` |
| `8` | `pr_document` | `✅used` |
| `9` | `department_name` |  |
| `10` | `department_id` |  |
| `11` | `assets_number` |  |
| `12` | `purchase_type_id` |  |
| `13` | `sap_login_id` |  |
| `14` | `cust_emp_fname` |  |
| `15` | `cust_emp_lname` |  |
| `16` | `purchase_type_code` | `✅used` |
| `17` | `purchase_type_name` |  |
| `18` | `materiallists` | `✅used` |
| `19` | `purchase_request_material_id` | `✅used` |
| `20` | `pr_id` | `✅used` |
| `21` | `material_id` | `✅used` |
| `22` | `material_code` | `✅used` |
| `23` | `material_group_id` | `✅used` |
| `24` | `material_group_code` | `✅used` |
| `25` | `acc_assets_category_id` | `✅used` |
| `26` | `category` | `✅used` |
| `27` | `item_category_id` | `✅used` |
| `28` | `item` | `✅used` |
| `29` | `quantity` | `✅used` |
| `30` | `unit_id` | `✅used` |
| `31` | `unit` | `✅used` |
| `32` | `total_price` | `✅used` |
| `33` | `plant_id` | `✅used` |
| `34` | `plant_code` | `✅used` |
| `35` | `purchase_organization` | `✅used` |
| `36` | `purchase_group_id` | `✅used` |
| `37` | `purchase_group_code` | `✅used` |
| `38` | `tracking_number` | `✅used` |
| `39` | `material_revision` | `✅used` |
| `40` | `quantity_ordered` |  |
| `41` | `quantity_open` |  |
| `42` | `request_date` |  |
| `43` | `release_date` |  |
| `44` | `pl_delivery_time` |  |
| `45` | `gr_proc_time` |  |
| `46` | `delivery_text` | `✅used` |
| `47` | `material_po_text` | `✅used` |
| `48` | `process_status` | `✅used` |
| `49` | `purchase_requisition_status` | `✅used` |
| `50` | `order_qty` | `✅used` |
| `51` | `uploading_point` | `✅used` |
| `52` | `recipient` | `✅used` |
| `53` | `g_l_account` | `✅used` |
| `54` | `assets` | `✅used` |
| `55` | `co_area` | `✅used` |
| `56` | `assignment_order` | `✅used` |
| `57` | `wbs_element` | `✅used` |
| `58` | `funds_center` | `✅used` |
| `59` | `is_deleted` | `✅used` |
| `60` | `created_at` |  |
| `61` | `updated_at` |  |
| `62` | `requisitioner` | `✅used` |
| `63` | `requisitioner_name` | `✅used` |
| `64` | `pr_rfq_id` | `✅used` |
| `65` | `vendor_id` | `✅used` |
| `66` | `vendor_detail` | `✅used` |
| `67` | `goods_receipt` |  |
| `68` | `invoice_receipt` |  |
| `69` | `item_text` | `✅used` |
| `70` | `item_note` | `✅used` |
| `71` | `delivery_date` | `✅used` |
| `72` | `initial_price` |  |
| `73` | `rfq_delivery_date` |  |
| `74` | `distribution` | `✅used` |
| `75` | `material_specification` | `✅used` |
| `76` | `service_detail` | `✅used` |
| `77` | `pro_id` |  |
| `78` | `ra_id` |  |
| `79` | `maximum_price` |  |
| `80` | `po_order_quantity` |  |
| `81` | `is_material_po_created` |  |
| `82` | `sap_item` |  |
| `83` | `arc_contract_id` | `✅used` |
| `84` | `asking_price` |  |
| `85` | `asking_quantity` |  |
| `86` | `unit_price` |  |
| `87` | `prm_publish_type` |  |
| `88` | `prm_selected_vendors` |  |
| `89` | `pending_quantity` |  |
| `90` | `prm_end_date` |  |
| `91` | `prm_ra_extension_counter` |  |
| `92` | `fixed_qty` |  |
| `93` | `material_name` |  |
| `94` | `material_short_description` |  |
| `95` | `attachments` |  |
| `96` | `utr_ref` |  |
| `97` | `utr_bank` |  |
| `98` | `utr_date` |  |
| `99` | `verified` |  |
| `100` | `last_name` |  |
| `101` | `vendor_id` |  |
| `102` | `vendor_tz` |  |
| `103` | `created_at` |  |
| `104` | `first_name` |  |
| `105` | `updated_at` |  |
| `106` | `utr_amount` |  |
| `107` | `vendor_fax` |  |
| `108` | `vendor_gst` |  |
| `109` | `vendor_pan` |  |
| `110` | `vendor_city` |  |
| `111` | `vendor_code` |  |
| `112` | `vendor_name` |  |
| `113` | `vendor_email` |  |
| `114` | `vendor_phone` |  |
| `115` | `vendor_state` |  |
| `116` | `prefix_change` |  |
| `117` | `vendor_active` |  |
| `118` | `vendor_cheque` |  |
| `119` | `vendor_emp_id` |  |
| `120` | `vendor_gst_no` |  |
| `121` | `vendor_images` |  |
| `122` | `vendor_pan_no` |  |
| `123` | `vendor_prefix` |  |
| `124` | `vendor_status` |  |
| `125` | `vendor_street` |  |
| `126` | `vendor_thumbs` |  |
| `127` | `checklist_pref` |  |
| `128` | `vendor_country` |  |
| `129` | `vendor_deleted` |  |
| `130` | `vendor_emp_ids` |  |
| `131` | `vendor_product` |  |
| `132` | `vendor_zipcode` |  |
| `133` | `utr_attachments` |  |
| `134` | `vendor_contract` |  |
| `135` | `vendor_district` |  |
| `136` | `vendor_nickname` |  |
| `137` | `beneficiary_name` |  |
| `138` | `vendor_bank_city` |  |
| `139` | `vendor_bank_ifsc` |  |
| `140` | `vendor_bank_name` |  |
| `141` | `vendor_emp_count` |  |
| `142` | `vendor_gst_thumb` |  |
| `143` | `vendor_pan_thumb` |  |
| `144` | `vendor_unique_id` |  |
| `145` | `deleted_customers` |  |
| `146` | `vendor_field_area` |  |
| `147` | `vendor_office_tel` |  |
| `148` | `validity_documents` |  |
| `149` | `vendor_bank_acc_no` |  |
| `150` | `vendor_attachment` |  |
| `151` | `vendor_bank_branch` |  |
| `152` | `vendor_category_id` |  |
| `153` | `service_provider_id` |  |
| `154` | `vendor_bank_address` |  |
| `155` | `vendor_cheque_thumb` |  |
| `156` | `vendor_country_code` |  |
| `157` | `vendor_customer_ids` |  |
| `158` | `is_pending_comp_cron` |  |
| `159` | `vendor_main_employee` |  |
| `160` | `deactivated_customers` |  |
| `161` | `vendor_contact_person` |  |
| `162` | `pending_comp_cron_time` |  |
| `163` | `vendor_currency_symbol` |  |
| `164` | `is_pending_comp_service` |  |
| `165` | `vendor_bank_branch_code` |  |
| `166` | `vendor_attachment_thumb` |  |
| `167` | `user_profile_show_vendor` |  |
| `168` | `is_vendor_active_for_customer` |  |
| `169` | `pr_id` | `✅used` |
| `170` | `pro_id` |  |
| `171` | `image_id` |  |
| `172` | `file_name` |  |
| `173` | `file_type` |  |
| `174` | `image_url` |  |
| `175` | `pr_rfq_id` | `✅used` |
| `176` | `thumb_url` |  |
| `177` | `created_at` |  |
| `178` | `updated_at` |  |
| `179` | `purchase_request_material_id` | `✅used` |

-------------------------


# **`3️⃣ Purchase Order`**

> **List of unused parameters in the API - `customer/purchaseRequestOrder/getPurchaseOrderLists`**


**Date: 16/10/25**

| **No** | **Parameter** | **Used/Unused** |
| --- | --- | --- |
| `1` | `pro_id` | `used` |
| `2` | `po_deadline` | `used` |
| `3` | `po_status` | `used` |
| `4` | `sap_po_number` | `used` |
| `5` | `po_vendor_document` |  |
| `6` | `is_deleted` | `used` |
| `7` | `collective_po_number` | `used` |
| `8` | `is_acknowledge` | `used` |
| `9` | `po_comparitive_document_link` | `used` |
| `10` | `po_reference_type` | `used` |
| `11` | `po_vendor_status` | `used` |
| `12` | `notifier_staff` |  |
| `13` | `tender_id` | `used` |
| `14` | `vendor_id` | `used` |
| `15` | `po_created_at` | `used` |
| `16` | `delete_remarks` | `used` |
| `17` | `cust_emp_id` |  |
| `18` | `pr_ids` |  |
| `19` | `ra_ids` |  |
| `20` | `pr_rfq_ids` |  |
| `21` | `arc_rfq_ids` |  |
| `22` | `advance_payment_notification` | `used` |
| `23` | `po_total_amount` |  |
| `24` | `vendor_code` | `used` |
| `25` | `vendor_name` | `used` |
| `26` | `vendor_email` | `used` |
| `27` | `vendor_phone` | `used` |
| `28` | `created_by` | `used` |
| `29` | `cust_emp_fname` | `used` |
| `30` | `cust_emp_lname` | `used` |
| `31` | `pr_number` | `used` |
| `32` | `collective_ra_no` | `used` |
| `33` | `rfq_details` | `used` |
| `34` | `arc_rfq_details` | `used` |
| `35` |  |  |
| `36` | `invoices` | `used` |
| `37` | `pr_rfq_id` |  |
| `38` | `rfq_status` | `used` |
| `39` | `collective_rfq_number` | `used` |
| `40` | `unit` | `used` |
| `41` | `unit_id` |  |
| `42` | `material_id` |  |
| `43` | `po_quantity` | `used` |
| `44` | `material_code` | `used` |
| `45` | `material_name` | `used` |
| `46` | `material_specification` | `used` |
| `47` | `material_short_description` | `used` |

---

> **List of unused parameters in the API - `customer/purchaseRequestOrder/getPurchaseOrderListDetails`**


**Date: 16/10/25**

| **Parameter** | **Used/Unused** |
| --- | --- |
| `pro_id` | `used` |
| `po_deadline` | `used` |
| `po_status` |  |
| `sap_po_number` | `used` |
| `is_deleted` | `used` |
| `collective_po_number` | `used` |
| `po_type_name` | `used` |
| `po_type_id` | `used` |
| `po_type_code` | `used` |
| `po_date` | `used` |
| `purchase_group_id` | `used` |
| `requisitioner_name` | `used` |
| `po_comparitive_link` |  |
| `is_acknowledge` |  |
| `po_comparitive_document_link` |  |
| `po_assignee_id` |  |
| `po_references` |  |
| `po_reference_type` | `used` |
| `po_vendor_status` |  |
| `pr_delivery_details` | `used` |
| `f_and_o` | `used` |
| `f_and_o_dec` | `used` |
| `payment_terms` | `used` |
| `delivery_terms` | `used` |
| `quantity_terms` | `used` |
| `payment_terms_dec` | `used` |
| `delivery_terms_dec` | `used` |
| `contact_person_name` | `used` |
| `contact_person_number` | `used` |
| `dms_id` | `used` |
| `tender_id` | `used` |
| `vendor_id` | `used` |
| `po_created_at` |  |
| `header_text` | `used` |
| `delete_remarks` |  |
| `department_name` | `used` |
| `department_id` | `used` |
| `notifier_staff` | `used` |
| `po_vendor_document` |  |
| `po_total_amount` |  |
| `po_remaining_amount` |  |
| `advance_payment_notification` |  |
| `old_pro_id` | `used` |
| `vendor_code` |  |
| `vendor_name` |  |
| `vendor_email` | `used` |
| `vendor_phone` |  |
| `created_by` | `used` |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `pr_number` | `used` |
| `collective_ra_no` | `used` |
| `dms_document_path` | `used` |
| `tender_document_path` | `used` |
| `rfq_details` |  |
| `pr_rfq_id` | `used` |
| `rfq_status` |  |
| `collective_rfq_number` | `used` |
| `arc_rfq_details` |  |
| `vendor_record` | `used` |
| `pro_id` | `used` |
| `f_and_o` | `used` |
| `rfq_type` |  |
| `pr_rfq_id` | `used` |
| `vendor_id` | `used` |
| `created_at` |  |
| `is_deleted` | `used` |
| `rfq_number` |  |
| `rfq_status` |  |
| `updated_at` |  |
| `cust_emp_id` | `used` |
| `customer_id` |  |
| `f_and_o_dec` | `used` |
| `total_amount` | `used` |
| `payment_terms` | `used` |
| `rfq_type_code` | `used` |
| `delivery_terms` | `used` |
| `quantity_terms` | `used` |
| `regret_remarks` | `used` |
| `vendor_remarks` | `used` |
| `reference_number` | `used` |
| `supplier_remarks` |  |
| `vendor_po_status` |  |
| `payment_terms_dec` | `used` |
| `delivery_terms_dec` | `used` |
| `contact_person_name` | `used` |
| `vendor_rfq_document` |  |
| `contact_person_email` | `used` |
| `rfq_vendor_master_id` |  |
| `contact_person_number` | `used` |
| `vendor_rfq_quotation_history` |  |
| `vendor_rfq_quotation_document` |  |
| `finalmateriallists` | `used` |
| `item` |  |
| `unit` | `used` |
| `pr_id` | `used` |
| `pro_id` | `used` |
| `f_and_o` | `used` |
| `unit_id` |  |
| `category` |  |
| `currency` | `used` |
| `plant_id` | `used` |
| `quantity` | `used` |
| `gst_price` |  |
| `item_note` | `used` |
| `item_text` | `used` |
| `order_qty` |  |
| `plant_gst` | `used` |
| `pr_rfq_id` | `used` |
| `vendor_id` | `used` |
| `created_at` |  |
| `is_deleted` | `used` |
| `plant_city` | `used` |
| `plant_code` | `used` |
| `plant_name` | `used` |
| `unit_price` | `used` |
| `updated_at` |  |
| `attachments` | `used` |
| `material_id` |  |
| `plant_state` | `used` |
| `po_quantity` | `used` |
| `total_amount` | `used` |
| `discount_type` | `used` |
| `initial_price` | `used` |
| `material_code` | `used` |
| `material_name` | `used` |
| `payment_terms` | `used` |
| `quantity_open` |  |
| `vendor_emp_id` |  |
| `discount_value` | `used` |
| `insurance_type` | `used` |
| `po_total_price` | `used` |
| `process_status` |  |
| `quotation_text` | `used` |
| `service_detail` | `used` |
| `insurance_value` | `used` |
| `quotation_price` |  |
| `discount_cn_type` | `used` |
| `gst_charge_value` | `used` |
| `invoice_delivery` | `used` |
| `item_category_id` |  |
| `quantity_ordered` |  |
| `quotation_status` |  |
| `cess_charge_value` | `used` |
| `insurance_cn_type` | `used` |
| `landed_unit_price` | `used` |
| `material_quantity` | `used` |
| `plant_postal_code` | `used` |
| `local_charges_type` | `used` |
| `local_charges_value` | `used` |
| `po_gst_charge_value` | `used` |
| `transportation_type` | `used` |
| `negotiate_unit_price` | `used` |
| `rfq_vendor_master_id` |  |
| `transportation_value` | `used` |
| `local_charges_cn_type` | `used` |
| `plant_additional_name` | `used` |
| `quotation_attachments` | `used` |
| `acc_assets_category_id` |  |
| `comparison_total_price` | `used` |
| `discount_lumpsum_value` | `used` |
| `loading_unloading_type` | `used` |
| `material_specification` | `used` |
| `po_vendor_quotation_id` |  |
| `transportation_cn_type` | `used` |
| `insurance_lumpsum_value` | `used` |
| `loading_unloading_value` | `used` |
| `material_service_detail` | `used` |
| `rfq_vendor_quotation_id` | `used` |
| `discount_lumpsum_cn_type` | `used` |
| `gst_charge_lumpsum_value` | `used` |
| `insurance_lumpsum_cn_type` | `used` |
| `loading_unloading_cn_type` | `used` |
| `packaging_forwarding_type` | `used` |
| `po_material_deadline_date` | `used` |
| `material_short_description` | `used` |
| `packaging_forwarding_value` | `used` |
| `local_charges_lumpsum_value` | `used` |
| `negotiate_landed_unit_price` | `used` |
| `packaging_forwarding_cn_type` | `used` |
| `purchase_request_material_id` | `used` |
| `transportation_lumpsum_value` | `used` |
| `local_charges_lumpsum_cn_type` | `used` |
| `transportation_lumpsum_cn_type` | `used` |
| `loading_unloading_lumpsum_value` | `used` |
| `loading_unloading_lumpsum_cn_type` | `used` |
| `packaging_forwarding_lumpsum_value` | `used` |
| `packaging_forwarding_lumpsum_cn_type` | `used` |
| `invoices` |  |
| `total_po_advance_amount` | `used` |

---

> **List of unused parameters in the API - `customer/purchaseRequestOrder/getAdvancePaymentRecordLists`**


**Date: 16/10/25**

| **Parameter** | **Used/Unused** |
| --- | --- |
| **papl_id** | used |
| **customer_id** | used |
| **cust_emp_id** |  |
| **pro_id** |  |
| **vendor_id** |  |
| **poi_id** | used |
| **po_advance_payment_type** | used |
| **po_advance_payment** | used |
| **created_at** |  |
| **updated_at** |  |
| **invoice_number** | used |
| **invoice_price** | used |
| **invoice_date** | used |
| **vendor_code** | used |
| **vendor_name** | used |


-------------------------



# **`4️⃣ ARC`**


> **List of unused parameters in the API - `customer/arcQuotation/getRFQlis`**
> 

**`Date: 17/10/25`**

| **Parameter** | **Used/Unused** |
| --- | --- |
| **`arc_rfq_id`** | used |
| **`arc_number`** | used |
| **`arc_deadline`** | used |
| **`arc_status`** | used |
| **`is_deleted`** | used |
| **`vendors_id`** | used |
| **`special_vendor_ids`** | used |
| **`collective_arc_number`** | used |
| **`arc_tendor_type`** | used |
| **`arc_type`** | used |
| **`arc_date`** | used |
| **`purchase_group_id`** |  |
| **`created_by`** | used |
| **`arc_type_code`** | used |
| **`tendor_type`** | used |
| **`arc_oc`** | used |
| **`arc_extend_status`** | used |
| **`negotiation_deadlinedate`** | used |
| **`is_show_negotiate`** | used |
| **`contract_name`** | used |
| **`cust_emp_fname`** | used |
| **`cust_emp_lname`** | used |
| **`approved_date`** | used |
| **`arc_title`** | used |
| **`pr_number`** | used |
| **`requisitioner_names`** | used |
| **`total_queries`** | used |
| **`unread_queries`** | used |
| **`comparitive_reports`** |  |
| **`ch_id`** |  |
| **`file_path`** |  |
| **`arc_rfq_id`** | used |
| **`created_at`** |  |
| **`cust_emp_id`** | used |
| **`customer_id`** |  |
| **`updated_comparision_report`** | used |
| **`po_attachments`** |  |
| **`oem_vendor_count`** | used |
| **`bidder_vendor_count`** | used |

---

> **List of unused parameters in the API - `customer/arcQuotation/get_rfq_details`**


**`Date: 17/10/25`**

| **Parameter** | **Used/Unused** |
| --- | --- |
| **`arc_rfq_id`** | used |
| **`arc_number`** |  |
| **`arc_deadline`** | used |
| **`arc_status`** | used |
| **`is_deleted`** | used |
| **`vendors_id`** |  |
| **`special_vendor_ids`** | used |
| **`vendor_email_ids`** |  |
| **`tendor_type`** |  |
| **`collective_arc_number`** |  |
| **`arc_tendor_type`** |  |
| **`arc_type`** |  |
| **`arc_date`** |  |
| **`purchase_group_id`** |  |
| **`created_by`** |  |
| **`arc_type_code`** | used |
| **`arc_oc`** |  |
| **`arc_extend_status`** |  |
| **`negotiation_deadlinedate`** |  |
| **`is_show_negotiate`** |  |
| **`contract_name`** |  |
| **`cust_emp_fname`** |  |
| **`cust_emp_lname`** |  |
| **`arc_title`** |  |
| **`pr_number`** |  |
| **`selected_vendors_details`** |  |
| **`requisitioner_names`** |  |
| **`total_queries`** |  |
| **`unread_queries`** |  |
| **`quotationlists`** |  |
| **`pro_id`** |  |
| **`f_and_o`** |  |
| **`vendor_id`** |  |
| **`arc_number`** |  |
| **`arc_rfq_id`** | used |
| **`arc_status`** | used |
| **`created_at`** |  |
| **`is_deleted`** |  |
| **`updated_at`** |  |
| **`cust_emp_id`** | used |
| **`customer_id`** | used |
| **`f_and_o_dec`** |  |
| **`gst_remarks`** |  |
| **`vendor_code`** |  |
| **`vendor_name`** |  |
| **`total_amount`** |  |
| **`vendor_email`** |  |
| **`vendor_phone`** |  |
| **`payment_terms`** |  |
| **`delivery_terms`** |  |
| **`quantity_terms`** |  |
| **`regret_remarks`** |  |
| **`unread_queries`** |  |
| **`vendor_remarks`** |  |
| **`arc_contract_id`** |  |
| **`reference_number`** |  |
| **`supplier_remarks`** |  |
| **`vendor_po_status`** |  |
| **`payment_terms_dec`** |  |
| **`delivery_terms_dec`** |  |
| **`contact_person_name`** |  |
| **`vendor_arc_document`** |  |
| **`arc_vendor_master_id`** |  |
| **`contact_person_email`** |  |
| **`contact_person_number`** |  |
| **`vendor_rfq_quotation_history`** |  |
| **`vendor_arc_quotation_document`** |  |
| **`vendoremaillists`** |  |
| **`comparitive_reports`** |  |
| **`ch_id`** |  |
| **`file_path`** |  |
| **`updated_comparision_report`** |  |
| **`po_attachments`** |  |
| **`materiallists`** |  |
| **`arc_request_material_id`** | used |
| **`pr_id`** |  |
| **`material_id`** |  |
| **`material_code`** |  |
| **`material_group_id`** |  |
| **`material_group_code`** |  |
| **`acc_assets_category_id`** |  |
| **`category`** | used |
| **`item_category_id`** |  |
| **`item`** |  |
| **`quantity`** | used |
| **`unit_id`** | used |
| **`unit`** | used |
| **`total_price`** |  |
| **`plant_id`** | used |
| **`purchase_organization`** |  |
| **`purchase_group_id`** |  |
| **`purchase_group_code`** |  |
| **`tracking_number`** |  |
| **`material_revision`** |  |
| **`quantity_ordered`** |  |
| **`quantity_open`** |  |
| **`request_date`** |  |
| **`release_date`** |  |
| **`pl_delivery_time`** |  |
| **`gr_proc_time`** |  |
| **`delivery_text`** |  |
| **`material_po_text`** |  |
| **`process_status`** |  |
| **`purchase_requisition_status`** |  |
| **`order_qty`** |  |
| **`uploading_point`** |  |
| **`recipient`** |  |
| **`g_l_account`** |  |
| **`assets`** |  |
| **`co_area`** |  |
| **`assignment_order`** |  |
| **`wbs_element`** |  |
| **`funds_center`** |  |
| **`requisitioner`** |  |
| **`requisitioner_name`** |  |
| **`vendor_detail`** |  |
| **`goods_receipt`** |  |
| **`invoice_receipt`** |  |
| **`item_text`** |  |
| **`item_note`** |  |
| **`delivery_date`** |  |
| **`initial_price`** |  |
| **`rfq_delivery_date`** |  |
| **`distribution`** |  |
| **`material_specification`** |  |
| **`service_detail`** |  |
| **`id`** |  |
| **`isEdit`** | used |
| **`row_id`** | used |
| **`currency`** | used |
| **`short_text`** | used |
| **`unit_price`** |  |
| **`cost_center`** | used |
| **`gross_price`** |  |
| **`service_number`** | used |
| **`arc_category_id`** | used |
| **`arc_category_name`** | used |
| **`annual_tentative_requirement`** |  |
| **`arc_sub_category_id`** | used |
| **`arc_sub_category_name`** | used |
| **`po_order_quantity`** |  |
| **`is_materil_po_created`** |  |
| **`sap_item`** | used |
| **`material_name`** |  |
| **`material_short_description`** |  |
| **`vendorqueries`** |  |
| **`attachments`** | used |

---

> **List of unused parameters in the API - `customer/arcQuotation/comparisionRFQApproverHistory`**


**`Date: 17/10/25`**

| **Parameter** | **Used/Unused** |
| --- | --- |
| **workflow_approval_id** | used |
| **customer_id** | used |
| **arc_rfq_id** | used |
| **cust_emp_id** | used |
| **remarks** | used |
| **is_delete** |  |
| **created_at** | used |
| **updated_at** | used |
| **deleted_at** |  |
| **approved_at** | used |
| **approval_status** | used |
| **comparative_link** | used |
| **approval_type** | used |
| **level_name** | used |
| **is_already_used** |  |
| **remarks_text** |  |
| **approval_assigne_at** |  |
| **approval_time** |  |
| **is_enquiry_important** | used |
| **reminder_cron_run** |  |
| **is_hold** |  |
| **is_unread** |  |
| **approval_hold_at** |  |
| **is_return** |  |
| **cust_emp_fname** | used |
| **cust_emp_lname** | used |
| **ceb_prefix** | used |

---

> **List of unused parameters in the API - `customer/arcQuotation/getDeleteRequestQuotation`**


**`Date: 17/10/25`**

| **Parameter** | **Used/Unused** |
| --- | --- |
| **`arc_rfq_id`** |  |
| **`arc_number`** |  |
| **`arc_deadline`** | `used` |
| **`arc_status`** |  |
| **`is_deleted`** |  |
| **`vendors_id`** |  |
| **`collective_arc_number`** | `used` |
| **`arc_tendor_type`** |  |
| **`arc_type`** |  |
| **`arc_date`** | `used` |
| **`purchase_group_id`** |  |
| **`created_by`** | `used` |
| **`arc_oc`** |  |
| **`arc_type_code`** |  |
| **`arc_extend_status`** |  |
| **`negotiation_deadlinedate`** |  |
| **`is_show_negotiate`** |  |
| **`remarks`** | `used` |
| **`contract_name`** | `used` |
| **`cust_emp_fname`** |  |
| **`cust_emp_lname`** |  |

---

> **List of unused parameters in the API - `customer/arcQuotation/getRequestQuotationARCDetails`**


**`Date: 17/10/25`**

| **Parameter** | **Used/Unused** |
| --- | --- |
| **`arc_number`** | **`used`** |
| **`arc_deadline`** | **`used`** |
| **`arc_status`** | **`used`** |
| **`is_deleted`** | **`used`** |
| **`vendors_id`** | **`used`** |
| **`vendor_email_ids`** | **`used`** |
| **`tendor_type`** | **`used`** |
| **`collective_arc_number`** | **`used`** |
| **`arc_tendor_type`** | **`used`** |
| **`arc_type`** | **`used`** |
| **`arc_date`** | **`used`** |
| **`purchase_group_id`** | **`used`** |
| **`created_by`** | **`used`** |
| **`arc_type_code`** | **`used`** |
| **`arc_oc`** |  |
| **`arc_extend_status`** |  |
| **`negotiation_deadlinedate`** |  |
| **`is_show_negotiate`** |  |
| **`contract_name`** | **`used`** |
| **`cust_emp_fname`** | **`used`** |
| **`cust_emp_lname`** | **`used`** |
| **`pr_number`** | **`used`** |
| **`requisitioner_names`** |  |
| **`total_queries`** |  |
| **`unread_queries`** |  |
| **`quotationlists`** | **`used`** |
| **`pro_id`** |  |
| **`f_and_o`** |  |
| **`vendor_id`** | **`used`** |
| **`arc_rfq_id`** | **`used`** |
| **`created_at`** |  |
| **`updated_at`** |  |
| **`cust_emp_id`** | **`used`** |
| **`customer_id`** | **`used`** |
| **`f_and_o_dec`** |  |
| **`gst_remarks`** |  |
| **`vendor_code`** |  |
| **`vendor_name`** |  |
| **`total_amount`** |  |
| **`vendor_email`** |  |
| **`vendor_phone`** |  |
| **`payment_terms`** |  |
| **`delivery_terms`** |  |
| **`quantity_terms`** |  |
| **`regret_remarks`** |  |
| **`vendor_remarks`** |  |
| **`arc_contract_id`** |  |
| **`reference_number`** |  |
| **`supplier_remarks`** |  |
| **`vendor_po_status`** |  |
| **`payment_terms_dec`** |  |
| **`delivery_terms_dec`** |  |
| **`contact_person_name`** |  |
| **`vendor_arc_document`** |  |
| **`arc_vendor_master_id`** |  |
| **`contact_person_email`** |  |
| **`contact_person_number`** |  |
| **`vendor_rfq_quotation_history`** |  |
| **`vendor_arc_quotation_document`** | **`used`** |
| **`vendoremaillists`** | **`used`** |
| **`comparitive_reports`** |  |
| **`ch_id`** |  |
| **`file_path`** |  |
| **`updated_comparision_report`** |  |
| **`po_attachments`** |  |
| **`image_id`** | **`used`** |
| **`file_name`** |  |
| **`file_type`** |  |
| **`image_url`** |  |
| **`thumb_url`** |  |
| **`materiallists`** | **`used`** |
| **`arc_request_material_id`** | **`used`** |
| **`pr_id`** | **`used`** |
| **`material_id`** | **`used`** |
| **`material_code`** | **`used`** |
| **`material_group_id`** | **`used`** |
| **`material_group_code`** | **`used`** |
| **`acc_assets_category_id`** | **`used`** |
| **`category`** | **`used`** |
| **`item_category_id`** | **`used`** |
| **`item`** | **`used`** |
| **`quantity`** | **`used`** |
| **`unit_id`** | **`used`** |
| **`unit`** | **`used`** |
| **`total_price`** | **`used`** |
| **`plant_id`** | **`used`** |
| **`purchase_organization`** | **`used`** |
| **`purchase_group_code`** | **`used`** |
| **`tracking_number`** | **`used`** |
| **`material_revision`** |  |
| **`quantity_ordered`** |  |
| **`quantity_open`** |  |
| **`request_date`** |  |
| **`release_date`** |  |
| **`pl_delivery_time`** |  |
| **`gr_proc_time`** |  |
| **`delivery_text`** | **`used`** |
| **`material_po_text`** | **`used`** |
| **`process_status`** | **`used`** |
| **`purchase_requisition_status`** | **`used`** |
| **`order_qty`** | **`used`** |
| **`uploading_point`** | **`used`** |
| **`recipient`** | **`used`** |
| **`g_l_account`** | **`used`** |
| **`assets`** | **`used`** |
| **`co_area`** | **`used`** |
| **`assignment_order`** | **`used`** |
| **`wbs_element`** | **`used`** |
| **`funds_center`** | **`used`** |
| **`requisitioner`** | **`used`** |
| **`requisitioner_name`** | **`used`** |
| **`vendor_detail`** | **`used`** |
| **`goods_receipt`** |  |
| **`invoice_receipt`** |  |
| **`item_text`** | **`used`** |
| **`item_note`** | **`used`** |
| **`delivery_date`** | **`used`** |
| **`initial_price`** |  |
| **`rfq_delivery_date`** | **`used`** |
| **`distribution`** |  |
| **`material_specification`** | **`used`** |
| **`service_detail`** | **`used`** |
| **`arc_category_id`** | **`used`** |
| **`arc_category_name`** | **`used`** |
| **`annual_tentative_requirement`** | **`used`** |
| **`arc_sub_category_id`** | **`used`** |
| **`arc_sub_category_name`** | **`used`** |
| **`po_order_quantity`** |  |
| **`is_materil_po_created`** |  |
| **`sap_item`** | **`used`** |
| **`material_name`** | **`used`** |
| **`material_short_description`** | **`used`** |
| **`vendorqueries`** | **`used`** |
| **`attachments`** | **`used`** |

-------------------------


# **`5️⃣ ARC Contract`**



> **List of unused parameters in the API (Pagination API) - `customer/arcContractOrder/getPurchaseOrderLists`**



| **Parameters** | **Used/Unused** |
| --- | --- |
| `arc_contract_id` | `used` |
| `po_deadline` | `used` |
| `po_status` | `used` |
| `sap_po_number` | `used` |
| `arc_tender_type` |  |
| `arc_contract_start_date` | `used` |
| `arc_contract_end_date` | `used` |
| `is_deleted` | `used` |
| `collective_arc_number` | `used` |
| `po_type_name` | `used` |
| `po_type_id` | `used` |
| `po_type_code` | `used` |
| `po_date` | `used` |
| `purchase_group_id` | `used` |
| `requisitioner_name` | `used` |
| `po_comparitive_link` |  |
| `po_comparitive_document_link` | `used` |
| `po_assignee_id` |  |
| `po_references` |  |
| `po_reference_type` | `used` |
| `po_vendor_status` | `used` |
| `pr_delivery_details` | `used` |
| `f_and_o` | `used` |
| `f_and_o_dec` | `used` |
| `payment_terms` | `used` |
| `delivery_terms` | `used` |
| `quantity_terms` | `used` |
| `payment_terms_dec` | `used` |
| `delivery_terms_dec` | `used` |
| `contact_person_name` | `used` |
| `contact_person_number` | `used` |
| `dms_id` | `used` |
| `vendor_id` | `used` |
| `po_created_at` | `used` |
| `header_text` | `used` |
| `delete_remarks` | `used` |
| `department_name` | `used` |
| `notifier_staff` | `used` |
| `po_vendor_document` |  |
| `po_total_amount` |  |
| `is_acknowledge` | `used` |
| `vendor_code` | `used` |
| `vendor_name` | `used` |
| `vendor_email` |  |
| `vendor_phone` |  |
| `created_by` | `used` |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `dms_document_path` | `used` |
| `arc_rfq_details` | `used` |
| `arc_rfq_id` | `used` |
| `arc_status` |  |
| `vendor_record` | `used` |
| `finalmateriallists` | `used` |
| `item` | `used` |
| `unit` | `used` |
| `pr_id` | `used` |
| `pro_id` |  |
| `unit_id` |  |
| `category` |  |
| `currency` |  |
| `plant_id` |  |
| `quantity` | `used` |
| `gst_price` |  |
| `item_note` |  |
| `item_text` |  |
| `order_qty` |  |
| `created_at` | `used` |
| `unit_price` |  |
| `updated_at` |  |
| `attachments` |  |
| `material_id` |  |
| `po_quantity` | `used` |
| `total_amount` |  |
| `discount_type` |  |
| `initial_price` |  |
| `material_code` | `used` |
| `material_name` | `used` |
| `plant_details` |  |
| `plant_gst` |  |
| `plant_city` |  |
| `plant_code` |  |
| `plant_name` |  |
| `customer_id` |  |
| `plant_state` |  |
| `plant_postal_code` |  |
| `plant_additional_name` |  |
| `quantity_open` |  |
| `vendor_emp_id` |  |
| `discount_value` |  |
| `insurance_type` |  |
| `po_total_price` |  |
| `process_status` |  |
| `quotation_text` |  |
| `service_detail` |  |
| `insurance_value` |  |
| `quotation_price` |  |
| `discount_cn_type` |  |
| `gst_charge_value` |  |
| `invoice_delivery` |  |
| `item_category_id` |  |
| `quantity_ordered` |  |
| `quotation_status` |  |
| `arc_category_name` | `used` |
| `cess_charge_value` |  |
| `insurance_cn_type` |  |
| `landed_unit_price` |  |
| `material_quantity` |  |
| `local_charges_type` |  |
| `local_charges_value` |  |
| `po_gst_charge_value` |  |
| `transportation_type` |  |
| `arc_vendor_master_id` | `used` |
| `landed_unit_wo_price` |  |
| `negotiate_unit_price` |  |
| `transportation_value` |  |
| `arc_sub_category_name` | `used` |
| `local_charges_cn_type` |  |
| `quotation_attachments` |  |
| `acc_assets_category_id` |  |
| `comparison_total_price` |  |
| `discount_lumpsum_value` |  |
| `loading_unloading_type` |  |
| `material_specification` | `used` |
| `transportation_cn_type` |  |
| `arc_request_material_id` |  |
| `arc_vendor_quotation_id` | `used` |
| `insurance_lumpsum_value` |  |
| `loading_unloading_value` |  |
| `material_service_detail` |  |
| `arc_price_service_detail` |  |
| `discount_lumpsum_cn_type` |  |
| `gst_charge_lumpsum_value` |  |
| `insurance_lumpsum_cn_type` |  |
| `loading_unloading_cn_type` |  |
| `packaging_forwarding_type` |  |
| `po_material_deadline_date` |  |
| `material_short_description` | `used` |
| `packaging_forwarding_value` |  |
| `local_charges_lumpsum_value` |  |
| `negotiate_landed_unit_price` |  |
| `packaging_forwarding_cn_type` |  |
| `transportation_lumpsum_value` |  |
| `local_charges_lumpsum_cn_type` |  |
| `transportation_lumpsum_cn_type` |  |
| `loading_unloading_lumpsum_value` |  |
| `loading_unloading_lumpsum_cn_type` |  |
| `packaging_forwarding_lumpsum_value` |  |
| `packaging_forwarding_lumpsum_cn_type` |  |

---

> **List of unused parameters in the API (API Called when taking reference for creating a new ARC Contract) - `customer/arcQuotation/getRFQApprovedRecord`**
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `arc_rfq_id` | `used` |
| `arc_number` |  |
| `arc_deadline` |  |
| `arc_status` |  |
| `is_deleted` |  |
| `vendors_id` | `used` |
| `collective_arc_number` | `used` |
| `arc_tendor_type` |  |
| `arc_type` |  |
| `arc_date` |  |
| `purchase_group_id` | `used` |
| `created_by` | `used` |
| `arc_type_code` |  |
| `arc_oc` |  |
| `arc_extend_status` |  |
| `negotiation_deadlinedate` |  |
| `is_show_negotiate` |  |
| `contract_name` |  |
| `cust_emp_fname` |  |
| `cust_emp_lname` |  |
| `vendorlists` | `used` |
| `pro_id` |  |
| `f_and_o` | `used` |
| `pr_number` | `used` |
| `vendor_id` | `used` |
| `created_at` |  |
| `updated_at` |  |
| `cust_emp_id` |  |
| `customer_id` |  |
| `f_and_o_dec` | `used` |
| `gst_remarks` |  |
| `rfq_created` |  |
| `vendor_code` | `used` |
| `vendor_name` | `used` |
| `total_amount` |  |
| `vendor_email` |  |
| `vendor_phone` |  |
| `materiallists` |  |
| `payment_terms` | `used` |
| `delivery_terms` | `used` |
| `quantity_terms` | `used` |
| `regret_remarks` |  |
| `vendor_remarks` | `used` |
| `arc_contract_id` | `used` |
| `reference_number` | `used` |
| `supplier_remarks` |  |
| `vendor_po_status` |  |
| `payment_terms_dec` | `used` |
| `delivery_terms_dec` | `used` |
| `instruction_policy` |  |
| `contact_person_name` |  |
| `negotiation_remarks` |  |
| `vendor_arc_document` |  |
| `arc_vendor_master_id` | `used` |
| `contact_person_email` |  |
| `contact_person_number` | `used` |
| `vendor_rfq_quotation_history` |  |
| `vendor_arc_quotation_document` |  |
| `updated_comparision_report` |  |


---



| **Parameters** | **Used/Unused** |
| --- | --- |
| `workflow_approval_id` | `used` |
| `customer_id` | `used` |
| `arc_contract_id` | `used` |
| `cust_emp_id` | `used` |
| `remarks` | `used` |
| `is_delete` |  |
| `created_at` | `used` |
| `updated_at` | `used` |
| `deleted_at` |  |
| `approved_at` | `used` |
| `approval_status` | `used` |
| `comparative_link` | `used` |
| `approval_type` | `used` |
| `level_name` | `used` |
| `is_already_used` |  |
| `approval_assigne_at` |  |
| `approval_time` |  |
| `is_hold` |  |
| `is_unread` |  |
| `approval_hold_at` |  |
| `is_return` |  |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `ceb_prefix` | `used` |

---




# **`6️⃣ Purchase DMS`**



> **List of unused parameters in the API (Pagination API) -** `customer/dmsdocument/getDocumentCollectionLists`
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `dms_id` | `used` |
| `customer_id` | `used` |
| `cust_emp_id` | `used` |
| `document_type_id` |  |
| `dms_number` | `used` |
| `dms_assignee_id` |  |
| `dms_status` | `used` |
| `is_deleted` | `used` |
| `created_at` |  |
| `updated_at` |  |
| `dms_document` | `used` |
| `release_remarks` |  |
| `ref_number` | `used` |
| `dms_date` |  |
| `dms_subject` | `used` |
| `dms_description` | `used` |
| `tender_ref` | `used` |
| `tender_notice_ref` | `used` |
| `dms_ref` |  |
| `delete_remarks` | `used` |
| `dept_id` | `used` |
| `next_assignee_ids` |  |
| `is_auto_release` |  |
| `auction_ref` |  |
| `document_name` | `used` |
| `document_code` |  |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `attachmentrecords` | `used` |
| `image_id` | `used` |
| `file_name` | `used` |
| `file_type` | `used` |
| `image_url` | `used` |
| `thumb_url` | `used` |
| `release_records` | `used` |
| `drs_id` | `used` |
| `is_hold` |  |
| `remarks` | `used` |
| `is_delete` |  |
| `is_return` |  |
| `is_unread` |  |
| `deleted_at` |  |
| `level_name` | `used` |
| `approved_at` | `used` |
| `assignee_id` | `used` |
| `emp_fullname` | `used` |
| `remarks_text` |  |
| `approval_time` |  |
| `approval_type` | `used` |
| `approval_status` | `used` |
| `is_already_used` |  |
| `strategy_status` | `used` |
| `approval_hold_at` |  |
| `comparative_link` |  |
| `approval_assigne_at` |  |
| `po_attachments` |  |

---

> **List of unused parameters in the API (Pagination API) -** `customer/dmsdocument/getDeletedDocumentCollectionLists`
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `dms_id` | `used` |
| `customer_id` | `used` |
| `cust_emp_id` | `used` |
| `document_type_id` |  |
| `dms_number` |  |
| `dms_assignee_id` |  |
| `dms_status` | `used` |
| `is_deleted` | `used` |
| `created_at` |  |
| `updated_at` |  |
| `dms_document` |  |
| `release_remarks` |  |
| `ref_number` | `used` |
| `dms_date` |  |
| `dms_subject` | `used` |
| `dms_description` |  |
| `tender_ref` |  |
| `tender_notice_ref` |  |
| `dms_ref` |  |
| `delete_remarks` | `used` |
| `dept_id` | `used` |
| `next_assignee_ids` |  |
| `is_auto_release` |  |
| `auction_ref` |  |
| `document_name` | `used` |
| `document_code` |  |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `attachmentrecords` | `used` |
| `release_records` | `used` |
| `created_at` |  |
| `dms_id` | `used` |
| `file_name` | `used` |
| `file_type` | `used` |
| `image_id` | `used` |
| `image_url` | `used` |
| `thumb_url` | `used` |
| `updated_at` |  |

---



# **`7️⃣ Document Management System`**


> **List of unused parameters in the API (Pagination API) - `customer/dmsdocument/getDocumentCollectionLists`**
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `dms_id` | `used` |
| `customer_id` | `used` |
| `cust_emp_id` | `used` |
| `document_type_id` | `used` |
| `dms_number` | `used` |
| `dms_assignee_id` |  |
| `dms_status` | `used` |
| `is_deleted` | `used` |
| `created_at` |  |
| `updated_at` |  |
| `dms_document` | `used` |
| `release_remarks` |  |
| `ref_number` | `used` |
| `dms_date` | `used` |
| `dms_subject` | `used` |
| `dms_description` | `used` |
| `tender_ref` | `used` |
| `tender_notice_ref` | `used` |
| `dms_ref` |  |
| `delete_remarks` | `used` |
| `dept_id` | `used` |
| `next_assignee_ids` |  |
| `is_auto_release` |  |
| `auction_ref` | `used` |
| `document_name` | `used` |
| `document_code` | `used` |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `attachmentrecords` | `used` |
| `image_id` | `used` |
| `file_name` | `used` |
| `file_type` | `used` |
| `image_url` | `used` |
| `thumb_url` | `used` |
| `release_records` | `used` |
| `drs_id` | `used` |
| `is_hold` |  |
| `remarks` | `used` |
| `is_delete` |  |
| `is_return` |  |
| `is_unread` |  |
| `deleted_at` |  |
| `level_name` | `used` |
| `approved_at` | `used` |
| `assignee_id` | `used` |
| `emp_fullname` | `used` |
| `remarks_text` |  |
| `approval_time` |  |
| `approval_type` | `used` |
| `approval_status` | `used` |
| `is_already_used` |  |
| `strategy_status` | `used` |
| `approval_hold_at` |  |
| `comparative_link` |  |
| `approval_assigne_at` |  |
| `po_attachments` | `used` |

---

> **List of unused parameters in the API (Pagination API) - `customer/dmsdocument/getDocumentCollectionLists`**
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `dms_id` | `used` |
| `customer_id` | `used` |
| `cust_emp_id` | `used` |
| `document_type_id` |  |
| `dms_number` | `used` |
| `dms_assignee_id` |  |
| `dms_status` | `used` |
| `is_deleted` | `used` |
| `created_at` | `used` |
| `updated_at` |  |
| `dms_document` |  |
| `release_remarks` |  |
| `ref_number` |  |
| `dms_date` |  |
| `dms_subject` | `used` |
| `dms_description` |  |
| `tender_ref` |  |
| `tender_notice_ref` |  |
| `dms_ref` |  |
| `delete_remarks` | `used` |
| `dept_id` | `used` |
| `auction_ref` |  |
| `document_name` | `used` |
| `document_code` |  |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `attachmentrecords` | `used` |
| `image_id` | `used` |
| `file_name` | `used` |
| `file_type` | `used` |
| `image_url` | `used` |
| `thumb_url` | `used` |
| `release_records` | `used` |
| `drs_id` | `used` |
| `is_hold` |  |
| `remarks` | `used` |
| `is_delete` |  |
| `is_return` |  |
| `is_unread` |  |
| `deleted_at` |  |
| `level_name` | `used` |
| `approved_at` | `used` |
| `assignee_id` | `used` |
| `emp_fullname` | `used` |
| `approval_time` |  |
| `approval_type` | `used` |
| `approval_status` | `used` |
| `is_already_used` |  |
| `strategy_status` | `used` |
| `approval_hold_at` |  |
| `comparative_link` |  |
| `approval_assigne_at` |  |
| `po_attachments` |  |

---


# **`8️⃣ Request Management`**


> **List of unused parameters in the API (Pagination API) - `customer/requests_master/getRequestsCollectionLists`**
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `request_id` | `used` |
| `customer_id` | `used` |
| `cust_emp_id` | `used` |
| `collective_request_no` | `used` |
| `request_form_id` | `used` |
| `request_form_fields` | `used` |
| `latitude` | `used` |
| `longitude` | `used` |
| `request_extra` | `used` |
| `selection_type` | `used` |
| `selection_view` | `used` |
| `field_selection` | `used` |
| `request_field` | `used` |
| `request_field_id` | `used` |
| `request_field_type` | `used` |
| `request_data_exists` |  |
| `request_field_value` | `used` |
| `request_field_required` | `used` |
| `request_status` | `used` |
| `request_deleted` | `used` |
| `request_assignee_id` | `used` |
| `request_delete_reason` |  |
| `request_document` | `used` |
| `request_approval_document` | `used` |
| `created_at` | `used` |
| `updated_at` |  |
| `release_remarks` |  |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `role_name` | `used` |
| `release_records` | `used` |
| `is_edit` | `used` |
| `is_hold` |  |
| `remarks` | `used` |
| `is_delete` |  |
| `is_return` |  |
| `is_unread` |  |
| `deleted_at` |  |
| `level_name` | `used` |
| `approved_at` | `used` |
| `assignee_id` | `used` |
| `emp_fullname` | `used` |
| `approval_time` |  |
| `approval_type` | `used` |
| `approval_status` | `used` |
| `is_already_used` |  |
| `strategy_status` | `used` |
| `approval_hold_at` |  |
| `comparative_link` |  |
| `approval_assigne_at` |  |
| `workflow_approval_id` | `used` |

---

> **List of unused parameters in the API (Pagination API) - `customer/requests_master/getDeletedRequestCollectionLists`**
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `request_id` | `used` |
| `customer_id` | `used` |
| `cust_emp_id` | `used` |
| `collective_request_no` | `used` |
| `request_form_id` | `used` |
| `request_form_fields` | `used` |
| `request_extra` | `used` |
| `request_field` | `used` |
| `request_field_id` | `used` |
| `request_field_type` | `used` |
| `request_field_value` | `used` |
| `request_field_required` | `used` |
| `request_status` | `used` |
| `request_deleted` | `used` |
| `request_assignee_id` | `used` |
| `request_delete_reason` |  |
| `request_document` | `used` |
| `request_approval_document` | `used` |
| `created_at` | `used` |
| `updated_at` |  |
| `release_remarks` |  |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `role_name` | `used` |
| `release_records` | `used` |
| `is_edit` | `used` |
| `is_hold` |  |
| `remarks` | `used` |
| `is_delete` |  |
| `is_return` |  |
| `is_unread` |  |
| `deleted_at` |  |
| `level_name` | `used` |
| `approved_at` | `used` |
| `assignee_id` | `used` |
| `emp_fullname` | `used` |
| `remarks_text` |  |
| `approval_time` |  |
| `approval_type` | `used` |
| `approval_status` | `used` |
| `is_already_used` |  |
| `strategy_status` | `used` |
| `approval_hold_at` |  |
| `comparative_link` |  |
| `approval_assigne_at` |  |
| `workflow_approval_id` | `used` |

---




# **`9️⃣ Workflow Management`**


> **List of unused parameters in the API (Pagination API) - `customer/requestQuotation/getWorkflowRequestQuotationRecords`**
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `pr_rfq_id` | `used` |
| `rfq_title` | `used` |
| `is_enquiry_important` | `used` |
| `is_return` | `used` |
| `is_hold` | `used` |
| `is_unread` | `used` |
| `rfq_number` | `used` |
| `rfq_deadline` | `used` |
| `rfq_status` | `used` |
| `is_deleted` | `used` |
| `vendors_id` | `used` |
| `collective_rfq_number` | `used` |
| `tendor_type` | `used` |
| `rfq_type` | `used` |
| `rfq_date` | `used` |
| `purchase_group_id` |  |
| `created_by` |  |
| `category_ids` |  |
| `rfq_oc` |  |
| `rfq_extend_status` |  |
| `negotiation_deadlinedate` | `used` |
| `is_show_negotiate` | `used` |
| `approval_assign_id` |  |
| `currency_detail` | `used` |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `workflow_approval_id` | `used` |
| `remarks` | `used` |
| `approval_type` | `used` |
| `level_name` | `used` |
| `workflow_createor_date` | `used` |
| `approval_assigne_at` |  |
| `rfq_work_apprpval_date` | `used` |
| `workflow_approved_at` | `used` |
| `workflow_assign_at` | `used` |
| `pr_number` | `used` |
| `total_queries` | `used` |
| `unread_queries` | `used` |
| `comparision_report` |  |
| `comparitive_report` | `used` |
| `technical_attachments` |  |
| `materiallists` | `used` |
| `purchase_request_material_id` | `used` |
| `pr_id` | `used` |
| `material_id` | `used` |
| `material_code` | `used` |
| `material_group_id` |  |
| `material_group_code` |  |
| `acc_assets_category_id` |  |
| `category` |  |
| `item_category_id` |  |
| `item` |  |
| `quantity` | `used` |
| `unit_id` | `used` |
| `unit` | `used` |
| `total_price` |  |
| `plant_id` |  |
| `plant_code` |  |
| `purchase_organization` |  |
| `purchase_group_code` |  |
| `tracking_number` |  |
| `material_revision` |  |
| `quantity_ordered` |  |
| `quantity_open` |  |
| `request_date` |  |
| `release_date` |  |
| `pl_delivery_time` |  |
| `gr_proc_time` |  |
| `delivery_text` |  |
| `material_po_text` |  |
| `process_status` |  |
| `purchase_requisition_status` |  |
| `order_qty` |  |
| `uploading_point` |  |
| `recipient` |  |
| `g_l_account` |  |
| `assets` |  |
| `co_area` |  |
| `assignment_order` |  |
| `wbs_element` |  |
| `funds_center` |  |
| `created_at` | `used` |
| `updated_at` | `used` |
| `requisitioner` |  |
| `requisitioner_name` | `used` |
| `vendor_id` | `used` |
| `vendor_detail` |  |
| `goods_receipt` |  |
| `invoice_receipt` |  |
| `item_text` |  |
| `item_note` |  |
| `delivery_date` |  |
| `initial_price` |  |
| `rfq_delivery_date` |  |
| `distribution` |  |
| `material_specification` | `used` |
| `service_detail` |  |
| `pro_id` | `used` |
| `ra_id` | `used` |
| `maximum_price` |  |
| `po_order_quantity` |  |
| `is_materil_po_created` |  |
| `sap_item` |  |
| `arc_contract_id` | `used` |
| `asking_price` |  |
| `asking_quantity` |  |
| `unit_price` |  |
| `prm_publish_type` |  |
| `prm_selected_vendors` |  |
| `pending_quantity` |  |
| `prm_end_date` |  |
| `prm_ra_extenstion_counter` |  |
| `fixed_qty` |  |
| `material_name` | `used` |
| `material_short_description` | `used` |
| `quotationlists` | `used` |
| `rfq_vendor_master_id` | `used` |
| `customer_id` | `used` |
| `vendor_rfq_document` |  |
| `vendor_rfq_quotation_document` | `used` |
| `cust_emp_id` | `used` |
| `f_and_o_dec` |  |
| `f_and_o` |  |
| `payment_terms_dec` | `used` |
| `payment_terms` |  |
| `total_amount` | `used` |
| `regret_remarks` |  |
| `vendor_remarks` |  |
| `supplier_remarks` |  |
| `delivery_terms_dec` | `used` |
| `delivery_terms` |  |
| `quantity_terms` |  |
| `reference_number` |  |
| `contact_person_name` |  |
| `contact_person_number` |  |
| `vendor_rfq_quotation_history` | `used` |
| `contact_person_email` |  |
| `vendor_po_status` |  |
| `vendor_code` | `used` |
| `vendor_name` | `used` |
| `workflow_history_records` |  |
| `is_delete` |  |
| `deleted_at` |  |
| `approved_at` | `used` |
| `approval_status` | `used` |
| `comparative_link` | `used` |
| `is_already_used` | `used` |
| `remarks_text` | `used` |
| `approval_time` |  |
| `reminder_cron_run` |  |
| `approval_hold_at` |  |
| `emp_fullname` | `used` |

---

> **List of unused parameters in the API (Pagination API) - `customer/purchaseRequestOrder/getWorkflowGRNPORecords`**
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `poi_id` |  |
| `pro_id` | `used` |
| `index` |  |
| `customer_id` | `used` |
| `cust_emp_id` | `used` |
| `vendor_id` | `used` |
| `vendor_emp_id` |  |
| `invoice_number` |  |
| `invoice_price` |  |
| `invoice_attachments` |  |
| `invoice_pdf` |  |
| `invoice_status` |  |
| `is_deleted` | `used` |
| `created_at` |  |
| `updated_at` |  |
| `invoice_date` |  |
| `grn_number` | `used` |
| `grn_date` | `used` |
| `grn_approval_pdf` | `used` |
| `grn_status` | `used` |
| `assignee_id` | `used` |
| `invoice_sgst` |  |
| `invoice_cgst` |  |
| `invoice_igst` |  |
| `invoice_gst` |  |
| `invoice_total` |  |
| `next_assignee_ids` |  |
| `is_auto_release` |  |
| `sap_grn_attchments` |  |
| `miro_number` |  |
| `sap_grn_number` |  |
| `collective_po_number` | `used` |
| `sap_po_number` | `used` |
| `po_status` | `used` |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `workflow_approval_id` | `used` |
| `remarks` | `used` |
| `approval_type` | `used` |
| `level_name` | `used` |
| `is_hold` | `used` |
| `is_return` | `used` |
| `is_unread` | `used` |
| `workflow_createor_date` | `used` |
| `approval_assigne_at` | `used` |
| `po_work_apprpval_date` |  |
| `comparision_report` |  |
| `workflow_history_records` | `used` |
| `is_delete` |  |
| `deleted_at` |  |
| `approved_at` |  |
| `emp_fullname` | `used` |
| `remarks_text` | `used` |
| `approval_time` |  |
| `approval_status` | `used` |
| `is_already_used` | `used` |
| `approval_hold_at` |  |
| `comparative_link` | `used` |
| `po_workflow_type` |  |

---

> **List of unused parameters in the API (Pagination API) - `customer/arcQuotation/getWorkflowRequestQuotationRecords`**
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `arc_rfq_id` | `used` |
| `arc_title` | `used` |
| `arc_number` |  |
| `arc_deadline` | `used` |
| `arc_status` | `used` |
| `is_deleted` |  |
| `vendors_id` | `used` |
| `collective_arc_number` | `used` |
| `arc_tendor_type` |  |
| `arc_type` | `used` |
| `arc_date` | `used` |
| `purchase_group_id` |  |
| `created_by` | `used` |
| `arc_type_code` |  |
| `arc_oc` |  |
| `arc_extend_status` |  |
| `negotiation_deadlinedate` | `used` |
| `is_show_negotiate` | `used` |
| `approval_assign_id` | `used` |
| `contract_name` | `used` |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `is_hold` |  |
| `is_return` | `used` |
| `is_unread` | `used` |
| `is_enquiry_important` | `used` |
| `workflow_approval_id` | `used` |
| `remarks` | `used` |
| `approval_type` | `used` |
| `level_name` | `used` |
| `workflow_createor_date` | `used` |
| `approval_assigne_at` |  |
| `rfq_work_apprpval_date` | `used` |
| `pr_number` | `used` |
| `materiallists` | `used` |
| `item` | `used` |
| `unit` | `used` |
| `pr_id` | `used` |
| `assets` |  |
| `pro_id` | `used` |
| `co_area` |  |
| `unit_id` |  |
| `category` |  |
| `plant_id` |  |
| `quantity` | `used` |
| `sap_item` |  |
| `item_note` |  |
| `item_text` |  |
| `order_qty` |  |
| `recipient` |  |
| `vendor_id` | `used` |
| `created_at` | `used` |
| `updated_at` | `used` |
| `attachments` | `used` |
| `g_l_account` |  |
| `material_id` |  |
| `total_price` |  |
| `wbs_element` |  |
| `distribution` |  |
| `funds_center` |  |
| `gr_proc_time` |  |
| `release_date` |  |
| `request_date` |  |
| `delivery_date` |  |
| `delivery_text` |  |
| `goods_receipt` |  |
| `initial_price` |  |
| `material_code` | `used` |
| `material_name` | `used` |
| `quantity_open` |  |
| `requisitioner` |  |
| `vendor_detail` |  |
|  |  |
| `process_status` |  |
| `service_detail` |  |
| `arc_category_id` |  |
| `arc_contract_id` | `used` |
| `invoice_receipt` |  |
| `tracking_number` |  |
| `uploading_point` |  |
| `assignment_order` |  |
| `item_category_id` |  |
| `material_po_text` |  |
| `pl_delivery_time` |  |
| `quantity_ordered` |  |
| `arc_category_name` | `used` |
| `material_group_id` |  |
| `material_revision` |  |
| `po_order_quantity` |  |
| `rfq_delivery_date` |  |
| `requisitioner_name` |  |
| `arc_sub_category_id` |  |
| `material_group_code` |  |
| `purchase_group_code` |  |
| `arc_sub_category_name` | `used` |
| `is_materil_po_created` |  |
| `purchase_organization` |  |
| `acc_assets_category_id` |  |
| `material_specification` | `used` |
| `arc_request_material_id` | `used` |
| `material_short_description` | `used` |
| `purchase_requisition_status` |  |
| `annual_tentative_requirement` |  |
| `total_queries` | `used` |
| `unread_queries` | `used` |
| `quotationlists` | `used` |
| `f_and_o` |  |
| `cust_emp_id` | `used` |
| `customer_id` | `used` |
| `f_and_o_dec` |  |
| `gst_remarks` |  |
| `vendor_code` | `used` |
| `vendor_name` | `used` |
| `total_amount` | `used` |
| `payment_terms` |  |
| `delivery_terms` |  |
| `quantity_terms` |  |
| `regret_remarks` |  |
| `vendor_remarks` |  |
| `reference_number` |  |
| `supplier_remarks` |  |
| `vendor_po_status` |  |
| `payment_terms_dec` | `used` |
| `delivery_terms_dec` | `used` |
| `contact_person_name` |  |
| `vendor_arc_document` |  |
| `arc_vendor_master_id` |  |
| `contact_person_email` |  |
| `contact_person_number` |  |
| `vendor_rfq_quotation_history` | `used` |
| `vendor_arc_quotation_document` | `used` |
| `comparision_report` |  |
| `comparitive_report` | `used` |
| `workflow_history_records` |  |
| `is_delete` |  |
| `deleted_at` |  |
| `approved_at` | `used` |
| `emp_fullname` | `used` |
| `remarks_text` |  |
| `approval_time` |  |
| `approval_status` | `used` |
| `is_already_used` |  |
| `approval_hold_at` |  |
| `comparative_link` | `used` |
| `reminder_cron_run` |  |
| `technical_attachments` |  |

---

> **List of unused parameters in the API (Pagination API) - `customer/arcContractOrder/getWorkflowPORecords`**
> 

| **Parametes** | **Used/Unused** |
| --- | --- |
| `arc_contract_id` | `used` |
| `po_deadline` | `used` |
| `po_status` | `used` |
| `sap_po_number` | `used` |
| `arc_tender_type` |  |
| `arc_contract_start_date` |  |
| `arc_contract_end_date` |  |
| `is_deleted` | `used` |
| `collective_arc_number` | `used` |
| `po_type_name` |  |
| `po_type_id` |  |
| `po_type_code` |  |
| `po_date` | `used` |
| `purchase_group_id` |  |
| `requisitioner_name` |  |
| `po_comparitive_link` |  |
| `po_comparitive_document_link` |  |
| `po_assignee_id` |  |
| `po_references` |  |
| `po_reference_type` |  |
| `vendor_id` |  |
| `po_created_at` |  |
| `header_text` |  |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `workflow_approval_id` | `used` |
| `remarks` | `used` |
| `approval_type` | `used` |
| `level_name` | `used` |
| `is_hold` |  |
| `is_return` |  |
| `is_unread` | `used` |
| `workflow_createor_date` | `used` |
| `approval_assigne_at` |  |
| `po_work_apprpval_date` |  |
| `updated_comparision_report` | `used` |
| `arc_rfq_details` | `used` |
| `arc_rfq_id` | `used` |
| `arc_status` |  |
| `comparision_report` |  |
| `workflow_history_records` |  |
| `is_delete` |  |
| `created_at` |  |
| `deleted_at` |  |
| `updated_at` |  |
| `approved_at` |  |
| `cust_emp_id` | `useed` |
| `customer_id` | `used` |
| `emp_fullname` |  |
| `remarks_text` |  |
| `approval_time` |  |
| `approval_status` | `used` |
| `is_already_used` |  |
| `approval_hold_at` |  |
| `comparative_link` | `used` |

---

> **List of unused parameters in the API (Pagination API) - `customer/dmsdocument/getDocumentWorkflowRelease`**
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `dms_id` | `used` |
| `customer_id` | `used` |
| `cust_emp_id` | `used` |
| `document_type_id` |  |
| `dms_number` | `used` |
| `dms_assignee_id` |  |
| `dms_status` | `used` |
| `is_deleted` | `used` |
| `created_at` | `used` |
| `updated_at` |  |
| `dms_document` | `used` |
| `release_remarks` | `used` |
| `ref_number` |  |
| `dms_date` |  |
| `dms_subject` | `used` |
| `dms_description` |  |
| `tender_ref` |  |
| `tender_notice_ref` |  |
| `dms_ref` |  |
| `delete_remarks` |  |
| `dept_id` | `used` |
| `next_assignee_ids` |  |
| `is_auto_release` |  |
| `auction_ref` |  |
| `document_name` | `used` |
| `document_code` |  |
| `drs_id` | `used` |
| `is_hold` | `used` |
| `is_return` | `used` |
| `is_unread` | `used` |
| `remarks` | `used` |
| `approval_type` | `used` |
| `level_name` | `used` |
| `workflow_createor_date` | `used` |
| `approval_assigne_at` | `used` |
| `rfq_work_apprpval_date` | `used` |
| `attachmentrecords` |  |
| `image_id` | `used` |
| `file_name` |  |
| `file_type` |  |
| `image_url` |  |
| `thumb_url` |  |
| `release_records` | `used` |
| `is_delete` |  |
| `deleted_at` |  |
| `approved_at` |  |
| `assignee_id` |  |
| `emp_fullname` | `used` |
| `remarks_text` | `used` |
| `approval_time` |  |
| `approval_status` | `used` |
| `is_already_used` | `used` |
| `strategy_status` | `used` |
| `approval_hold_at` |  |
| `comparative_link` |  |
| `workflow_history_records` | `used` |

---

> **List of unused parameters in the API (Pagination API) - `customer/dmsdocument/getDocumentWorkflowRelease`**
> 

| **Parameters** | **Used/Unused** |
| --- | --- |
| `dms_id` | `used` |
| `customer_id` | `used` |
| `cust_emp_id` | `used` |
| `document_type_id` |  |
| `dms_number` | `used` |
| `dms_assignee_id` |  |
| `dms_status` | `used` |
| `is_deleted` | `used` |
| `created_at` | `used` |
| `updated_at` |  |
| `dms_document` | `used` |
| `release_remarks` | `used` |
| `ref_number` |  |
| `dms_date` |  |
| `dms_subject` | `used` |
| `dms_description` |  |
| `tender_ref` |  |
| `tender_notice_ref` |  |
| `dms_ref` |  |
| `delete_remarks` |  |
| `dept_id` | `used` |
| `next_assignee_ids` |  |
| `is_auto_release` |  |
| `auction_ref` |  |
| `document_name` | `used` |
| `document_code` |  |
| `drs_id` | `used` |
| `is_hold` | `used` |
| `is_return` | `used` |
| `is_unread` | `used` |
| `remarks` | `used` |
| `approval_type` | `used` |
| `level_name` | `used` |
| `workflow_createor_date` | `used` |
| `approval_assigne_at` | `used` |
| `rfq_work_apprpval_date` | `used` |
| `attachmentrecords` | `used` |
| `image_id` | `used` |
| `file_name` |  |
| `file_type` |  |
| `image_url` |  |
| `thumb_url` |  |
| `release_records` | `used` |
| `is_delete` |  |
| `deleted_at` |  |
| `approved_at` |  |
| `assignee_id` |  |
| `emp_fullname` | `used` |
| `remarks_text` | `used` |
| `approval_time` |  |
| `approval_status` | `used` |
| `is_already_used` | `used` |
| `strategy_status` | `used` |
| `approval_hold_at` |  |
| `comparative_link` |  |
| `workflow_history_records` | `used` |

---

> **List of unused parameters in the API (Pagination API) - `customer/requests_master/getRequestWorkflowRelease`**
> 

| **Parameter** | **Used/Unused** |
| --- | --- |
| `request_id` | `used` |
| `customer_id` | `used` |
| `cust_emp_id` | `used` |
| `collective_request_no` | `used` |
| `request_form_id` |  |
| `request_form_fields` |  |
| `latitude` |  |
| `longitude` |  |
| `request_extra` |  |
| `max` |  |
| `min` |  |
| `selection_type` |  |
| `selection_view` |  |
| `field_selection` |  |
| `request_field` |  |
| `request_field_id` |  |
| `request_field_type` |  |
| `request_field_value` |  |
| `name` | `used` |
| `fileType` |  |
| `file_url` |  |
| `contentType` |  |
| `request_field_required` |  |
| `request_status` | `used` |
| `request_deleted` | `used` |
| `request_assignee_id` |  |
| `request_delete_reason` |  |
| `request_document` | `used` |
| `request_approval_document` | `used` |
| `created_at` | `used` |
| `updated_at` |  |
| `release_remarks` |  |
| `is_hold` | `used` |
| `is_return` | `used` |
| `is_unread` | `used` |
| `workflow_approval_id` | `used` |
| `remarks` | `used` |
| `approval_type` | `used` |
| `level_name` | `used` |
| `workflow_createor_date` | `used` |
| `approval_assigne_at` | `used` |
| `rfq_work_apprpval_date` | `used` |
| `release_records` | `used` |
| `is_edit` |  |
| `is_delete` |  |
| `is_already_used` | `used` |
| `strategy_status` | `used` |
| `approval_hold_at` |  |
| `comparative_link` |  |
| `workflow_history_records` | `used` |
| `is_edit` |  |
| `is_hold` | `used` |
| `remarks` | `used` |
| `is_delete` |  |
| `is_return` | `used` |
| `is_unread` | `used` |
| `created_at` | `used` |
| `deleted_at` |  |
| `level_name` | `used` |
| `request_id` | `used` |
| `updated_at` |  |
| `approved_at` |  |
| `assignee_id` |  |
| `emp_fullname` | `used` |
| `remarks_text` | `used` |
| `approval_time` |  |
| `approval_type` | `used` |
| `approval_status` | `used` |
| `is_already_used` | `used` |
| `strategy_status` | `used` |
| `approval_hold_at` |  |
| `comparative_link` |  |
| `approval_assigne_at` | `used` |
| `workflow_approval_id` | `used` |
| `workflow_history_records` | `used` |
| `is_edit` |  |
| `is_hold` | `used` |
| `remarks` | `used` |
| `is_delete` |  |
| `is_return` | `used` |
| `is_unread` | `used` |
| `created_at` | `used` |
| `deleted_at` |  |
| `level_name` | `used` |
| `request_id` | `used` |
| `updated_at` |  |
| `approved_at` |  |
| `assignee_id` |  |
| `emp_fullname` | `used` |
| `remarks_text` | `used` |
| `approval_time` |  |
| `approval_status` | `used` |
| `approval_hold_at` |  |
| `approval_assigne_at` | `used` |

---



> **List of unused parameters in the API (Pagination API) - `customer/purchaseRequestOrder/getWorkflowPORecords`**
> 


| **Parameters** | **Used/Unused** |
| --- | --- |
| `pro_id` | `used` |
| `po_deadline` | `used` |
| `po_status` | `used` |
| `is_deleted` | `used` |
| `sap_po_number` | `used` |
| `collective_po_number` | `used` |
| `po_type_name` |  |
| `po_type_id` |  |
| `po_type_code` |  |
| `po_date` | `used` |
| `purchase_group_id` |  |
| `requisitioner_name` |  |
| `po_comparitive_link` | `used` |
| `po_comparitive_document_link` |  |
| `po_assignee_id` |  |
| `po_references` |  |
| `po_reference_type` |  |
| `vendor_id` | `used` |
| `po_created_at` |  |
| `header_text` |  |
| `cust_emp_fname` | `used` |
| `cust_emp_lname` | `used` |
| `workflow_approval_id` | `used` |
| `is_hold` | `used` |
| `is_return` | `used` |
| `is_unread` | `used` |
| `approval_assigne_at` | `used` |
| `remarks` | `used` |
| `approval_type` | `used` |
| `level_name` | `used` |
| `workflow_createor_date` | `used` |
| `po_work_apprpval_date` |  |
| `pr_number` | `used` |
| `rfq_details` | `used` |
| `pr_rfq_id` | `used` |
| `rfq_status` |  |
| `collective_rfq_number` | `used` |
| `updated_comparision_report` | `used` |
| `arc_rfq_details` | `used` |
| `comparision_report` |  |
| `workflow_history_records` | `used` |
| `poi_id` | `used` |
| `pro_id` | `used` |
| `is_hold` | `used` |
| `remarks` | `used` |
| `is_delete` |  |
| `is_return` | `used` |
| `is_unread` | `used` |
| `created_at` |  |
| `deleted_at` |  |
| `level_name` | `used` |
| `updated_at` |  |
| `approved_at` |  |
| `cust_emp_id` | `used` |
| `customer_id` | `used` |
| `emp_fullname` | `used` |
| `approval_time` |  |
| `approval_type` | `used` |
| `approval_status` | `used` |
| `is_already_used` | `used` |
| `approval_hold_at` |  |
| `comparative_link` | `used` |
| `po_workflow_type` | `used` |
| `approval_assigne_at` | `used` |
| `workflow_approval_id` | `used` |


---

