# StripeSOC - Hermetic Wiper Malware Detection Rules
These detection rules are shared in ARM format, this means that you can download and directly import them without the fuss of using the raw kusto

Go to Azure Sentinel -> Analytics -> Import and select the ARM template e.g. 'STRSOC-UKR-HermeticWiper-ARMGRP.json' from your downloads

The file named 'STRSOC-UKR-HermeticWiper-ARMGRP.json' is a group of all of these rules, so you can import this one and it will import all three without you having to.

Should you wish to pick and choose amongst the rules there are 3 seperate rules sorted by class (CL1-5).

Currently awaiting R&D on Class-4 which is a detection for commandline arguments.

## Update
Added raw-kql files (suffixed -KQL) in case you were not into the idea of uploading directly to Sentinel and/or wanted to translate to another platform.

The license of this directory is the same as the parent directory, GPL. 

StripeSOC Team
