# Submit Version 1.0.3
## Test Environments
* local OS X build, check, install, R version 3.5.1
* travis-ci Ubuntu Linux 16.04.6 LTS build, check, install, R version 3.6.0
* win-builder

## R CMD check results
There was 1 NOTE:

```
* checking CRAN incoming feasibility ... NOTE
Maintainer: 'Justin Kamerman <justin@kaleco.net>'

New maintainer:
  Justin Kamerman <justin@kaleco.net>
Old maintainer(s):
  Justin Kamerman <justin.kamerman@unb.ca>
```


# Submit Version 1.0.2
## Test Environments
* local OS X build, check, install, R 3.3.0
* local AWS Linux build, check, install, R 3.2.2
* win-builder

## R CMD check results
There was 1 NOTE:

```
* checking CRAN incoming feasibility ... NOTE
Maintainer: ‘Justin Kamerman <justin.kamerman@unb.ca>’

License components with restrictions and base license permitting such:
  MIT + file LICENSE
File 'LICENSE':
  YEAR: 2016
  COPYRIGHT HOLDER: Connie Stewart, Justin Kamerman
```


# Submit Version 1.0.1
## Test Environments
* local OS X build, check, install, R 3.3.0
* local AWS Linux build, check, install, R 3.2.2
* win-builder

## R CMD check results
There was 1 NOTE:

```
* checking CRAN incoming feasibility ... NOTE
Maintainer: ‘Justin Kamerman <justin.kamerman@unb.ca>’

License components with restrictions and base license permitting such:
  MIT + file LICENSE
File 'LICENSE':
  YEAR: 2016
  COPYRIGHT HOLDER: Connie Stewart, Justin Kamerman
``

# Submit Version 1.0.0 
## Resubmission
* Added @examples code to main function p.QFASA() detailing use of package:

```
* checking files in ‘vignettes’ ... OK
* checking examples ... OK
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ...
  Running ‘testthat.R’
 OK
* checking for unstated dependencies in vignettes ... OK
* checking package vignettes in ‘inst/doc’ ... OK
* checking re-building of vignette outputs ... OK
* DONE

Status: OK

R CMD check results
0 errors | 0 warnings | 0 notes
```

## Resubmission
* Incorporate late authorship change request in DESCRIPTION
* Updated LICENSE to comply with CRAN template

## Test Environments
* local OS X build, check, install, R 3.2.4
* local OS X build, check, install, R 3.3.0
* local AWS Linux build, check, install, R 3.2.2
* win-builder

## R CMD check results
There were no NOTES, ERRORS or WARNINGS.

Submitted from Linux because of LaTeX errors on OSX:

```
* checking PDF version of manual ... WARNING
LaTeX errors when creating PDF version.
This typically indicates Rd problems.
LaTeX errors found:
! Font T1/phv/m/n/14.4=phvr8t at 14.4pt not loadable: Metric (TFM) file not fou
nd.
<to be read again> 
                   relax 
l.45 \Rdcontents{\R{} topics documented:}
* checking PDF version of manual without hyperrefs or index ... ERROR
* DONE

Status: 1 ERROR, 1 WARNING
See
  ‘/private/var/folders/g6/7xdk55_s7d5b4q17985h2b1r0000gp/T/Rtmpqktvy0/QFASA.Rcheck/00check.log’
for details.

R CMD check results
1 error  | 1 warning  | 0 notes
checking PDF version of manual without hyperrefs or index ... ERROR

checking PDF version of manual ... WARNING
LaTeX errors when creating PDF version.
This typically indicates Rd problems.
LaTeX errors found:
! Font T1/phv/m/n/14.4=phvr8t at 14.4pt not loadable: Metric (TFM) file not fou
nd.
<to be read again> 
                   relax 
l.45 \Rdcontents{\R{} topics documented:}
```


