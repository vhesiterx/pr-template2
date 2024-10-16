## Description
Sherpa Wizard Checklist

## Checklist
- [ ] **Database Consistency:** Check the consistency of the database across QA, Staging, and Production environments (e.g., trial_info_id, wizard_classifications, roles, components, groups).
- [ ] **Authorization Changes:** If authorization was added, update components, groups, roles in QA and staging environments. For production, create an ITOPS ticket.
- [ ] **New Condition ID:** Confirm condition ID is in Shorty studies table. If it is not present, update shorty table via DBA ahead of time.
- [ ] **Wizard Dependencies:** If this is a P1 wizard, verify if there’s a corresponding Patient Team wizard component.
