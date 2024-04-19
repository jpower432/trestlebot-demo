---
x-trestle-comp-def-rules:
  My Comp:
    - name: rule-ac-2.2
      description: Rule for ac-2.2
x-trestle-param-values:
  ac-02.02_odp.01:
  ac-02.02_odp.02:
x-trestle-global:
  profile:
    title: Example
    href: trestle://profiles/example/profile.json
  sort-id: ac-02.02
---

# ac-2.2 - \[Access Control\] Automated Temporary and Emergency Account Management

## Control Statement

Automatically {{ insert: param, ac-02.02_odp.01 }} temporary and emergency accounts after {{ insert: param, ac-02.02_odp.02 }}.

## Control Assessment Objective

temporary and emergency accounts are automatically {{ insert: param, ac-02.02_odp.01 }} after {{ insert: param, ac-02.02_odp.02 }}.

## Control guidance

Management of temporary and emergency accounts includes the removal or disabling of such accounts automatically after a predefined time period rather than at the convenience of the system administrator. Automatic removal or disabling of accounts provides a more consistent implementation.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

My implementation for ac-2.2 with additional information with even more information.

### Rules:

  - rule-ac-2.2

### Implementation Status: partial

______________________________________________________________________
