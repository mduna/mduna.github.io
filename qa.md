---
layout: default
title: Question and Answer
---

## What data items are required by CMS for Provicer Directory
### Essential information
- **Provider Name**: Full legal name of the provider (individual or organization).   
- Provider Type: Type of healthcare professional (e.g., physician, nurse practitioner, therapist).
- **Specialties**: Medical and surgical specialties.   
- **Addresses**: Practice address, Mailing address (if different)
- Phone Numbers: Office phone number, Fax number (if available)
- Contact Information: Email address (if available), Website URL (if available)   
- Network Participation: In-network status for the specific plan, Any applicable restrictions (e.g., limited network)
- Languages Spoken: Languages spoken by the provider

### Additional Information (May vary by plan type)
- Accepting New Patients: Indication of whether the provider is accepting new patients.   
- Gender: Gender of the provider.
- Credentials: Medical degrees, Board certifications
- Hospital Affiliations: Hospitals where the provider has admitting privileges
- Accessibility: Information about accessibility features for patients with disabilities.   
- **Cultural and Linguistic Services (maybe required in 2026)**: Availability of interpreters or other language support services.
- **Specialties and Services offered (maybe required in 2026)**


### Important Notes
- Accuracy: The information in the provider directory must be accurate and up-to-date.   
- Accessibility: The directory must be easily accessible to enrollees and the public.   
- Searchability: The directory must be searchable by various criteria, such as provider name, specialty, location, and network status.

## [Provider Directory API CMS requirement](https://www.cms.gov/priorities/key-initiatives/burden-reduction/interoperability/frequently-asked-questions/provider-directory-api)
Medicare Advantage (MA) organizations, Medicaid state agencies, Medicaid managed care plans, Children’s Health Insurance Program (CHIP) state agencies and CHIP managed care entities are required to offer a public facing Provider Directory API which must include **data on a payer’s network of contracted providers**. 

## [NPPES Individual Provider Profile](https://nppes.cms.hhs.gov/webhelp/nppeshelp/INDIVIDUAL%20PROVIDER%20PROFILE%20PAGE.html#)
- Provide the provider’s full legal name. This name must match the name on file with the Social Security Administration (SSA). First and last names are required for initial applications.
1. Name
- Other Name (if Applicable)
- Prefix 
- First Name
- Middle Name
- Last Name
- Suffix

2. Credential(s)
3. Type of Other Name: Former Name, Professional Name, Other Name
4. Other Identifying information
- Date of Birth
- Social Security Number
- State of Birth
- Gender
5. Is the Provider a Sole Proprietor
6. Other Optional Infomration
- Ethnicity
- Race
- Language(s) spoken

## [NPPES Organization Provider Provider Profile](https://nppes.cms.hhs.gov/webhelp/nppeshelp/ORGANIZATIONAL%20PROVIDER%20PROFILE%20PAGE.html)
1. Employer Identification Number (EIN)
2. Organization Name (Legal Business Name)
3. Is the Organization a subpart
4. Is the parent EIN the same as subpart EIN
5. Parent Organization EIN
6. Parent Organization Legal Business Name (LBN)
7. Other Name
8. Type of Other Name (Doing Business As, Former Legal Business Name, Other Name)
9. Organizational Other Names Grid and Navigation Buttons
10. Authorized Official for the Organization
11. Orthorized Official Name and other details
- Prefix
- First Name
- Middle Name
- Last Name
- Suffix
- Credentials 
- Title/Position
- Telephone Number
12. Address
- Business Mailing Address
- Practice Location Address
13. Languages Spoken
14. Office hours
15. Accessibility

## [NPPES Health Information Exchange Page](https://nppes.cms.hhs.gov/webhelp/nppeshelp/HEALTH%20INFORMATION%20EXCHANGE.html)
Health Information Exchange (HIE) is the mobilization of health care information electronically across organizations within a region, community or hospital system. HIE provides 
the capability to electronically move clinical information among different health care information systems.

This information is collected in NPPES to facilitate the electronic exchange of health care information such as Medical records, order and referrals, etc., in a safe and secure fashion. 
Providers are encouraged to enter Endpoint information in NPPES to promote interoperability in health care, however, this information is not required to obtain an NPI. 
Providers can still obtain an NPI without providing such information.

1. Endpoint Type  
When entering an Endpoint, you are required to enter the Endpoint Type. Please select the Endpoint Type for the dropdown list. 
The dropdown list includes the following:
- Direct Messaging Address
- SOAP URL
- CONNECT URL
- FHIR URL
- RESTful URL
- Other URL

2. Endpoint 
When entering an Endpoint, you are required to enter the actual Endpoint in an accurate and appropriate format.

3. Endpoint Description  
When entering an Endpoint, you can enter a brief description of the Endpoint to help identify the Endpoint.

4. Endpoint Use 
When entering an Endpoint, you can enter how the Endpoint will be used.

5. Endpoint Content type
When entering an Endpoint, you can enter the Content Type which can identify the format of the data.

6. Is the Endpoint affiliated to another organization

7. Endpoint Location  
You can select the Endpoint Location from the list of addresses in the dropdown list, or select 
“Enter a new Endpoint Location”. The list of addresses in the dropdown box will consist of all Practice 
Location and Endpoint addresses associated with your NPI, as well as, the Practice Locations and 
Endpoint Locations associated with the Endpoint Affiliated Organization if one has been selected from NPPES.

If you select “Enter a new Endpoint Location” you can manually enter the Endpoint Location address. 
This new location information will go through address standardization check and you will 
have the option of choosing the standardized address or using the input address.

8. Affiliation Legal Bussiness Name when Endpoint is affiliated to another organization

9. Endpoint Affiliation Search 
- Search based on NPI, EIN, and/or Legal Business Name 

10. Endpoint Use Terms and conditions




## What is CMS MA Network Adquacy Requirements?
CMS has strict network adequacy requirements for Medicare Advantage (MA) plans, designed to ensure that enrollees have access to a sufficient number of providers and 
facilities to meet their healthcare needs. These requirements are outlined in the [Code of Federal Regulations (CFR) Title 42, Part 422.116.](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-B/part-422/subpart-C/section-422.116)

### Key Requirements:
- **Access to Covered Services:**  
MA plans must have an adequate network of providers to ensure access to covered services, including specialists and primary care physicians.   
- **Time and Distance Standards:**  
CMS sets maximum time and distance standards for enrollees to access providers, taking into account factors like rural areas and telehealth.   
- **Minimum Number of Providers:**  
MA plans must maintain a minimum number of providers in each specialty within a specific geographic area.   
- **Provider Quality and Participation:**  
CMS requires MA plans to ensure that providers in their network are qualified and actively participating in the plan.   
- **Network Adequacy Reviews:**  
CMS conducts regular network adequacy reviews to assess whether MA plans are meeting these requirements.   

### Additional Considerations for Specific Provider Types:

- **Behavioral Health Providers:**  
CMS has specific requirements for behavioral health providers, including Clinical Psychologists and Clinical Social Workers.   
- **Telehealth Providers:**  
MA plans can receive credit towards time and distance standards for providing telehealth services from certain provider types.  

### Resources
- [CMS Network Adequacy Guidance](https://www.cms.gov/medicare/health-drug-plans/network-adequacy)
- [42 CFR 422.116](//www.ecfr.gov/current/title-42/chapter-IV/subchapter-B/part-422)

## [The current MA and Section 1876 Cost Plan Provider Directory Model](https://www.cms.gov/files/document/cy2021-maandsection1876costplanproviderdirectorymodel7-08-2020.pdf)
**Regulatory Requirements**
CMS regulations at [42 CFR 422.111(b)(3)(i)](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-B/part-422/subpart-C/section-422.111) require organizations to provide the number, mix, and distribution (addresses) of providers from whom enrollees may reasonably be expected to obtain services. This information must be provided to each enrollee in a clear, accurate, and standardized form [(42 CFR 422.111(a)(2))](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-B/part-422/subpart-C/section-422.111). Regulations 
at [42 CFR 422.504(a)](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-B/part-422/subpart-K/section-422.504) and [422.504(a)(4)](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-B/part-422/subpart-K/section-422.504) require organizations to adhere to all regulations and general instructions and to 
disclose information to beneficiaries in the manner and the form prescribed by CMS as required under [42 CFR 422.111](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-B/part-422/subpart-C/section-422.111). In accordance with [42 CFR 422.111(h)(2)(ii)](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-B/part-422/subpart-C/section-422.111), each organization must post an online provider directory on its website. Section 1876 cost plan regulations at [42 CFR 417.427](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-B/part-417/subpart-K/section-417.427) require cost plans to adhere to the MA regulations at [42 CFR 422.111](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-B/part-422/subpart-C/section-422.111). In addition, 
section 1876 cost plans are required to comply with the applicable requirements and conditions 
set forth in this subpart and in general instructions issued by CMS [(42 CFR 417.472(b))](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-B/part-417/subpart-K/section-417.427)

**The rules of Provider Listings in the provider directory**

1. Plans must list **only currently contracted and credentialed providers** in their directory. Plans may not list a provider in their directory prior to being credentialed. 
2. Provider directories must clearly explain all plan-specific rules regarding enrollee access to providers. For example, a health maintenance organization (HMO) plan may have an open panel of providers or it may only offer a closed panel. A closed panel may require that enrollees obtain a referral from a Primary Care Provider (PCP) in order to access specialists. The plan must clearly explain this information in the directory. In addition, the directory must identify the providers and/or services for which an enrollee must obtain a referral, or the directory must explain to enrollees where they can find this information. 
3. Plans may not list a provider in their directory if the enrollee cannot call the phone number listed and request an appointment with that provider at the address listed (e.g., when the provider works only at a hospital/urgent care center and is not available for routine office visits).
4. Plans may not include providers in their directory that serve as on-call and substitute providers and who are not regularly available to provide covered services at an office or practice location. 
5. Plans may only list providers who regularly practice at the specified location. 
6. Plans must clearly state in the directory the capacity in which the provider is serving for that particular network even if the provider is credentialed in more than one specialty. For example, an internal medicine physician/oncologist that does not practice as a PCP should not be displayed 
as a PCP in the directory. The plan may only list the provider under the category of the services he/she will be furnishing to enrollees.
7. Plans may list non-physician practitioners (e.g., nurse practitioners, physician’s assistants) as “Primary Care Providers if an enrollee can make an appointment with that practitioner. The plan must clearly identify that the provider is a non-physician practitioner.
8. If a provider practices at multiple locations, the plan may only list the location(s) at which the provider regularly sees patients, and not every location where the provider may practice only occasionally.

**Regarding Accepting new patient**
1. Plans must either clearly identify whether or not a provider is accepting new patients or provide a notice directing beneficiaries to contact a provider to determine if he or she is accepting new patients. If listing the status for each individual provider, plans are not limited in the manner by which they identify providers who are/are not accepting new patients (i.e., “Accepting New Patients? Yes/No”), so long as beneficiaries can determine those providers from whom they may reasonably expect to obtain services (e.g., a special character next to the provider’s name and an accompanying footnote for all providers who are not accepting new patients).
2. Plans must make a reasonable attempt to ensure provider practice names are up-to-date and reflect the name of the practice used when an enrollee calls to make an appointment. 
3. Plans whose providers may have restrictions on access must include a notation next to the provider’s listing indicating such restrictions. Examples include, but are not limited to, the following:
- Providers who are only available to a subset of enrollees (e.g., only Native American enrollees may access a provider associated with a Native American tribe, only enrollees 
who are students may access the college’s student health service); 
- Providers who practice concierge medicine and are available only to patients who pay an annual fee or retainer;
- Providers who only offer home visits and do not see patients at a physical office location;
- Providers who regularly alternate between two or more different office locations;
- Providers who offer services exclusively via telehealth;
- Providers who will be available in-network as of a future, specified contract effective date (Plans must list this date next to the provider’s name); and
- Providers who will leave the network as of a specified contract termination date (Plans must list this date next to the provider’s name if the termination date is known/final).

**Sub-Networks**
If a plan offers sub-networks, it may develop a separate provider directory for each sub-network. Enrollees in a sub-network may be provided a directory reflecting their sub-network, 
but the directory also must clearly state that enrollees are not limited to the providers listed in the sub-network directory. The plan must provide a link where the enrollee can obtain 
a directory that includes the plan’s entire provider network. This larger directory may be made available online or furnished in hard copy upon request by the enrollee. In addition, the 
plan must describe how enrollees may request access to providers outside of the sub-network. For more information on sub-networks, please refer to the network adequacy 
guidance, [located at](https://www.cms.gov/medicare/health-drug-plans/medicare-advantage-application).

**Provider-Specific Plans**
A provider-specific plan (PSP) must develop a separate directorywhich clearly identifies available providers in the PSP network. A contract-level provider directory cannot be used for 
the purpose of communicating a PSP network to potential beneficiaries or enrollees. For example, a plan cannot simply add symbols or information to the broader network’s directory 
to show which providers are in the more limited PSP network.

**Different Cost Sharing Arrangements/Tiering.**  
Plans that reduce or eliminate cost sharing for enrollees that use certain providers (e.g., through the use of MA uniformity flexibilities), must identify these providers with special characters 
and/or footnotes.  

Plans that tier cost sharing of medical benefits for certain providers must use special characters and/or footnotes indicating there are different cost sharing amounts for those providers. 
Plans must include language referring enrollees to the Evidence of Coverage (EOC) for more information. Plans are not required to use the word “tier” if they use different terminology to describe 
these cost sharing arrangements.

**Best Practice to have the following elements in provider directory**
- Machine readable content
- Provider medical group
- Provider institutional affiliation
- Non-English languages spoken by provider
- Provider website address
- Accessibility for people with physical disabilitie

### What is in the provider directory?
#### Instroduction Section
Provide a list of plan' network providers. Describe how enrollees should use this directory. 

**Data Items for Provider Directory**

| Type | Name | Accepting New Patients? if applicable | address | Phone | website or e-mail address (optional) | for PCP support ePrescibing (optional) |
| ===== | ===== | ===== | ===== | ===== | ===== | ===== |
| PCP   | Yes   | Yes   | Yes   | Yes   | Yes   | Yes   |
| Specialist | Yes   | Yes   | Yes   | Yes   | Yes   | Yes   |
| Hospital   | Yes   | Yes   | Yes   | Yes   | Yes   | Yes   |
| SNFs  | Yes   | Yes   | Yes   | Yes   | Yes   | Yes   |
| Outpatient Mental Health Prviders | Yes   | Yes   | Yes   | Yes   | Yes   | Yes   |
| Pharmacies | Yes   | Yes   | Yes   | Yes   | Yes   | Yes   |


## What is CMS HSD?
CMS HSD typically refers to the Centers for Medicare & Medicaid Services (CMS) Health Services Delivery (HSD) requirements. These requirements are used to ensure that 
Medicare Advantage Organizations (MAOs) and other CMS-regulated plans have an adequate network of providers to deliver health services to their beneficiaries.

**Key Aspects of CMS HSD:**
1. Network Adequacy:  
CMS establishes specific criteria for network adequacy, including time and distance standards that providers must meet to ensure beneficiaries have reasonable access to care.

2. Provider Types:  
The HSD requirements often include a range of provider types, such as primary care physicians, specialists, hospitals, and other healthcare facilities.

3. Service Areas:
These requirements are evaluated based on the plan's service area, which can vary by geography (e.g., urban, rural).

4. Validation and Submission:  
Plans must submit their HSD tables to CMS to demonstrate compliance. These tables include information about the providers in the network, their specialties, locations, 
and the services they provide.

5. Monitoring and Compliance:  
CMS conducts periodic reviews to ensure compliance with HSD standards. Non-compliance can result in penalties or corrective actions.

6. Importance:  
HSD requirements aim to protect beneficiaries by ensuring that they have access to timely and appropriate care within their health plan's network.

**For example:**
[2025-hsd-reference-file-update-12032024](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fwww.cms.gov%2Ffiles%2Fdocument%2F2025-hsd-reference-file-updated-12032024.xlsx&wdOrigin=BROWSELINK)


## What is CMS PFFS?
CMS PFFS refers to the Centers for Medicare & Medicaid Services (CMS) Private Fee-for-Service (PFFS) plans. PFFS plans are a type of Medicare Advantage (Part C) plan offered 
by private insurance companies and approved by CMS. They provide Medicare benefits but operate differently from other Medicare Advantage plans like HMOs or PPOs.

### Key Features of CMS PFFS Plans:
1. Fee-for-Service Structure:  
In a PFFS plan, the insurance company determines how much it will pay doctors, hospitals, and other healthcare providers, as well as how much the enrollee must pay for services.

2. Provider Flexibility:  
- Enrollees can see any doctor or healthcare provider who accepts the plan's terms and agrees to treat them.
- Providers must agree to the plan's payment terms each time they deliver care.

3. No Network Restrictions:  
Unlike HMOs and PPOs, PFFS plans do not have a specific network of providers. However, not all providers may accept the plan’s payment terms.

4. Covered Services:
- PFFS plans must cover all Medicare Part A and Part B services.
- Many PFFS plans also include prescription drug coverage (Part D).

5. Cost-Sharing:  
Enrollees are responsible for co-payments, coinsurance, and deductibles as specified by the plan.

6. Regulatory Oversight:  
CMS regulates PFFS plans to ensure they meet Medicare Advantage requirements and provide sufficient access to care.


## What are in HHS CMS-4208-p RIN [0938-AV40 ](https://www.govinfo.gov/content/pkg/FR-2024-12-10/pdf/2024-27939.pdf)


### Codification of CBOs and Related Entities
1. **What Does Codifying Mean in This Context?**  
Codification involves formally including definitions and requirements in the federal regulations to ensure consistency and enforceability. For this rule, codifying ensures that entities such as CBOs, in-home benefit providers, and direct furnishing entities have clear, standardized definitions and requirements.

2. **Specific Codification Proposals**  
- Definition of CBOs:  
Codify what constitutes a Community-Based Organization (CBO) to provide clarity and consistency across MA plans. A CBO is proposed to be an entity deeply embedded in local communities, offering services tailored to community needs.
- In-Home and Hybrid Providers:  
Codify the distinction between in-home, at-home, and hybrid providers who offer both in-home and in-office services.
- Direct Furnishing Entities:  
Codify that all direct furnishing entities must be included in provider directories, ensuring transparency for beneficiaries.

3. **Directory Requirements and Codification**
- Directories must clearly identify:
  - Which providers are CBOs.  
  - Providers offering in-home or hybrid services.
- This ensures beneficiaries can easily find these organizations and make informed decisions about their care.

4. **Purpose of Codification**
- To create clear, enforceable standards for including CBOs and related entities in MA provider directories.
- To strengthen transparency, safety, and equity in how services are delivered to Medicare beneficiaries.

5. **Impact of Codifying These Definitions**
- Consistency: Ensures that all MA plans adhere to the same definitions and standards.
- Transparency: Makes it easier for beneficiaries to identify and access community-focused services.
- Safety and Trust: Enhances beneficiary trust by providing accurate, standardized information about providers, particularly those offering in-home services.

### Proposed Requirements for MA Provider Directory Sharing 

1. Submission to CMS:
- MA organizations are required to submit their provider directory data to CMS to populate the Medicare Plan Finder (MPF).
- This ensures beneficiaries have access to consistent, accurate, and comprehensive provider information when evaluating MA plans.

2. Accuracy and Consistency:
- MA organizations must attest that the provider directory data:
  - Is accurate.
  - Aligns with the data submitted for CMS’s network adequacy reviews.
- This alignment is critical to prevent discrepancies between directories and network adequacy data.

3. Key Data Elements to Be Added:
- Cultural and linguistic capabilities.
- Specialties and services offered.  
This information is particularly important for underserved communities and beneficiaries with specific needs.

4. Timeline for Implementation:
- The requirement to operationalize provider directories for testing purposes is proposed to begin in **Summer 2025**.
- Full implementation is required by **October 1, 2026**, for the contract year 2026.

5. Goal of the Requirement:
- To empower beneficiaries with accurate, transparent information when choosing MA plans.
- To enhance the usability and accessibility of online resources like the MPF.  

**Benefits of the Proposed Requirement**
- Informed Decision-Making:  
Beneficiaries can better evaluate coverage options with clear and detailed provider information.
- Transparency:  
Prevents misleading or inaccurate directory data that could result in poor beneficiary experiences.
- Equity:  
Improves access to information for underserved and diverse communities by including culturally relevant details.
