## init
* init
  - utter_init
## greetings + goodbye
* greet
  - utter_greet
* goodbye
  - utter_goodbye

## happy path 1
* calculate_aggregate{"degree":"bs"}
  - utter_calculate_aggregate_BS
* programs_info{"degree":"bs","bs_program":"cs"}
  - utter_programs_bs_cs
* procedure_to_apply{"degree":"bs"}
  - utter_procedure_to_apply_for_BS_and_MSc
* merit_formula{"degree":"bs"}
  - utter_merit_formula_for_BS
* fee_structure{"degree":"bs"}
  - utter_fee_structure_for_BS
* eligibility_criteria{"degree":"bs"}
  - utter_eligibility_criteria_BS
* priciple_list{"degree":"bs","bs_program":"cs"}
  - utter_priciple_list_bs_cs
* vc_list{"degree":"bs","bs_program":"cs"}
  - utter_vc_list_bs_cs
* calender
  - utter_calender
* time_table
  - utter_time_table

## happy path 2
* calculate_aggregate{"degree":"bs"}
  - utter_calculate_aggregate_BS
* programs_info{"degree":"bs","bs_program":"it"}
  - utter_programs_bs_it
* procedure_to_apply{"degree":"bs"}
  - utter_procedure_to_apply_for_BS_and_MSc
* merit_formula{"degree":"bs"}
  - utter_merit_formula_for_BS
* fee_structure{"degree":"bs"}
  - utter_fee_structure_for_BS
* eligibility_criteria{"degree":"bs"}
  - utter_eligibility_criteria_BS
* priciple_list{"degree":"bs","bs_program":"it"}
  - utter_priciple_list_bs_it
* vc_list{"degree":"bs","bs_program":"it"}
  - utter_vc_list_bs_it
* calender
  - utter_calender
* time_table
  - utter_time_table

## happy path 3
* calculate_aggregate{"degree":"bs"}
  - utter_calculate_aggregate_BS
* programs_info{"degree":"bs","bs_program":"se"}
  - utter_programs_bs_se
* procedure_to_apply{"degree":"bs"}
  - utter_procedure_to_apply_for_BS_and_MSc
* merit_formula{"degree":"bs"}
  - utter_merit_formula_for_BS
* fee_structure{"degree":"bs"}
  - utter_fee_structure_for_BS
* eligibility_criteria{"degree":"bs"}
  - utter_eligibility_criteria_BS
* priciple_list{"degree":"bs","bs_program":"se"}
  - utter_priciple_list_bs_se
* vc_list{"degree":"bs","bs_program":"se"}
  - utter_vc_list_bs_se
* calender
  - utter_calender
* time_table
  - utter_time_table



## calculate aggregate bs  
* calculate_aggregate
  - utter_ask_degree
* choose_degree{"degree":"bs"}
  - slot{"degree":"bs"}
  - utter_calculate_aggregate_BS


## calculate aggregate msc  
* calculate_aggregate
  - utter_ask_degree
* choose_degree{"degree":"msc"}
  - slot{"degree":"msc"}
  - utter_calculate_aggregate_MSc

## programs info cs
* programs_info{"bs_program":"null"}
  - utter_ask_bs_program
* choose_bs_program{"bs_program":"cs"}
  - slot{"degree":"bs","bs_program":"cs"}
  - utter_programs_bs_cs


## programs info it
* programs_info{"bs_program":"null"}
  - utter_ask_bs_program
* choose_bs_program{"bs_program":"it"}
  - slot{"degree":"bs","bs_program":"it"}
  - utter_programs_bs_it

## programs info se
* programs_info{"bs_program":"null"}
  - utter_ask_bs_program
* choose_bs_program{"bs_program":"se"}
  - slot{"degree":"bs","bs_program":"se"}
  - utter_programs_bs_se


## programs info msc
* programs_info
  - utter_ask_degree
* choose_degree{"degree":"msc"}
  - slot{"degree":"msc"}
  - utter_programs_msc_cs

## programs info Mphill
* programs_info
  - utter_ask_degree
* choose_degree{"degree":"mphill"}
  - slot{"degree":"mphill"}
  - utter_programs_mphill_cs

## programs info PhD
* programs_info
  - utter_ask_degree
* choose_degree{"degree":"phd"}
  - slot{"degree":"phd"}
  - utter_programs_PHD

## procedure to apply Bs and MSc
* procedure_to_apply
  - utter_ask_degree
* choose_degree{"degree":"bs"}
  - slot{"degree":"bs"}
  - utter_procedure_to_apply_for_BS_and_MSc

## procedure to apply Bs and MSc
* procedure_to_apply
  - utter_ask_degree
* choose_degree{"degree":"msc"}
  - slot{"degree":"msc"}
  - utter_procedure_to_apply_for_BS_and_MSc  

## procedure to apply mphill
* procedure_to_apply
  - utter_ask_degree
* choose_degree{"degree":"mphill"}
  - slot{"degree":"mphill"}
  - utter_procedure_to_apply_for_MPhill  

## procedure to apply PhD
* procedure_to_apply
  - utter_ask_degree
* choose_degree{"degree":"phd"}
  - slot{"degree":"phd"}
  - utter_procedure_to_apply_for_PHD 


## merit formula bs
* merit_formula
  - utter_ask_degree
* choose_degree{"degree":"bs"}
  - slot{"degree":"bs"}
  - utter_merit_formula_for_BS

## merit formula msc
* merit_formula
  - utter_ask_degree
* choose_degree{"degree":"msc"}
  - utter_merit_formula_for_MSc

## merit formula mphill
* merit_formula
  - utter_ask_degree
* choose_degree{"degree":"mphill"}
  - slot{"degree":"mphill"}
  - utter_merit_formula_for_MPhill

## merit formula phd
* merit_formula
  - utter_ask_degree
* choose_degree{"degree":"phd"}
  - slot{"degree":"phd"}
  - utter_merit_formula_for_PhD

## eligibility criteria bs
* eligibility_criteria
  - utter_ask_degree
* choose_degree{"degree":"bs"}
  - slot{"degree":"bs"}
  - utter_eligibility_criteria_BS

## eligibility criteria msc
* eligibility_criteria
  - utter_ask_degree
* choose_degree{"degree":"msc"}
  - utter_eligibility_criteria_MSc

## eligibility criteria mphill
* eligibility_criteria
  - utter_ask_degree
* choose_degree{"degree":"mphill"}
  - slot{"degree":"mphill"}
  - utter_eligibility_criteria_MPhill  

## eligibility criteria phd
* eligibility_criteria
  - utter_ask_degree
* choose_degree{"degree":"phd"}
  - slot{"degree":"phd"}
  - utter_eligibility_criteria_PhD

## fee structure bs
* fee_structure
  - utter_ask_degree
* choose_degree{"degree":"bs"}
  - slot{"degree":"bs"}
  - utter_fee_structure_for_BS

## fee structure msc
* fee_structure
  - utter_ask_degree
* choose_degree{"degree":"msc"}
  - utter_fee_structure_for_MSC

## fee structure mphill
* fee_structure
  - utter_ask_degree
* choose_degree{"degree":"mphill"}
  - slot{"degree":"mphill"}
  - utter_fee_structure_for_Mphill

## fee structure phd
* fee_structure
  - utter_ask_degree
* choose_degree{"degree":"phd"}
  - slot{"degree":"phd"}
  - utter_fee_structure_for_PhD 


## priciple list bs-it
* priciple_list{"bs_program":"null"}
  - utter_ask_bs_program
* choose_bs_program{"bs_program":"it"}
  - slot{"degree":"bs","bs_program":"it"}
  - utter_priciple_list_bs_it

## priciple list bs-se
* priciple_list{"bs_program":"null"}
  - utter_ask_bs_program
* choose_bs_program{"bs_program":"se"}
  - slot{"degree":"bs","bs_program":"se"}
  - utter_priciple_list_bs_se

## priciple list bs-cs
* priciple_list{"bs_program":"null"}
  - utter_ask_bs_program
* choose_bs_program{"bs_program":"cs"}
  - slot{"degree":"bs","bs_program":"cs"}
  - utter_priciple_list_bs_cs  


## priciple list ms-cs
* priciple_list
  - utter_ask_degree
* choose_degree{"degree":"msc"}
  - slot{"degree":"msc"}
  - utter_priciple_list_ms_cs
  
## vc list bs-it
* vc_list{"bs_program":"null"}
  - utter_ask_bs_program
* choose_bs_program{"bs_program":"it"}
  - slot{"degree":"bs","bs_program":"it"}
  - utter_vc_list_bs_it
  
## vc list bs-cs
* vc_list{"bs_program":"null"}
  - utter_ask_bs_program
* choose_bs_program{"bs_program":"cs"}
  - slot{"degree":"bs","bs_program":"cs"}
  - utter_vc_list_bs_cs
  
## vc list bs-se
* vc_list{"bs_program":"null"}
  - utter_ask_bs_program
* choose_bs_program{"bs_program":"se"}
  - slot{"degree":"bs","bs_program":"se"}
  - utter_vc_list_bs_se
  
## vc list msc
* vc_list
  - utter_ask_degree
* choose_degree{"degree":"msc"}
  - slot{"degree":"msc"}
  - utter_vc_list_ms_cs


## calculate aggregate bs  
* calculate_aggregate{"degree":"bs"}
  - utter_calculate_aggregate_BS

## calculate aggregate msc  
* calculate_aggregate{"degree":"msc"}
  - utter_calculate_aggregate_MSc  

## programs info cs
* programs_info{"degree":"bs","bs_program":"cs"}
  - utter_programs_bs_cs

## programs info se
* programs_info{"degree":"bs","bs_program":"se"}
  - utter_programs_bs_se

## programs info it
* programs_info{"degree":"bs","bs_program":"it"}
  - utter_programs_bs_it  

## programs info msc
* programs_info{"degree":"msc"}
  - utter_programs_msc_cs

## programs info Mphill
* programs_info{"degree":"mphill"}
  - utter_programs_mphill_cs

## programs info PhD
* programs_info{"degree":"phd"}
  - utter_programs_PHD

## procedure to apply Bs and MSc
* procedure_to_apply{"degree":"bs"}
  - utter_procedure_to_apply_for_BS_and_MSc

## procedure to apply Bs and MSc
* procedure_to_apply{"degree":"msc"}
  - utter_procedure_to_apply_for_BS_and_MSc  

## procedure to apply mphill
* procedure_to_apply{"degree":"mphill"}
  - utter_procedure_to_apply_for_MPhill  

## procedure to apply PhD
* procedure_to_apply{"degree":"phd"}
  - utter_procedure_to_apply_for_PHD  

## merit formula bs
* merit_formula{"degree":"bs"}
  - utter_merit_formula_for_BS

## merit formula msc
* merit_formula{"degree":"msc"}
  - utter_merit_formula_for_MSc

## merit formula mphill
* merit_formula{"degree":"mphill"}
  - utter_merit_formula_for_MPhill

## merit formula phd
* merit_formula{"degree":"phd"}
  - utter_merit_formula_for_PhD

## eligibility criteria bs
* eligibility_criteria{"degree":"bs"}
  - utter_eligibility_criteria_BS

## eligibility criteria msc
* eligibility_criteria{"degree":"msc"}
  - utter_eligibility_criteria_MSc

## eligibility criteria mphill
* eligibility_criteria{"degree":"mphill"}
  - utter_eligibility_criteria_MPhill  

## eligibility criteria phd
* eligibility_criteria{"degree":"phd"}
  - utter_eligibility_criteria_PhD

## fee structure bs
* fee_structure{"degree":"bs"}
  - utter_fee_structure_for_BS

## fee structure msc
* fee_structure{"degree":"msc"}
  - utter_fee_structure_for_MSC

## fee structure mphill
* fee_structure{"degree":"mphill"}
  - utter_fee_structure_for_Mphill

## fee structure phd
* fee_structure{"degree":"phd"}
  - utter_fee_structure_for_PhD 

## priciple list bs-it
* priciple_list{"degree":"bs","bs_program":"it"}
  - utter_priciple_list_bs_it

## priciple list bs-se
* priciple_list{"degree":"bs","bs_program":"se"}
  - utter_priciple_list_bs_se

## priciple list bs-cs
* priciple_list{"degree":"bs","bs_program":"cs"}
  - utter_priciple_list_bs_cs  


## priciple list ms-cs
* priciple_list{"degree":"msc"}
  - utter_priciple_list_ms_cs
  
## vc list bs-it
* vc_list{"degree":"bs","bs_program":"it"}
  - utter_vc_list_bs_it
  
## vc list bs-cs
* vc_list{"degree":"bs","bs_program":"cs"}
  - utter_vc_list_bs_cs
  
## vc list bs-se
* vc_list{"degree":"bs","bs_program":"se"}
  - utter_vc_list_bs_se
  
## vc list msc
* vc_list{"degree":"msc"}
  - utter_vc_list_ms_cs
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        