# OCCRP Azerbaidjani Laundromat dataset

Dataset from the OCCRP Azerbaijani laundromat story https://www.occrp.org/en/azerbaijanilaundromat/.

This is an enrichment from the raw data available on https://www.occrp.org/en/azerbaijanilaundromat/raw-data/ with the following modifications.

1. CSV Format
2. IDs are generated with the `occrp-az-laundromat-` prefix
3. IBAN validation APIs have been used to extract the bank name and swiftCode when possible
4. Extracted persons and companies from transaction data