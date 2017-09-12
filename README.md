# Veracode All Flaws to CSV

## Description
Creates a CSV file with all open flaws for an account. The default includes policy-violating, non-mitigated flaws for all scan types. Flags can be used to override.

## Parameters
1.  **-user**: Veracode username.
2.  **-password**: Veracode password.
3. **-nonpv**: Will include non-policy violating flaws.
4. **-mitigated**: Will include flaws with accepted mitigations.
5. **-staticOnly**: Will only export flaws from static scans.
6. **-dynamicOnly**: Will only export flaws from dynamic scans.

**Note**: Setting _-staticOnly_ and _-dynamicOnly_ flags will export all flaws excluding those from MPT.