---
x-trestle-comp-def-rules:
  Inactivity Logout:
    - name: rule-ac-2.5
      description: Rule for ac-2.5
x-trestle-param-values:
  ac-02.05_odp:
x-trestle-global:
  profile:
    title: Example Using NIST SP 800-53 Rev 5 Controls and SP 800-53A Rev 5 Assessment
      Procedures
    href: trestle://profiles/oscal_to_bash_example/profile.json
  sort-id: ac-02.05
---

# ac-2.5 - \[Access Control\] Inactivity Logout

## Control Statement

Require that users log out when {{ insert: param, ac-02.05_odp }}.

## Control Assessment Objective

users are required to log out when {{ insert: param, ac-02.05_odp }}.

## Control guidance

Inactivity logout is behavior- or policy-based and requires users to take physical action to log out when they are expecting inactivity longer than the defined period. Automatic enforcement of inactivity logout is addressed by [AC-11](#ac-11).

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ac-2.5 -->

### Rules:

  - rule-ac-2.5

### Implementation Status: planned

______________________________________________________________________
