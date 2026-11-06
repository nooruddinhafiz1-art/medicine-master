# medicine-master

Shared list of Indian medicine names (about 2.58 lakh: Rx + OTC/supplements) used by UltraAccounting medical software (ASMA Medical and future shop apps).

- `master.txt.gz` – gzip text. Sections `#C` companies, `#S` compositions, `#M` medicines (`name<TAB>companyIndex<TAB>saltIndex<TAB>pack<TAB>packLabel`).
- `version.txt` – bump this number every time `master.txt.gz` changes. Apps re-download only when it changes.

Contains only medicine names and public product data. No customer or patient data.
