<p align="center"><a href="https://advantagecsp.com/" rel="noopener" target="_blank"><img width="500px" src="https://advantagecsp.com/Assets/AdvantageCMS/Images/advantagecsp-2x.png" alt="Advantage CSP - Enterprise-Class Content Management System"></a></p>

## Upgrading from versions < 7.4.0.0  to 7.4.x.x (+)
If you utilize source code control.  Please ensure that all *new* files are included in your check-in after upgrade.  Specifically the Bin and Scripts folder.  There have been lots of additions to incorporate the latest Microsoft security implementations and Bootstrap script files.

## Admin web.config
Please make sure to review the /Admin/web.config file.  There are new settings for password complexity.
 
## Application web.config
Please review and update the following sections in the applications web.config
- <runtime><assemblyBinding><dependentAssembly> - Additional required references for Microsoft OWIN implementation
- <system.codedom><compilers> - Update of the Rosyln code compiler to latest version






