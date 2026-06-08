# n8n Lead Generator

A simple lead generation workflow built using n8n.

## What it does

* Takes a business category and location as input
* Fetches business data using Apify
* Filters businesses with available email addresses
* Creates a CSV file
* Sends the CSV file through Gmail

## Tools Used

* n8n
* Apify
* Gmail

## Workflow

1. Submit location and business category
2. Fetch business data
3. Filter entries with emails
4. Generate CSV file
5. Send results via email

## Example Output

The generated file may contain:

* Business Name
* Email
* Phone Number
* Website
* Address

## Screenshot

Add your workflow screenshot here.

## Learning

This project helped me understand:

* APIs
* Workflow automation
* Data filtering
* File generation
* Email automation
