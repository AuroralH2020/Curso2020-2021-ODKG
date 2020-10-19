# Hands-on assignment 4 – Self assessment

## Checklist

**Every RDF file:**

- [ ] Uses the .nt extension
- [x] Is serialized in the NTriples format
- [x] Follows the resource naming strategy
- [x] Uses class and property URIs that are the same as those used in the ontology

**Every URI in the RDF files:**

- [x] Is "readable" and has some meaning (e.g., it is not an auto-increased integer) 
- [ ] Is not encoded as a string
- [ ] Does not contain a double slash (i.e., “//”)

**Every individual in the RDF files:**

- [x] Has a label with the name of the individual
- [x] Has a type

**Every value in the RDF files:**

- [x] Is trimmed
- [ ] Is properly encoded (e.g., dates, booleans)
- [x] Includes its datatype
- [ ] Uses the correct datatype (e.g., values of 0-1 may be booleans and not integers, not every string made of numbers is a number)

## Comments on the self-assessment
- RDF file is in Turtle format
- URI in RDF file contains a double slash in http:**//**
- Initial version does only contain strings