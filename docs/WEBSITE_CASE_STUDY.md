# Microsoft 365 IAM & Least-Privilege Access Control

**RiveraTechProtection | Hands-on cybersecurity / IT administration project**

## The challenge
How can an organization make sure employees have the access needed for their jobs—without giving everyone in the same department access to sensitive files?

## What I built
I configured a simulated Microsoft 365 tenant with three test identities, three SharePoint department resources (Finance, Human Resources and Payroll), and Microsoft Entra security groups. I assigned permissions based on business responsibilities, then verified them using permission audits and separate account sessions.

## Highlights
- **Finance:** Implemented read-only access to a fictional quarterly report and validated the restriction in Word for the web.
- **Employee transfer:** Revoked Shay's Finance permissions and provisioned HR Edit access; verified the old site denied access.
- **HR collaboration:** Validated two HR employee accounts could access the same revised onboarding document.
- **Payroll isolation:** Created a dedicated Payroll security group and private site; validated Payroll Specialist editing while an ordinary HR employee received Access Denied.

## Security principles
Least privilege · group-based authorization · department transfers · access revocation · sensitive-resource separation · positive and negative testing.

## Outcomes
**3 fictional employee identities · 3 SharePoint department resources · 3 Entra security groups · verified read/edit/denied outcomes.** All records are synthetic training data.

## Technology
Microsoft 365 Business Premium · Microsoft Entra ID · SharePoint Online · Microsoft 365 Admin Center · Word for the web.

## Suggested gallery captions
1. **Read-only Finance:** Shay's effective SharePoint permission was Read before transfer.
2. **Revocation after transfer:** Shay's Finance permission changed to None after removing obsolete group membership.
3. **Authorized HR collaboration:** Shay and Alex saw the same saved SOP revision.
4. **Restricted Payroll:** Taylor received Edit; Shay and Alex had None.
5. **Real-world negative test:** SharePoint denied Shay access to Payroll Operations.

## Call to action
[View full GitHub case study](INSERT_GITHUB_REPOSITORY_URL)
