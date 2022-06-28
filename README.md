# e-commerce-website

Create an e-commerce web application. Integrate the shopping cart with the Bambora Payment gateway APIs (refer https://dev.na.bambora.com/docs/references/payment_APIs).

Use custom checkout javascript library (refer to https://dev.na.bambora.com/docs/guides/custom_checkout) to generate the single-use token, which shall further be used to perform the following operations:
Generate a Payment Profile (POST to v1/Profile endpoint)
Process a charge against a card (POST to v1/Payments endpoint)

If you are processing the charge against the card as the first step, a Payment profile can be generated using the TransactionID from the Approved transaction.
