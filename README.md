# Citrix Workspace

Download latest release from Releases:       
https://github.com/glideroute/Citrix-Workspace/releases/tag/25.3.10

Use the on-screen installer to complete the setup and initial configuration according to your organization's requirements. Consult the Installation and Setup Guide for comprehensive instructions.

## System Requirements

* **Operating System:** Requires Windows 10 24H2 or a newer compatible release.
* **.NET Framework:** Must have .NET Desktop Runtime 8.0 or later installed.
* **Supported Browsers:** Provides full compatibility with modern Chromium-based browsers.
* **Hardware Compatibility:** Designed to run efficiently on desktops, tablets, and thin clients that satisfy Citrix hardware guidelines regarding CPU, memory, and storage.

## Configuration

To deliver consistent performance and maintain a standardized user environment, refine the Citrix Workspace App using the following configuration settings:

* **Beacon Tests:**
  These tests confirm that network paths to Citrix services are reachable, helping ensure stable connectivity. Use the Configuration Checker to run these validations and maintain session reliability.

* **USB Device Memory:**
  Improves peripheral management by remembering manually attached USB devices. After a device is detected once, it will reconnect automatically during later sessions, streamlining user workflows.

* **Store Setup:**
  Administrators can assign clear and identifiable store names within the app. Additional settings allow or restrict users from altering these names to maintain uniformity across deployments.

* **Power Policy Management:**
  Prevents devices from entering sleep mode while sessions are active, minimizing workflow interruptions.

* **Advanced Customization:**
  Offers IT administrators granular control over appearance, session behaviors, and virtual channel settings, enabling the workspace to be tailored to organizational standards.

For complete setup instructions, consult the [Citrix Workspace Configuration Guide](*).

## Troubleshooting

The Citrix Workspace App provides an extensive set of diagnostic tools designed to help quickly detect and resolve technical issues. Key troubleshooting categories include:

* **Authentication Issues:**

  * SSO or Kerberos-related problems are often resolved by confirming user credentials and validating Active Directory configuration.
  * Consistent login failures may require reviewing authentication logs within the Workspace App.

* **Network Diagnostics:**

  * Use the Connection Strength Indicator for real-time visibility into network conditions and potential connectivity issues.
  * For deeper investigation, complement Citrix utilities with reputable third-party network analysis tools.

* **Device Compatibility Validation:**

  * Verify that USB devices, webcams, and audio equipment are supported by the installed app version. Keeping drivers current helps maintain consistent performance.
  * Citrix documentation includes lists of tested hardware and any known limitations.

* **Log Analysis and Reporting:**

  * Session logs and diagnostic reports provide crucial information for troubleshooting complex issues. Administrators can use these records to pinpoint root causes more effectively.

* **Session Disconnection Handling:**

  * Review client settings, network parameters, and session policies to identify why unexpected disconnections occur.
  * Enabling auto-reconnect features can help mitigate the effects of brief network interruptions.

For complete troubleshooting guidance, visit the [Citrix Workspace Troubleshooting Page](*).

## Changelog

### Version 2409 (Latest)

* **New Enhancements:**

  * Full support for Windows 11 24H2, incorporating the latest OS improvements.
  * Refinements focused on improved energy efficiency and enhanced beacon responsiveness.
  * TLS 1.3 is now enabled by default, providing stronger encryption.
  * Optimized handling of virtual desktops during launch and resizing for a smoother interface.

* **Resolved Issues:**

  * Corrected login issues tied to Workspace Environment Management.
  * Fixed display inconsistencies and errors in resource listings.
  * Addressed USB device reconnection failures during session restarts.
  * Improved error messaging to better assist in diagnosing launch failures.

### Previous Versions

* **Version 2405:**

  * Introduced Single Sign-On support for ARM64 hardware, broadening platform coverage.
  * Enhanced logging capabilities and beacon diagnostics to simplify administration.
  * Improved multimedia performance for Microsoft Teams running in virtualized environments.
  * Added MJPEG webcam support for enhanced video quality.
  * Delivered new Desktop Viewer customization options, including toolbar and session controls.

* **Version 2403:**

  * Added new power-saving features tailored for hybrid environments.
  * Improved domain-based SSO for faster authentication processes.
  * Updated support for the latest Chromium Embedded Framework (CEF) builds.
  * Added new security policy controls such as process whitelisting and USB restrictions.
  * Streamlined installation of the Microsoft Teams VDI plugin to enhance collaboration.

## Key Features

Citrix Workspace App for Windows provides a comprehensive set of features designed to enhance security, usability, and overall productivity. Notable capabilities include:

* **Single Sign-On (SSO):**
  Enables seamless login using domain credentials or Kerberos, ensuring direct and secure access.

* **Integrated Microsoft Teams Optimization:**
  Enhances virtual collaboration through superior audio and video handling and dedicated Teams optimizations.

* **Streamlined Desktop Experience:**
  Supports smooth desktop launching and resizing, ensuring a consistent visual experience.

* **TLS 1.3 Encryption Support:**
  Uses the most current Transport Layer Security protocol to deliver stronger data protection.

* **SOCKS5 Proxy Compatibility:**
  Allows secure and flexible connectivity across enterprise networks.
