# DiskDonkey
A minimal disk usage analyzer made with native C#. No nuget packages or dependencies required.

Usage: DiskUsage.exe [-p <path>] [-m <minSizeGB>] [-d <maxDepth>] [-o <outputFilePath>] [-h]

-p, -path <path>        : Starting directory to scan (e.g., C:\).

-m, -minsizegb <size>   : Minimum size in GB for a folder to be reported. Default is 1 GB.

-d, -maxdepth <depth>   : Maximum directory depth to scan. -1 for infinite (default).

-o, -output <filePath>  : Path to a file to save the report. (e.g., C:\\Reports\\du_report.txt)

-h, -help, /?           : Show this help message.
  
