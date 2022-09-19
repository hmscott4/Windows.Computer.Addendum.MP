# Windows.Computer.Addendum.MP
Windows computer Addendum MP with useful classes, rules and tasks

## Computer Attributes
Populates attributes that exist in the Operations Manager Windows.Computer object model, but which are not populated by default.

### GMT Offset Discovery
Discovers and populates the GMT Offset interval.

### Non-Microsoft Hypervisor Virtual Machine
Discovers and populates the Virtual Machine Attribute (True/False) even if the underlying hypervisor is not Hyper-V.

## Custom Computer Attributes (Extended Class)
Extends the Microsoft Windows Computer class to allow for custom attributes for organizing Windows Computers operationally.

### Division
The divison attribute is used to represent organizational entities within an Enterprise (for example, HR, Operations, Accounting, Sales)

### Service
The Service attribute is intended to represent the services hosted by the Windows Computer. For example, SQL, IIS, DNS, ADFS.

### Environment
The environment attribute is intended to represent the environment in which the Windows Computer resides.  For example, Production, Test, DR.

### Contact
The Contact attribute is intended to represent the individual (or individuals) who should be contacted when communications about a Windows Server are required.

## Non Microsoft Services Monitoring
Monitors selected non-Microsoft Services.  These Monitors are disabled by default.

### BES Client
Monitors the BigFix Enterprise Client Service

### McAfee
Monitors the McAfee client service

## VMWare Performance Counters
Collects selected VMWare Performance Counters that are exposed to the Windows guest operating system when VMWare Tools is installed.  These performance collection rules are all disabled by default.
