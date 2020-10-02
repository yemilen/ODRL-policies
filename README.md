# Sample ODRL-policies


---
The [Open Digital Rights language](https://www.w3.org/TR/odrl-model/) is designed as a policy expression language aiming to provide a flexible and interoperable information model, vocabulary and encoding mechanism for representing normative statements. This repository presents sample ODRL policies to test the capabilities of ODRL for our use-case.

- Delegation
  - Delegation1.json: An agreement between CompanyX and CompanyY for transfer the ownership of the target datasetA
  - Delegation2.json: CompanyX assigned CompanyY the ability to create new policies for third party use of the target datasetA with the grantuse action. It also assigns it a duty that has a specific policy for third party usage of the asset. The newPolicy states that the allowed third party permission is read for datasetA.
  - Delegation3.json: This policy shows what  is possible with the nesting of the above policies, i.e grantUse and nextPolicy combination of use(as recommended by the ODRL group). It can enable us to form a hierarchical structure one step further than the above example
- Duty
  - Duty1.json: CompanyX assigned CompanyY the duty to compensate the former 2000 euro
  - Duty2.json: ComapanyX assigned companyY the usage right for datasetA with the precondition that an amount of 500 euro be paid. Here “duty” is used to represent the conditionality of the permission .  
- Lack of granularity
  - partygranularity.json: CompanyX is given the duty towards companyY that companyZ performs a certain action  
- Transformational aspects
  - Transformational.json: CompanyY lend companyX some money up to a certain time with a percent of the money borrowed to be paid. Here we couldn’t show that the incrementation of percentage to be paid every month.
- Policy conflict
  - Conflict.json: CompanyX is prohibited to share datasetA outside of the EU. But companyX may share the data outside of the EU given the constraints that the purpose of sharing is emergency and the recipient has a cross border agreement with the EU.
