# SonarQube Manager — Downloads

An independent Windows desktop utility for configuring and managing a SonarQube Windows service. Built with Rust and GPUI Kit.

## Download

[Download the Windows x64 installer](https://github.com/sannlynnhtun-coding/sonarqube-manager-downloads/releases/latest/download/SonarQubeManager-Setup.exe) · [All releases](https://github.com/sannlynnhtun-coding/sonarqube-manager-downloads/releases)

## Requirements and setup

1. Install the Java version required by your SonarQube release and make it available on PATH.
2. Download and extract SonarQube separately.
3. Install SonarQube Manager and approve the Windows administrator prompt.
4. Select the extracted SonarQube folder, configure host and port, then install/start the Windows service.
5. Open SonarQube after the web server becomes ready. Use your scanner separately to analyze projects.

Java and SonarQube are not bundled. The manager supports one Windows service named SonarQube. The default host is 127.0.0.1 and port is 9000. Closing the manager hides it to the system tray; exiting the manager leaves the service running.

This repository publishes installers only. It is an independent utility and is not an official SonarSource product. SonarQube branding belongs to SonarSource.
