# wCCD-smart-contract

. build.sh
. test.sh
. build.sh OUT_FILE.WASM.V1
. deploy.sh OUT_FILE.WASM.V1 ACCOUNT MODULE_NAME
. initialize.sh MODULE ACCOUNT CONTRACT NAME

## Example

```
. build.sh
. test.sh
. build.sh cis2_wccd.wasm.v1
. deploy.sh cis2_wccd.wasm.v1 prince cis2_wccd_module
. initialize.sh cis2_wccd_module prince CIS2-WCCD cis2_wccd_module_instance
```
