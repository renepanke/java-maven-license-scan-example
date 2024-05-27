# Java Maven License Scan Example

## Acknowledgments to the plugin author

All functionality-wise credits go to [github.com: carlomorelli/licensescan-maven-plugin](https://github.com/carlomorelli/LicenseScan-Maven-Plugin).
This repository does only provide an example on how to use the plugin.

---

This repository holds a basic example for scanning a maven project for licenses that can't be used in proprietary
projects.

> **DISCLAIMER: THIS IS NOT LEGAL ADVICE NOR DOES THIS LIST CLAIM TO BE EXHAUSTIVE.**
>
> **FEEL FREE TO OPEN A PULL REQUEST TO SUBMIT ADDITIONAL LICENSES THAT DO  REQUIRE TO DISCLOSE
SOURCE CODE.**

## Executing the scan

You can execute the license scan by executing `mvn clean package licensescan:audit` on the command line.

A report is generated under `${projectDir}/target/license-scan-resulsts/index.html` which can be opened with any
browser.

## Usage/Examples

Try adding the commented out projects and see the `licensescan:audit` command failing. Also have a look on the report.
