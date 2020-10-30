--- 

title: WMS Standard APIs 

language_tabs: 
   - shell 

toc_footers: 
   - <a href='#'>Sign Up for a Developer Key</a> 
   - <a href='https://github.com/lavkumarv'>Documentation Powered by lav</a> 

includes: 
   - errors 

search: true 

--- 

# Introduction 

This is a sample Spring Boot RESTful service using springdoc-openapi and OpenAPI 3. 

# /API/V1/DC/ASN
## ***GET*** 

**Summary:** Retrieve ASN.

### HTTP Request 
`***GET*** /api/v1/dc/asn` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wh_id | query |  | Yes |  |
| shipment_number | query |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Merge ASN. Update the ASN if existed, otherwise create a new one.

### HTTP Request 
`***PUT*** /api/v1/dc/asn` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |

## ***POST*** 

**Summary:** Create ASN.

### HTTP Request 
`***POST*** /api/v1/dc/asn` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Delete ASN.

### HTTP Request 
`***DELETE*** /api/v1/dc/asn` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wh_id | query |  | Yes |  |
| shipment_number | query |  | Yes |  |
| client_code | query |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PATCH*** 

**Summary:** Update ASN.

### HTTP Request 
`***PATCH*** /api/v1/dc/asn` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /API/V1/DC/ASN/REPLACE
## ***PUT*** 

**Summary:** Replace ASN. Create a new ASN after delete the old one.

### HTTP Request 
`***PUT*** /api/v1/dc/asn/replace` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /API/V1/OUTBOUND/ACK
## ***GET*** 

### HTTP Request 
`***GET*** /api/v1/outbound/ack` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***POST*** 

### HTTP Request 
`***POST*** /api/v1/outbound/ack` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

<!-- Converted with the swagger-to-slate https://github.com/lavkumarv/swagger-to-slate -->
