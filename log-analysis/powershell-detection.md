# Suspicious PowerShell Detection

## Objective

Detect encoded PowerShell commands commonly used by attackers.

## Test Activity

Executed the following command:

powershell -EncodedCommand aGVsbG8=

## Detection Query

index=main CommandLine="*EncodedCommand*"

## Expected Outcome

The SIEM should return an event showing encoded PowerShell execution.

## Results

Replace with screenshot of query results.

## Security Insight

Encoded PowerShell commands are frequently used in malware and attacker scripts.
