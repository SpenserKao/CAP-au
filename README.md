# CAP-au
Idea, finding, issue and note of CAP-au (Common Alerting Protocol - Australia)

## Schemas set 
The officicial home page of CAP-au is [1] and its Schemas set (XSD) ver 3.0 is available from [2].

### Issue with the ver 3.0 XSD
Duplicate definitions of Element 'code' - at line#110 and #117 is causing ill-formedness, as shown in the screenshot below.
<img href=""/>

This means that it cannot be used any further. On the contrary, CAP ver 1.2 [3] doesn't present such issue.

#### The resolution
See screenshot for an easy resolution.
<img href=""/>




# Reference
[1] https://data.gov.au/dataset/cap-au-std
[2] https://data.gov.au/dataset/cap-au-std/resource/137e98ce-f069-48ca-a420-274afc4ad78c
[3] https://github.com/google/cap-library/blob/master/schema/cap12_extended.xsd
