# CryptoShare Demo 1.0.0-demo.3

Corrective public evaluation build for Windows x64.

- Package: `CryptoShare-Demo-1.0.0-demo.3-windows-x64.zip`
- Size: `68,789,895 bytes`
- SHA-256: `06cdf1103206c4237ea275528303d985ba85529a7354d3730b00799471897929`

## Fixed

- signature verification no longer accesses WPF controls from a background thread;
- encrypted-file inspection no longer accesses WPF controls from a background thread;
- the affected tools can now be used normally after encryption or decryption.

## Interface

- completely renewed Windows Presentation Foundation interface;
- dashboard, navigation, colours, typography and controls redesigned in the style of CodexUsageMonitor;
- new application icon coordinated with the refreshed visual identity;
- simplified presentation while preserving the complete CryptoShare workflow;
- self-contained Windows x64 package: no separate .NET installation is required.

## Included

- file and folder encryption with AES-GCM;
- all-of-N key-share generation;
- decryption workflow;
- RSA public-key export, signature verification and encrypted-package inspection;
- the same navigation and operational interface as CryptoShare Full 1.0.0-rc.3.

## Demo limitation

The selected file, or the sum of all files contained in a selected folder, must not exceed
1 MiB (1,048,576 bytes). No other feature is intentionally disabled.

## Important

This is unsigned, pre-release evaluation software. It has not undergone an independent security
audit, is provided without support or warranty, and must not be used with critical data.
