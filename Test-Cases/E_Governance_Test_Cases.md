# E-Governance Test Cases

| Test ID | Module | Test Type | Scenario | Expected Result | Status |
|---|---|---|---|---|---|
| UT-001 | Citizen Registration | Unit Testing | Register citizen with valid data | Citizen registered successfully | PASS |
| UT-002 | Application Management | Unit Testing | Create application with valid details | Application created | PASS |
| UT-003 | Document Verification | Unit Testing | Verify valid document | Document verified | PASS |
| UT-004 | Certificate Generation | Unit Testing | Generate certificate for verified application | Certificate generated | PASS |
| VT-001 | Citizen Registration | Validation Testing | Citizen name is blank | Validation error displayed | PASS |
| VT-002 | Citizen Registration | Validation Testing | Invalid mobile number | Invalid mobile rejected | PASS |
| VT-003 | Application Management | Validation Testing | Invalid Application ID | Application not found | PASS |
| VT-004 | Document Verification | Negative Testing | Application submitted without document | Incomplete application rejected | PASS |
| NT-001 | Application Management | Negative Testing | Application ID does not exist | Application not processed | PASS |
| IT-001 | Application + Document | Integration Testing | Application sent for document verification | Application available for verification | PASS |
| IT-002 | Document + Certificate | Integration Testing | Verified document used for certificate generation | Certificate generated | PASS |
| IT-003 | Application + Reporting | Integration Testing | Saved application included in report | Application appears in report | PASS |
| PT-001 | Performance Testing | Performance Assessment | Repeated processing workload | Efficient processing | PASS |
