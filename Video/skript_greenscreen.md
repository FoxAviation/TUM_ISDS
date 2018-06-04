# Definition of configuration management
Instead of manual command-line interaction, configuration managment enables us to specify details about our system as code. Just like you would write and configure software.
* Marker["When we have a new collegue..." (00:08:21)]

# Reasons for Configuration Management
Configuration management allows me to keep track of every host I have and what software is running on it. I can automatically apply my configuration to all hosts, update all nodes or roll back a change if necessary. Configuration management also helps me to m onitor my environment and detect configuration issues before they arise on the live system. If there is a security issue, this setup allows me to automatically roll out patches for the affected software.
* Security [Marker]

# Key properties of configuration management
When selecting a configuration management tool, there are 4 key properties to look for.
* First: How is the environment specified?
Some tools use a declarative approach, where you describe the desired system state. What properties should your system have? In an imperative approach, you describe the steps to get your system to the desired state.
* Usually, configuration management tools are managed by a central server which provides the input files to the nodes you want to manage. Nodes can either pull their configuration from the central server or the server pushes the configuration on the nodes.
* Having infrastructure structured as code, this enables you to use all the tools you are familiar with in software development, especially version control. This allows for easy conflict management and testing.

* Interview: What advise would you give...? [Marker]

* Finally, you should not forget to check wether your tool of choice integrates well with the existing infrastructure. Also, you must consider if it is still in active development.
* Greenscreen fällt

What are the key properties?
* Input specification
    * Declarative / imperative
    * command line / gui based
    * Marker["When we have a new collegue..." (00:08:21)]
* Deployment properties
    * Scalability
    * Stage consistency (when migrating to another host)
    * Central / distributed management
    * Push / Pull
    * Plattform support
* Specification management properties (How to handle the specification)
    * VCS
    * Testing
    * Conflict management
* Support & Integration
    * Integration with other environments (Docker, ...)
    * Remote access
    * Community
