# Introduction 

Configuration management refers to the process by which all artifacts relevant to
your project, and the relationships between them, are stored, retrieved, uniquely
identified, and modified.

# Using version control

* Keep Absolutely Everything in Version Control
    * Check Everything In
    * Version Control: The Freedom to Delete
* Check In Regularly to Trunk
* Use Meaningful Commit Messages    

# Managing Dependencies 

* Managing External Libraries
* Managing Components

# Managing Software configuration 

* Configuration and Flexibility
* The Danger of Ultimate Configurability
* Types of Configuration
* Packaging Configuration Information
* Managing Application Configuration
* Don’t Check Passwords into Source Control or Hard-Code Them
* in Your Application
* Accessing Configuration
```
getThisProperty()
getThatProperty()
```
* Modeling Configuration
* Testing System Configuration
* Managing Configuration across Applications
* Principles of Managing Application Configuration

# Managing Your Environments 

* Applying Configuration Management to Infrastructure
* Tools to Manage Environments
    * Puppet and CfEngine are two examples of tools that make it possible to manage
    operating system configuration in an automated fashion.
* Managing the Change Process    

# Summary

If your configuration management process is sound, you should be able to
answer “yes” to the following questions:
* Could you completely re-create your production system, excluding produc-
tion data, from scratch from the version-controlled assets that you store?
* Could you regress to an earlier, known good state of your application?
* Can you be sure that each deployed environment in production, in staging,
and in test is set up in precisely the same way?
If not, then your organization is at risk.
