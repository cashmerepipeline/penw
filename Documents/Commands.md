# Commands

## Environment
    Environment is the base.

### New-PEWEnvironment
    Create a environment configs base on a template.
    Usage:
        New-PEWEnvironment TemplateName Environment [OutPath]

### Get-PEWEnvironment
    Get a environment for running some packages.
    Usage:
        Get-PEWEnvironment environment [clean]
        clean: if use current environment or not.

### Install-PEWEnvironment
    Install a configured environment.
    Usage:
        Install-PEWEnvironment environment

### Check-PEWEnvironment
    Check a environment is ok.
    Usage:
        Check-PEWEnvironment environment
    
## Package
    Package is the actor.

### New-PEWPackage
    Create a new package base on a template.
    Usage:
        New-PEWPackage

### Install-PEWPackage
    Install package or Packages and dependents.
    Usage:
        Install-Package package [FromSource]

### Check-PEWPackage
    Check package and dependents status and log.
    Usage:
        Check-PEWPackage package

### Run-PEWPackage
    Run a package, package is must executable.
    Usage:
        Run-PEWPackage package [with environment]

