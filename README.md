# ScorpionTrack Tacho

ScorpionTrack Tacho is SaaS that enables you organisation to remotely download your company vehicles Tachograph files.

The files are stored on the Tacho server in the one in the desired formats (.DDD, .V1B, .C1B, .TGD). 

The tachograph files can be downloaded via the website, email or FTP'd to a remote server.  

## Requirements

!> Tachograph  - Siemens VDO Digital Tachograph - DTCO 1381 (release 1.3a, 1.4 or later), Stoneridge Tachograph - SE5000 (release 7.1 or later) 

!> Additional hardware - Company card registered in the Tachograph, Tachograph Card reader (SmartCardReader), recommended model: Cryptotech CLOUD 2700 R 

## Company Card Check

The Company card which will be used for downloading the DDD files remotely must be registered in tachograph. 

This is the same company card that would be used if directly downloading from the tachograph, this card should already be registered with the tachograph unit.

A PC with the company card connected to it via the card reader must be available at all times for authorization to work between the tachograph unit and server to complete the download.

This machine must have an active internet connection and connected company card via card reader with the installed software. Then the tachograph unit may authorize the card and upload tachograph files to the tacho server. 

To connect a company card, “Remote SCard Reader” applicaiton should be installed. 
 
Installation Guide: 
* To install the “Remote SCard Reader”
    * Launch installer application “Remote SCard Reader.exe” 
    * Press “Install”
    * Wait for installation to complete 
    * Close installer. 
 
If card reader is connected and company card is inserted – you should see following view: 
* Gray - Company card is not inserted
* Red - Unable to read Card ID, inappropriate or broken Card.
* Yellow - Company card ID read, waiting for authorization from server.
* Green - Company card ID is read and authorized.
* Blue - Shows using what device(imei) company card is communicating with tachograph.

## Vehicles

The vehicle section is the home view, from here you can add, remove and edit vehicles, monitor and download files and observe schedule status changes in real time.

## Download Schedules

From the download schedule tab, you can create, edit and remove shedules for pulling the tachograph files, using the checkboxes you can select what information you want to download from the tachograph unit.  

## Tachograph Files

From the tachograph file view, you can download the syncronized tachograph files to your local machine, for the files to be present the vehicle must have cycled ignition after the scheduled download time with the company card present in the card reader.

## History

From the history tab, you can view the history of scheduled file downloads, when the unit was last present and if the files were downloaded before, the history acts as an audit log to show what happened where and why.

## Company Card Management

From the company card management tab, you can add, edit and delete company cards. Multiple cards may be necessary when working with fleets using multiple company cards (regional depots). Using the tacho card reader program, you can generate the card code to enter into the code area.

## Company Management

From the company management screen you can add, edit and delete companies. This is used for managing depots within a single company, this is subject to the total limit of devices available to the current logged in company group.

## User Management

From the user management screen you can add, edit and delete users. Setting the users view permissions and access, they can be restricted to view only certain depots.

## Remote File Synchronization

From the remote file synchronization screen you can set up custom FTP settings. This means that files can automatically be FTP'ed once they have been syncronized between the tachograph unit and the tacho server.
 