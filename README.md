# Tiket Online Agent Website

### Update Step

-   Export Latest Database for backup, and for migrate/upgrade on local
-   Backup any image in public/uploads

### Build

#### Swiftbooking

-   changes .env
    VITE_BUILD_OPT="partner"
-   npm run build
-   zip the folder

#### Nusa

-   changes .env
    VITE_BUILD_OPT="nusa"
-   npm run build
-   zip the folder

#### Singgahsiniaja

-   changes .env
    VITE_BUILD_OPT="partner"
    VITE_BUILD_GLOBALTIX=false
-   npm run build
-   zip the folder
