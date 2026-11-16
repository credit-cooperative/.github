<div align="center">

<img src="https://avatars.githubusercontent.com/u/127978544?v=4" width="96" alt="Credit Cooperative logo" />

# Credit Cooperative

### Leverage future cash flows.

Onchain secured lending, built on escrowed revenue.

<br />

[![Website](https://img.shields.io/badge/Website-creditcoop.xyz-7B61FF?style=for-the-badge)](https://www.creditcoop.xyz)
[![App](https://img.shields.io/badge/App-app.creditcoop.xyz-7B61FF?style=for-the-badge)](https://app.creditcoop.xyz)
[![Docs](https://img.shields.io/badge/Docs-docs.creditcoop.xyz-7B61FF?style=for-the-badge)](https://docs.creditcoop.xyz)
[![Analytics](https://img.shields.io/badge/Analytics-app.creditcoop.xyz%2Fanalytics-7B61FF?style=for-the-badge)](https://app.creditcoop.xyz/analytics)
[![Blog](https://img.shields.io/badge/Blog-blog.creditcoop.xyz-7B61FF?style=for-the-badge)](https://blog.creditcoop.xyz)

[![X](https://img.shields.io/badge/X-%40creditcoop__xyz-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/creditcoop_xyz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Credit%20Coop-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/credit-coop)
[![Substack](https://img.shields.io/badge/Substack-creditcoop-FF6719?style=flat-square&logo=substack&logoColor=white)](https://creditcoop.substack.com/)
[![Email](https://img.shields.io/badge/Email-contact%40creditcoop.xyz-555555?style=flat-square&logo=gmail&logoColor=white)](mailto:contact@creditcoop.xyz)

</div>

<br />

## How it works

Credit Coop enables onchain secured lending by escrowing a borrower's **future** cash flows onchain.

| | |
|---|---|
| **Borrowers** | Businesses draw credit against their revenue, with future cash flows escrowed onchain to service the line. |
| **Lenders** | Fund those facilities directly, or through vaults. |
| **Onchain** | Lines, escrow and repayments live in public smart contracts, so activity is verifiable on the ledger. |

## Open source

| Repository | What it is | |
|---|---|---|
| [**Line-Of-Credit**](https://github.com/credit-cooperative/Line-Of-Credit) | v1 Line of Credit smart contracts (deployed) | ![Solidity](https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white) |
| [**v3-protocol-payment-rails**](https://github.com/credit-cooperative/v3-protocol-payment-rails) | Modular cross-chain token routing: a `PaymentRails` router plus pluggable action modules | ![Solidity](https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white) |

## Audits

Credit Coop contracts have been independently reviewed at every protocol generation.

| Date | Auditor | Scope | |
|---|---|---|---|
| Jul – Aug 2022 | [Halborn](https://www.halborn.com/) | v1 Line of Credit | [Report 🔒](https://github.com/credit-cooperative/security-and-audits/blob/master/audits/credit-coop-v1/halborn/2022-08-12_Halborn_P2P_Loan_Security_Audit_Report.pdf) |
| Nov 2022 | [Code4rena](https://code4rena.com/) | v1 Line of Credit (public contest) | [Report](https://github.com/code-423n4/2022-11-debtdao-findings/blob/main/report.md) |
| Jan 2023 | [Halborn](https://www.halborn.com/) | v1 migration contracts | [Report 🔒](https://github.com/credit-cooperative/security-and-audits/blob/master/audits/credit-coop-v1/halborn/2023-01-14_Halborn_Migration_Security_Audit_Report.pdf) |
| Mar – May 2024 | [Halborn](https://www.halborn.com/) | v2 Line of Credit and Vaults | [Report 🔒](https://github.com/credit-cooperative/security-and-audits/blob/master/audits/credit-coop-v2/halborn/2024-05-10_Halborn_Security_Review_Report.pdf) |
| Sep 2024 | [LightChaser](https://www.lightchaser.online/) | v2 Line of Credit and Vaults (automated) | [Report 🔒](https://github.com/credit-cooperative/security-and-audits/blob/master/audits/credit-coop-v2/lightchaser/2024-09-29_LightChaser_Automated_Review_Report.pdf) |
| Oct – Nov 2024 | [Enigma Dark](https://www.enigmadark.com/) | v2 Line of Credit and Vaults | [Report 🔒](https://github.com/credit-cooperative/security-and-audits/blob/master/audits/credit-coop-v2/enigma-dark/2024-10-30_Enigma_Dark_Security_Review_Report.pdf) |
| Nov – Dec 2024 | [Recon](https://getrecon.xyz/) | v2 Line of Credit and Vaults (invariant testing + review) | [Report 🔒](https://github.com/credit-cooperative/security-and-audits/blob/master/audits/credit-coop-v2/recon/credit-coop-invariants/2024-12-12_Recon_Security_Review_Report.pdf) |
| Dec 2024 – Jan 2025 | [Recon](https://getrecon.xyz/) | v2 Vaults (follow-up) | [Report 🔒](https://github.com/credit-cooperative/security-and-audits/blob/master/audits/credit-coop-v2/recon/credit-coop-invariants-2/2025-01-08_Recon_Security_Review_Report.pdf) |
| May 2026 | [Certora](https://www.certora.com/) | v3 Payment Rails modules | [Report 🔒](https://github.com/credit-cooperative/security-and-audits/blob/master/audits/credit-coop-v3/certora/2026-05-26_Certora_Payment_Rails_Modules_Final_Report.pdf) |
| Sep 2026 | [Certora](https://www.certora.com/) | v3 Payment Rails Atum module | [Report 🔒](https://github.com/credit-cooperative/security-and-audits/blob/master/audits/credit-coop-v3/certora/2026-09-14_Certora_Atum_Module_Final_Report.pdf) |

> 🔒 **Partner access.** Reports marked with a lock, along with the v2 source repositories, are kept in private repositories and are shared with partners — investors, lenders, borrowers and integrators — for due diligence. Without access, these links return a GitHub 404. To request access, email **[contact@creditcoop.xyz](mailto:contact@creditcoop.xyz)** with your GitHub username.
>
> Full index: [security-and-audits](https://github.com/credit-cooperative/security-and-audits) 🔒

## Security

Found a vulnerability? Please **do not open a public issue**.
Email **[security@creditcoop.xyz](mailto:security@creditcoop.xyz)** and see our [security policy](https://github.com/credit-cooperative/.github/blob/main/SECURITY.md).

<div align="center">
<sub>© Credit Cooperative</sub>
</div>
