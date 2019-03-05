# ref_cc_c
A script to examine EPrints' history and make doubly sure that, even if installed after Apr 2016, the hefce_oa data is accurate

## usage

To report on potenial changes for FOA, FCD and EMB_LEN:

`ref_cc_c [repoid]`

To send CSV output to a file:

`ref_cc_c [repoid] --output=[file]`

To report on (or update) a single record:

`ref_cc_c [repoid] --eprintid=[eprintid]`

To update the hoa_date_foa, hoa_date_fcd and hoa_emb_len. __Do not use this if you are unsure what it will do__

`ref_cc_c [repoid] --update`
