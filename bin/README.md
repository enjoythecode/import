directory of random files required to run the import tool on my (snny) import tool.

I am committing these into a branch that is never to be merged, because I want to be able to reference
arbitrary commands here for areas of improvements I find along the way.

workflow:
1. *change something in the original source* (potentiall using vim dc_generated/report.json to peek at the errors)
1. s/cp_src.sh # copies over source files (mcf/tmcf/csv) from ~/data/scripts/fema/nri (which is the setup I have on my local)
1. s/lint.sh   # runs lint on schema mcf
1. git diff    # see what errors have changed
1. *repeat as needed* 
