GitSchool_Internal
breastfeeding husband_away fatalistic respondent_opposed partner_opposed others_opposed religion /// 
no_knowledge no_source_known side_effects health no_access cost preferred_unavailable /// 
no_method_available inconvenient interferes_with_body other dontknow noresponse{ 
gen wn`var'=0 if why_not_using!=""  
forval y=1/`x' { 
gen wn`var'=0 if why_not_using!="" & why_not_using!=96
label values wn`var' yes_no_dnk_nr_list 