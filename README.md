# ODRL-policies
sample policies for critical reflection of ODRL
A critical refelection on ODRL
---
Goal
The Open Digital Rights language [ODRL] is designed as a policy expression language aiming to provide a flexible and interoperable information model, vocabulary and encoding mechanism for representing normative statements. The goal of this work is to identify ODRL limitation to identify possible directions for extension. We do that by modelling data sharing usage policies in a distributed infrastructure.

- Delegation
  - Listing1: An agreement between companyX and CompanyY for transfer the ownership of the target dataset1 -
  - Listing2: CompanyX assigned CompanyY the ability to create new policies for third party use of the target datasetA with the grantuse action. It also assigns it a duty that has a specific policy for third party usage of the asset. The newPolicy states that the allowed third party permission is read for datasetA.
  - Listing3: This policy shows what  is possible with the nesting of the above policies, i.e grantUse and nextPolicy combination of use(as recommended by the ODRL group). It can enable us to form a hierarchical structure one step further than the above example
- Duty
  - Listing 4: CompanyX assigned CompanyY the duty to compensate the former 2000 euro
  - Listing 5: ComapanyX assigned companyY the usage right for datasetA with the precondition that an amount of 500 euro be paid. Here “duty” is used to represent the conditionality of the permission .  
- Lack of granularity
  - Listing 6:Company x is given the duty towards company y that company z performs a certain action  
- Transformational aspects
  - Listing 7:CompanyY lend companyX some money up to a certain time with a percent of the money borrowed to be paid. Here we couldn’t show that the incrementation of percentage to be paid every month.
- Policy conflict
  - Listing 8:CompanyX is prohibited to share datasetA outside of the EU. But companyX may share the data outside of the EU given the constraints that the purpose of sharing is emergency and the recipient has a cross border agreement with the EU.
