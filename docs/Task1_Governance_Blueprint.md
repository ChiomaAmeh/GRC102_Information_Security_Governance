# Task 1: Governance Blueprint

## 1.1 Current-State Governance Gap Assessment

GHC's security arrangements have not kept pace with its growth. Two acquisitions were folded in without anyone reconciling the security practices that came with them, and the recent data-leakage near-miss suggests the organisation got lucky rather than being well defended.

### Security sits inside IT rather than standing apart from it

John Smith runs infrastructure and, on top of that, handles security more or less by default. Whenever the two jobs compete, uptime tends to win, and security controls get quietly deferred.

### Compliance and security aren't talking to each other

Mark Johnson's compliance work is focused on healthcare regulatory obligations, but nothing connects that work to the security decisions being made day to day.

### Two acquisitions, no harmonised security posture

Each acquired company almost certainly arrived with its own tools, habits and policies, none of which appear to have been reconciled with GHC's own.

### Onboarding and offboarding aren't linked to access control

Robert Green's HR team owns onboarding and offboarding, but there's no indication that the process is tied to when accounts actually get created or switched off.

### No one has to answer for security at Board level

There is no defined channel through which Sarah Chen or David Miller receive regular and meaningful security reporting.

---

## 1.2 Proposed Security Governance Organisational Chart

```text
Board of Directors (David Miller)
│
├── Board Risk & Audit Committee
│
└── CEO (Sarah Chen)
     │
     └── Director, Information Security Governance
          │
          ├── Security Steering Committee
          ├── IT Manager (John Smith)
          ├── CTO (Elena Rodriguez)
          ├── Compliance Officer (Mark Johnson)
          ├── HR Manager (Robert Green)
          ├── Senior Developer (Jane Doe)
          └── Finance/Data Representative (Emily White)

Internal Audit
│
└── Reports Independently to the Board Risk & Audit Committee
```

---
 
## 1.3 RACI Matrix

| Activity | Board | CEO | Director ISG | IT Manager | CTO | Compliance | HR |
|-----------|---------|---------|---------|---------|---------|---------|---------|
| Policy Approval | A | R | R | C | C | C | I |
| Risk Assessment | I | I | A | C | C | C | I |
| Incident Response | I | I | A | R | C | C | I |
| Compliance Tracking | I | I | C | I | I | A | I |
| Security Awareness Training | I | I | A | I | I | C | R |
| Access Provisioning | I | I | A | R | I | I | R |
| Vendor Due Diligence | I | I | A | C | R | C | I |

 
Legend:

- R = Responsible
- A = Accountable
- C = Consulted
- I = Informed
 
---

## 1.4 Governance Structure Justification

Accountability improves because every activity now has a clearly identified owner.

Transparency improves because Internal Audit reports independently to the Board Risk and Audit Committee.

Business alignment improves by bringing IT, Compliance, HR, Development, and Finance into governance discussions through the Security Steering Committee.

Risk management improves because critical activities such as vendor due diligence, incident response, and access management receive formal ownership and oversight.

``
