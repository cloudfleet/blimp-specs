The Data Model of a Cloud Fleet Blimp
====================================

## Types of Data

1. Application
2. Cloudfleet Configuration
3. Blimp Configuration
4. User Data

### 1. Application Data

Everything the Application needs to run inside the cloudfleet environment.
(Including configuration where the data is stored)
This is only updated when application is updated.

### 2. Cloudfleet Configuration

This contains everything necessary to connect to the cloudfleet network. At least a preshared key that identifies the box.

### 3. Blimp Configuration

This contains the key for the disk encryption and the backup. MUST NOT be stored on disk.

### 4. User Data 


## Interaction Between Apps
