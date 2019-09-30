# printclient-releases
Contains releases for SimpleRfid print client

Product code {8927ECC5-7B21-457A-9177-00A34E9FCD69}

Upgrade code {A8A4BFEE-D869-4A2A-BA3D-CDCDDD73AA21}


Steps to deploy New print Client's version:

1. Increase Assembly vresion and File version of SimpleRfid.NewPrintClient project (these options will be in Properties -> Assembly Information window).
2. Increase SimpleRfid.NewPrintClient.Installer's Version (in Properties window). After increasing Version's number you'll see window which should ask you to change Product code. Press "Yes". (!IMPORTANT! SimpleRfid.NewPrintClient versions numbers and SimpleRfid.NewPrintClient.Installer version number should be the same).
3. Change Upgrade code in SimpleRfid.NewPrintClient.Installer project to Upgrade code from this documentation (↑ above this steps).
4. Build SimpleRfid.NewPrintClient project in Prod or Release mode.
5. Build SimpleRfid.NewPrintClient.Installer project in Prod or Release mode.
6. Go to SimpleRfid.NewPrintClient.Installer's folder, then go into "Release" folder, where you'll see simplerfid-printclient.msi file.
7. Create new release with same number as your project's versions in this repository. And add simplerfid-printclient.msi as attached file.
