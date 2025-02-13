# CAPA Initiation Example: Service Authentication Outage

## 1. CAPA Identification
```markdown
CAPA-ID: 2024-02-13-001
Created Date: 2024-02-13
Due Date: 2024-04-13
Owner: Jane Smith
Department: Platform Services
```

## 2. Impact Statement
```markdown
On February 13, 2024, from 14:30 to 16:45 UTC, the authentication service experienced intermittent failures affecting approximately 150 users across three regions. Users were unable to log in to the system, resulting in business disruption and multiple customer escalations.

Impact Details:
- Environment: Production Authentication Service
- Duration: 2 hours 15 minutes
- Customer Impact: Users unable to access critical business applications
- Users Affected: 150 users across NA, EU, and APAC regions
```

## 3. Initial Assessment

### Severity Classification
- [x] Critical (S1) - Major service outage, significant customer impact
- [ ] Major (S2) - Service degradation, multiple customers affected
- [ ] Moderate (S3) - Limited impact, single customer affected
- [ ] Minor (S4) - No customer impact, internal issue only

### Impact Type
- [x] External Customer
- [x] Internal Customer
- [x] System/Process
- [ ] Compliance/Regulatory
- [ ] Security/Privacy

### Trigger Type
- [x] Incident
- [ ] Audit Finding
- [ ] Process Deviation
- [ ] Customer Feedback
- [ ] Learning Event

## 4. Related Information

### Reference Links
```markdown
- Incident Ticket: INC-2024-0213-001
- Change Ticket: CHG-2024-0213-001
- Customer Case: CS-2024-0213-001
- Monitoring Dashboard: https://monitoring.example.com/auth-service
```

### Stakeholders
```markdown
Primary Owner: Jane Smith / Platform Services Lead

Additional Stakeholders:
1. John Doe / Database Team Lead - Technical assessment
2. Sarah Johnson / Customer Success - Customer communication
3. Mike Wilson / Operations - Incident management
```

## 5. Initial Timeline

### Key Dates
```markdown
- Incident Date: 2024-02-13
- CAPA Creation: 2024-02-13
- Review Due: 2024-02-20
- Break Fix Due: 2024-02-27
- Action Items Due: 2024-04-13
```

## 6. Preliminary Scope

### Areas of Investigation
```markdown
1. Database Connection Management
   - What caused the connection pool exhaustion?
   - Are there monitoring gaps?
   - What capacity planning is in place?

2. Monitoring and Alerting
   - Why wasn't this detected earlier?
   - What alerts should be added?
   - How can we improve visibility?

3. Incident Response
   - How effective was our response?
   - Were procedures followed?
   - What improvements are needed?
```

### Known Information
```markdown
1. Current Understanding
   - Database connection pool exhaustion occurred
   - No alerts triggered until service failure
   - Manual intervention was required
   - Recent traffic growth may have contributed

2. Information Gaps
   - Root cause of pool exhaustion
   - Traffic patterns leading to incident
   - Current capacity limits
   - Historical trending data
```

## 7. Resource Requirements

### Team Resources
```markdown
Required Roles:
1. Database Engineer - 5 days
2. Platform Engineer - 3 days
3. Operations Engineer - 2 days
```

### Additional Resources
```markdown
Required Access/Tools:
1. Database monitoring tools
2. Performance analysis tools
3. Capacity planning tools
```

## Quality Checklist
- [x] All sections completed
- [x] Clear impact statement
- [x] Specific dates and times
- [x] Stakeholders identified
- [x] References included
- [x] Timeline defined
- [x] Resources identified

## Next Steps
1. Begin investigation phase
2. Schedule technical review
3. Gather monitoring data
4. Interview stakeholders

## Notes
```markdown
Initial assessment suggests this is a critical incident requiring immediate attention and thorough investigation. Focus areas include capacity management, monitoring improvements, and incident response procedures.
