# Windows.Computer.Addendum.MP
Windows computer Addendum MP with useful classes, rules and tasks

# H2 Computer Attributes
Populates attributes that exist in the Operations Manager Windows.Computer object model, but which are not populated by default.

# H3 GMT Offset Discovery
Discovers and populates the GMT Offset interval.

# H3 Non-Microsoft Hypervisor Virtual Machine
Discovers and populates the Virtual Machine Attribute (True/False) even if the underlying hypervisor is not Hyper-V.

# H2 Custom Computer Attributes (Extended Class)
Extends the Microsoft Windows Computer class to allow for custom attributes for organizing Windows Computers operationally.

# H3 Division
The divison attribute is used to represent organizational entities within an Enterprise (for example, HR, Operations, Accounting, Sales)

# H3 Service
The Service attribute is intended to represent the services hosted by the Windows Computer. For example, SQL, IIS, DNS, ADFS.

# H3 Environment
The environment attribute is intended to represent the environment in which the Windows Computer resides.  For example, Production, Test, DR.

# H3 Contact
The Contact attribute is intended to represent the individual (or individuals) who should be contacted when communications about a Windows Server are required.

# H2 Non Microsoft Services Monitoring
Monitors selected non-Microsoft Services.  These Monitors are disabled by default.

# H3 BES Client
Monitors the BigFix Enterprise Client Service

# H3 McAfee
Monitors the McAfee client service

# H2 VMWare Performance Counters
Collects selected VMWare Performance Counters that are exposed to the Windows guest operating system when VMWare Tools is installed.  These performance collection rules are all disabled by default.
