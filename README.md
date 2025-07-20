# Week7-Celebal
# Azure Data Factory Assignment: Truncate Load Daily Pipeline

#What’s Implemented

- Pipeline: TruncateLoadDailyPipeline
- Data Flow: Load_CUST_MSTR_Flow
- Datasets: CUST_MSTR, master_child, H_ECOM_Orders
- Derived Column logic for `load_date`, `date`, and `dateKey`
- Sink mappings configured properly
- Daily trigger setup
- Debug run and successful execution verified

#How to Deploy

1. Go to Azure Data Factory → Manage → ARM Template
2. Click "Import ARM Template"
3. Upload `ARMTemplateForFactory.json` and `ARMTemplateParametersForFactory.json`
4. Publish the factory

