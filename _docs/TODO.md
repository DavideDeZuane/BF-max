
# TODO

## Refactoring

- [x] Organize this repos
- [x] 3 files, one for each decoder (BFmax, hybrid and OoP)
- [x] Make BFmax the default decoder
- [x] Add hybrid decoder
- [x] Add OoP decoder
- [x] Reorganize code for bfmax
- [x] Add comments to the cmake decoder section
- [x] Add hybrid decoder with different configurations
- [x] Define a new header file for new circulant side
- [x] Precompute modular inverse for new circulant side
- [x] Add the ciruclant side also at compile time
- [x] Change benchmarking for DFR measurement
- [ ] CMake to compile one executable for each decoder (opzione `ALL`)
- [ ] Move keygen inside the loop for DFR measurements
- [x] Add flag for benchmark with `libcpucycles`
- [x] Add `ntfy.sh` for the status of the simulations
- [x] Script to compile for each value of `R_BITS`
- [x] Edit `test_dfr.c` to be compliant with the script for gnu parallel (move logging to file and keep only the end line)
- [x] Create directory `scripts` and move `dfr.sh` and `cc.sh` inside
- [ ] Standardize the parameters of the two scripts 
- [ ] Remove `primes` dir from `_docs` and update scripts example 


## Implementation

- [ ] Define `bfmax_decode_ctx` with 2 functions `argmax` and `update`
- [ ] Remove the conversion function from benchmark
- [ ] Optimization with BIKE structure
- [ ] Add explicit failure in building executable in `dfr.sh`
- [ ] Add `CONSTANT_TIME` flag for the OOP decoder

## Simulations

- [x] Value of P to achieve `10^-5` for each decoder
- [x] Latex file for DFR graphs 
- [x] Simulation for Hybrid with `0.3t -> 3`
- [x] Simulations with `p` in 10500-11500
- [x] DFR Missing primes for hybrid(0.4,2)
- [ ] 1e8 Simulations for Decoder

## Question

- [ ] Is the BFmax constant time?
- [ ] security L3
- [ ] Goals of the paper
- [ ] DECODER COMPLEXITY for comparison

