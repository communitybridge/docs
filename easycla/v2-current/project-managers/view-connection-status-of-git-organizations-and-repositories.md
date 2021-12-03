# View Connection Status of Git Organizations and Repositories

After you add a GitHub or Gerrit organization or GitLab group, the organizations or groups are displayed with different colors referring to their connection statuses. The following is an example:

![Git Organization Connection Status](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MYOFDf7emdfValpgSIU%2F-MYORveInxrclFsUvUa5%2Fgithub%20organization%20connection%20status.png?alt=media\&token=936ddffc-4f11-4bab-b080-dbb2dab0433c)

* ​![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MGgGDh5YsW-7vaCluVV%2F-MGh5g18AZefEt1wpYYV%2Fconnected%20green%20color.png?alt=media\&token=3ee52f88-3621-4e59-a8d3-f8d1c1c50005)indicates _full connection_: all the repositories of the organization are connected.
* ​![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MGgGDh5YsW-7vaCluVV%2F-MGh5plY4opHfbYw2yrL%2Forange%20partial%20connection.png?alt=media\&token=9e218691-df77-4c18-84ae-cf14041a23c2)indicates _partial connection_: some repositories of the organization are connected.
* ​![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MGgGDh5YsW-7vaCluVV%2F-MGh62lG27ujeWeQxhlO%2Fgrey%20no%20connection.png?alt=media\&token=7b0a6e53-42f3-42ce-94cd-8c676d815a2d)indicates _no connection_: the organization is added, but its repositories are not [EasyCLA enforced](enforce-or-remove-cla-mechanism.md).
* ​![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MGgGDh5YsW-7vaCluVV%2F-MGh68mF0vvr0JPoDen0%2Fred%20connection%20failure.png?alt=media\&token=3ba17994-1ea0-4523-b738-9fd17ef0debe)indicates _connection failure_: for a connected organization, either the EasyCLA configuration is uninstalled or the organization is deleted from GitHub/Gerrit/GitLab.

A repository with a cross mark next to it indicates connection failure. It means the repository was EasyCLA enabled, but it is deleted from the organization.
