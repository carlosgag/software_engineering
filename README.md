# Design of a Professionals Hiring System

Professional
- accounting
- country accounting
- birth date
- initial information collected date
- increment
- is_contract_prob_period_applies
- is_failed_to_launch
- is_fixed_term_emp_contract
- is_guaranteed_salary_increase
- is_sponsoring_visa
- is_offboardlead_unassigned
- is_thirteenth_month
- is_transfer
- security_questions_answered
- right_to_work_in_work_country
- is_visa_sponsorship_required
- is_sponsorship_visa_for_dependants_required
- job_category (it´s an entity, would have only one?)
- legacy_other_insurance_notes
paid_to_professional_in_month
po_number
pto_days_alotted
pto_days_carry_over
date_carryover_must_be_taken
is_days_carryover_indefinite
pto_notes
residency_status
salary_frequency
sponsoring_visa_expire_date
sponsoring_visa_notes
status
travel_insurance_cost_type
travel_insurance_notes
work_email
user_id
annual_base_salary_currency
client_id
client_country_id
funded_lsp_country_id
gp_offboard_lead_id
gp_onboard_lead_id
home_address_id
home_country_id
lsp_country_id
legacy_professional_medical_id
legacy_professional_other_insurance_id
legacy_professional_pension_id
professional_offboarding_id
professional_onboarding_id
work_address_id
lsp_professional_id
professional_in_country_transfer_id
roles
title
bus_phone
mobile_phone
first_name
last_name
legal_full_name
goes_by
is_no_longer_with_firm
is_enabled
forecast_start_date
forecast_end_date
service_class
personal_email
is_contract_end_date_manually_set
is_payroll_enrollment_form_completed
payroll_enrollment_form_completed_date
preferred_pronoun
is_country_specific_items_verified
is_sponsorship_visa_for_dependants
employment_contract_reject_count
is_override_bill_status_check


Remuneration
- remuneration type
- professional

Remuneration type
- Example:
-- annual base salary
-- client thirteenth month payment

Contract
- professional
- start date
- end date
- notes
- prob period end date

Deposit
- professional
- amount
- billed
- balance

Emergency
- professional
- email
- name
- phone

Expense
- professional
- frequency
- method

Job Category

Payroll
- professional
- other_notes
payroll_end_date
payroll_start_date
