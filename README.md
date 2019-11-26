# YubiKey4Linux
An easy-to-use Yubikey installation tool for Ubuntu (and other Debian Distros)

## Introduction

Yubikey is a portable USB based biometric authentication device developed by Yubico that provides secure login and authentication to a variety of popular services and platforms. It provides intuitive installation process for some popular platforms such as Windows and Google Account, but installation process for Linux still remains complicated.

## Project Overview
Currently Yubikey installation process for Linux distributions is not an easy and simply process. This project aims to bring easy and convenient installation to Ubuntu, one of the most popular distribution of Debian Linux.

## Dependencies
Any version of Ubuntu, Python 3.7, Pyinstall. Anaconda Python management platform in prefered.

## Official Practices and Limitations

Currently all methods of installing Yubikey authentication to Ubuntu requires configuring YubiKey through terminal commands, testing YubiKey configuration through terminal commands, and finally enabling YubiKey. The whole process will take a long time to implement and test the result of installation. Along the process, several system files will be touched and modified along the way, if configured improperly, system and root privileges may be locked and cannot properly function without system re-imaging.

## Proposed Approach and Advantage

The aim of this project is to streamline the complex solution in order to make the setup as easy as possible. The tool will backup necessary system configuration files and walk users through the whole installation process. In case of uninstalling YubiKey, the tool will also reverse any changes to the system, and clean up any trace it left.

## Target Population and Benefit of the Project

This project is beneficial to all users willing to add extra security layer to their systems running Ubuntu. The streamlined process will be suitable for installation of YubiKey on large numbers of computers.

## Projected Risk and Risk Management

There are certainly risks that come with automated system. Luckily, this project requires minimal user and outside input. In fact, one of the goals of this project is to make user input as few as possible. However, the installation process requires two outside software packages, which may be tampered by third party. In addition, the scripts of installation and guiding tool may also be modified by third party.  

## Cost of the Project

For people already own Yubikey products, this tool will be free of charge.

