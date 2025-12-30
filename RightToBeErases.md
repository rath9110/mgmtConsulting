**Right to be erased - GDPR Article 17 

The core mission of Article 17 is to give individuals control over their digital footprint. As a Controller (the brand), you must delete data "without undue delay" if the user requests it.

1. When MUST you delete the data?
You have no choice but to erase if:

- You don't need the data for the original reason you collected it (e.g., the order was delivered 3 years ago and the account is closed).

- Consent for the data is revoked

- The user  exercise their Right to Object (Article 21) and you can't prove your "Legitimate Interest" is more important than their privacy.

- You never should have had the data in the first place.

- A specific EU law tells you that this data category must be wiped after X time.

2. When CAN the data be kept?
A delete request can be ignored if keeping the data is necessary for:

- Tax laws; Purchase history can't be deleted if Swedish/EU tax law requires you to keep financial records for 7+ years.

- The data is required to fight a legal claim or a lawsuit.

- There's a public interest in the data; specifically relevant in banking (fraud prevention) or medical sectors.

- If it's for journalism and public discourse it's protected.

***The "Propagation" Rule (Paragraph 2)
If the customer's data has been shared with third parties (like Google or Analytics tool), it is the job of the Controller to tell those third parties to also delete the data. Must often this is done through an /cleansing API endpoint call or similar to ensure the "links, copies, or replications" are wiped from the entire ecosystem.

The "Hard" vs. "Soft" Delete
Hard Delete: Wiping the PII (Name, Email, Phone) from the production DB.

Anonymization (Soft Delete): Removing the PII but keeping the "Order Value" and "Product SKU" for your Power BI dashboards. GDPR only cares about personal data. If it’s truly anonymous, you can keep the stats forever.