```json
{
	"primary_key": "centre#9e99e9-e99ee-e9e9e9",
	"secondary_key": "region#939393-3993-33939",
	"centre_details": {
		"name": "centre_name",
		"address": "addres",
		"cname": "custom_website",
		"email": "email"
	}
}
```
```json
	"primary_key": "centre_adminstrator#939393-03993-09393",
	"secondary_key": "centre#9e99e9-e99ee-e9e9e9",
	"user_details": {
		"username": "user_name",
		"contact_information": {}
	},
	"forms": {
		"registration": {},
        "permission": {}
	}
```

```json
	"primary_key": "centre_adminstrator#939393-03993-09393",
	"secondary_key": "centre#9e99e9-e99ee-e9e9e9",
	"user_details": {
		"username": "user_name",
		"contact_information": {}
	},
	"forms": {
		"enrollment": {},
        "clothing": {}
	}
```

```json
{
	"primary_key": "entry#9e99e9-e99ee-e9e9e9",
	"secondary_key": "centre#9e99e9-e99ee-e9e9e9",
	"entry": {
		"entry_type": "registration",
		{
			"child_name": "",
			"id_number": ""
		}
	}
	}
```
* Event: new registration
	* Notification:
		* These are your details
		* This is the amount you owe
		* Bank details to pay

* Event: update payment information (payment received)
	* Form
		* Entry id
		* Payment made: amount
	* Event
		* Create account
		* Send notification. Payment received
			* Account details
			* Enrollment details (PDF)

```json
{
	"primary_key": "account#9e99e9-e99ee-e9e9e9",
	"secondary_key": "centre#9e99e9-e99ee-e9e9e9",
	"children": 
		{
			
		}
}
```

```json
{
	"primary_key": "entry#9e99e9-e99ee-e9e9e9",
	"secondary_key": "centre#9e99e9-e99ee-e9e9e9",
	"entry": {
		"entry_type": "clothing",
		{
			"child_id": "child#9e99e9-e99ee-e9e9e9"
			"child_name": "",
			"id_number": ""
		}
	}
  }
```
