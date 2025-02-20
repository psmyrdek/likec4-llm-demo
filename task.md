Container "SFTP"
Container “Worker” that consumes files from SFTP
Container “App DB” that is Database
Container “WebApp”
Container “WebApp” and “Worker” are connecting to “App DB”
Person "User" that connects to "WebApp"
