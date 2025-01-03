# Db2 Driver for SQLTools

Built and maintained by

- Lucas Hancock (lucashancock@ibm.com)
- Daniel Hancock (daniel.hancock@ibm.com)

## Supported (Tested) Architectures

- MacOS Silicon
- Windows x86

## Installing and Running

The driver depends on node package ibm_db. For supported architectures above, this package will prompt you to install upon first use. For MacOs Silicon, it will be installed in the following directory:

`/Users/user/Library/Application Support/vscode-sqltools`

For Windows machines, it will be installed in the following directory:

`C:\Users\user\AppData\Local\Code\...`

You may also be prompted to enable a setting within SQLTools to acknowledge node runtime. Please select to enable. This is required for the driver to work. The purpose of this is to look on your machine for an up to date version of node to use as the runtime. The extension was built on the latest stable version of node (v23.4.0).

## Requirements

- VSCode version 1.96.0 or above
- Latest stable node version (tested v23.4.0)
- Latest stable npm version (tested v10.9.2)

## FAQ

WIP

## Contact

- Lucas Hancock (lucashancock@ibm.com)
- Daniel Hancock (daniel.hancock@ibm.com)

## Contributing & Development Environment

1. Clone the github repository
2. Refer to the contributing docs on SQLTools website to get started
3. Run `npm i` to install dependencies.
4. Run `npm run watch` to compile in watch mode or `npm run compile` to compile.
5. Press F5 while on src code tab to start Extension Development Host, or navigate to run and debug menu and run from there.
6. Have fun!
