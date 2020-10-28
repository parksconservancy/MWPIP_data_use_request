# MWPIP_data_use_request

Thank you for your research interest in camera trap data from the One Tam project: the Marin Wildlife Picture Index Project! We welcome requests from any researcher and try to accomodate all reasonable requests. We ask that if you use our data in your research that you clearly cite it. We would also be grateful for a copy of your finished report.

This repository contains everything you need to decide if the data is suitable for your research and sending your research proposal to the project managers.

### Files

  1 Sample dataset
  2 Reach data use request form
  3 MWPIP data use policy
  
### Background

The Marin Wildlife Picture Index Project (MWPIP) was set up to monitor mid sized mammals continuously with automatically triggering wildlife cameras. Each time the camera is triggered it takes a burst of 3 images.  The cameras are placed on a 0.5 km grid, though the size of the grid was reduced to 1km sometime in 2016. The project is broken into smaller study sites, roughly representing different areas of public land. Camera memory cards are collected every 3 months, and cataloged by staff and volunteers, and then verified by experts.

Because the focus of the project was mid sized mammals, birds images are usually cataloged to Bird, unless the volunteer can ID the bird instantly. This was done to reduce cataloging time. Similarly small rodents are lumped together, and bats. Each species in an image gets its own record. For example if there is a deer and skunk on the same image there will 2 records with the same image ID, and different species

The dataset available for researchers runs from September 2014 to August 2017 and contains all verified reords. It is provided as a flat file (.csv). It does not contain any images. It does not contain any records of humans unless specifically requested and approved.

### Sample data

The sample dataset is a very small subset of the data from 5 random cameras. It is provided to give researches an idea of the utility of the data for them. The sample data has had the coordinates and cataloger names changed to protect sensitive data. 

Field Name    | Description
------------- | -------------
Project.ID | The name of the study site
Deployment.ID | The unique identifier of the deployment. A deployment is a data collection period at a camera
Image.ID | The unique identifier of the image.
Photo.Type | The type of cataloged image
Photo.Type.Identified.by | Who cataloged the image
Genus.Species | The scientific name of the species identified. General values of Bird, Bat, and Small Rodent are included
Uncertainty | The level of certainty that the cataloger had over their identification
DateTime.Captured | the timestamp of the image
Count | The number of individuals of that species in the image
Deployment.Location.ID | The unique identifier for the camera location within the grid cell (_1 is the first time a camera was placed in a grid cell, _2 would be for the next time, for example if a camera needed to be moved)
Longitude.Resolution | Longitude of the Deployment Location (fuzzied for sample data)
Latitude.Resolution | Latitude of the Deployment Location (fuzzied for sample data)
Camera.Deployment.Begin.Date | Date the SD card was placed in the camera to start the deployment
Camera.Deployment.End.Date | Date the SD card was removed from the camera to end the deployment
Bait.Type | Type of bait used. We don't use bait for this project
Camera.ID | The unique identifier for the 0.5 km grid cell
Quiet.Period.Setting | the number of seconds after camera has been triggered before it can be triggered again
Camera.Failure.Details | Was the camera working when the SD card was recovered
Make | Make of the camera
Model | Model of the camera
Year.Purchased | Year the camera was purchased

### Making a request

Please read the MWPIP data use policy thoroughly before filling out the data request. Although aimed at cataloging volunteers it does outline what the data is and is not to be used for. 

The MWPIP data belongs to a collaboration of four public land agencies and a supporting non profit. For this reason all Agencies must agree to release the data to a researcher. The group meet roughly every month to discuss research requests. Please be as detailed as possible when filling out the request form, this ensures that the request process is as smooth and fast as possible. Once filled out please email to the person that sent you the link to this github repository, and who is helping with your request.
