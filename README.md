# Red_Cross_Investigations
In this repository, I explore and describe data usable for the DKDC Red Cross Project.

#NFIRS Variable Descriptions

state - state incident occured

fdid - fire department id number

inc_no - incident number, "a unique number assigned to an incident, not an identification number"

city - city incident occured

street- street incident occured

zip5 - zip code

lat - latitude of incident (vector of NA)

lon - longitude of incident (vector of NA)

fips - (vector of NA)

date - date of incident

oth-inj

oth-death

exp_no - exposure number, "Exposure Number identifies each separate property type involved in the fire
  is defined as a fire resulting from another fire outside that building, structure, or vehicle, or 
  a fire that extends to an outside property from a building, structure, or vehicle."
  
inc_type - incident type, there are 11 different numbers that represent a type, "Buildings:111,
  Special structure: 112, Confined: 113–118, Mobile property: 120–123"
  
prop_loss - property loss

cont_loss - content lost, "illustrates the magnitude of the fire problem, provides an additional
  indicator of the incident severity, and can be used to evaluate progress in fire protection."
  
tot_loss - total loss, property loss + content loss

detector - presence of a detector: 1 if yes, N if no, U if unknown?

det_type - detector type, "1: Smoke, 2: Heat, 3: Combination smoke and heat, 4: Sprinkler, water flow detection,
  5: More than one type present, 0: Other, U: Undetermined."


det_power - detector power supply," 1: Battery only, 2: Hardwire only, 3: Plug-in,
  4: Hardwire with battery, 5: Plug-in with battery, 6: Mechanical, 7: Multiple detectors & power supplies,
  0:Other, U: Undetermined."
  
det_operat - detector operation, "1: Operated/effective, 2: Operated/Not effective, 3: Fire too small to activate,
  4: Failed to operate, 0: Other, U: Undetermined."
  
det_effect - detector effectiveness

det_fail - detector failure, "1: Power failure, shutoff, or disconnect, 
  2:Improper installation or placement, 3: Defective,
  4: Lack of maintenance, includes not cleaning, 5: Battery missing or disconnected,
  6: Battery discharged or dead, 0: other, U: Undetermined."
  
aes_pres - automatic extinguishing system, "1: Wet-pipe sprinkler system, 2: Dry-pipe sprinkler system,
  3: Other sprinkler system includes deluge sprinkler systems and pre-action sprinkler systems,
  4: Dry chemical system, 5: Foam system, 6: Halogen-type system includes nonhalogenated 
  suppression systems that operate on the same principle, 7: Carbon dioxide system,
  0: Special hazard system, other, U: Undetermined."
  
aes_type - 

aes_oper -

no_spr_op - number of sprinkler heads operating

aes_fail - reasure for system failure, "1 System shut off. 2 Not enough agent discharged to control the fire.
  3 Agent discharged, but did not reach the fire. 4 Inappropriate system for the type of fire.
  5 Fire not in area protected by the system. 6 System components damaged. 
  7 Lack of maintenance. Includes corrosion or heads painted. 8 Manual intervention defeated the system.
  0 Reason system not effective, other. U Undetermined."
