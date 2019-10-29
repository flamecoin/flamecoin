## Seeds

Utility to generate the seeds.txt list that is compiled into the client
(see [src/chainparamsseeds.h](/src/chainparamsseeds.h) and other utilities in [contrib/seeds](/contrib/seeds)).

Be sure to update `PATTERN_AGENT` in `makeseeds.py` to include the current version,
and remove old versions as necessary.

# How to use
    git clone https://github.com/flamecoin/flamecoin/
    cd contrib/seeds/
Place all you IPs of seeds in `nodes_main.txt`

Then run
    
    python generate-seeds.py .
    
It should output a peice of code that looks like the one in src/chainparamsseeds.h


### Dependencies

Ubuntu:

    sudo apt-get install python3-dnspython
