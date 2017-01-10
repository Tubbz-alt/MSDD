# REDHAWK FEI Compliance Test Results

## Execution

To run [test\_MSDD\_FEI.py](test_MSDD_FEI.py), execute the following command from the `/tests` directory:

```
python test_MSDD_FEI.py
```

The test may take several minutes to perform the many checks when successful. It is common that fewer checks are made when unexpected failures occur, which prevent all checks from being made.

## Important Note

The unit test test needs to be configured with the IP address settings for the MSDD device under test. In the test\_MSDD\_FEI.py file there is a python dictionary called dut\_configuration with entries for "msdd_configuration" and "msdd_output_configuration" which needs to be updated to have the correct network settings for your radio. dut_capabilities also needs to be set to represent the correct capabilities for your hardware. The current capabilities are correct for an MSDD-6000.

## Test Configuration
Our testing was completed with the following hardware and software

Model: MSDD-6000
FPGA: 
firmware: 
 

## Results

### Summary Report

```
Report Statistics:
   Checks that returned "WARN" .................. 34
   Checks that returned "no" .................... 5
   Checks that returned "ok" .................... 205
   Checks with silent results ................... 38
   Total checks made ............................ 282

```

* `FAIL` indicates the test failed. It may be acceptable to fail a test depending on the device/design. 
* `WARN` CAN be fine, and may just be informational. 
* `info` is fine, just informational for developer to confirm the intended results.
* `no` is fine, just informational for developer to confirm the intended results. Indicates an optional field was not used.
* `ok` is good, and indicates a check passed.
* `silent results` are checks that passed but do not appear anywhere in the output unless they fail.
'''

### `error` Details
None

