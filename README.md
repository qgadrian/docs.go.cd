# Go Design Documentation

#### 1. Introduction

#### 2. Concepts in Go

* [2.1 Domain](2/2.1.md) ![NOT DONE](images/red.png)

    * [2.1.1 Pipeline](2/2.1.1.md) ![NOT DONE](images/red.png)

    * [2.1.2 Stage](2/2.1.2.md) ![NOT DONE](images/red.png)

    * [2.1.3 Job](2/2.1.3.md) ![NOT DONE](images/red.png)

    * [2.1.4 Task](2/2.1.4.md) ![NOT DONE](images/red.png)

    * [2.1.4 Material](2/2.1.4.md) ![NOT DONE](images/red.png)

* [2.2 Implementation](2/2.2.md) ![NOT DONE](images/red.png)

#### 3. Getting Started

* [3.1 Setting up your development Environment](3/3.1.md) ![IN PROGRESS](images/yellow.png)

#### 4. Technology Stack

* [4.1 Plugins Architecture - OSGi](4/4.1.md) ![NOT DONE](images/red.png)

* [4.2 Object Relation Mapping (ORM) - Hibernate & IBatis](4/4.2.md) ![IN PROGRESS](images/yellow.png)

* [4.3 Caching - EhCache](4/4.3.md) ![NOT DONE](images/red.png)

* [4.4 Dependency Injection (DI) - Spring](4/4.4.md) ![NOT DONE](images/red.png)

* [4.5 Model View Controller (MVC)](4/4.5.md) ![NOT DONE](images/red.png)

    * [4.5.1 Models - Java](4/4.5.1.md) ![NOT DONE](images/red.png)

    * [4.5.2 Controllers - Servlets & Rails](4/4.5.2.md) ![NOT DONE](images/red.png)

    * [4.5.3 Views - Rails & Velocity](4/4.5.3.md) ![NOT DONE](images/red.png)

* [4.6 User Interface (UI) - jQuery & Prototype, SCSS, HTML](4/4.6.md) ![IN PROGRESS](images/yellow.png)

* [4.7 Build Tool - Buildr](4/4.7.md) ![NOT DONE](images/red.png)

#### 5. Architecture of Go

* [5.1 Overview](5/5.1.md) ![NOT DONE](images/red.png)

* [5.2 Go Server](5/5.2.md) ![NOT DONE](images/red.png)

    * [5.2.1 Configuration Management](5/5.2.1.md) ![NOT DONE](images/red.png)

        * [5.2.1.1 XSD & XML](5/5.2.1.1.md) ![NOT DONE](images/red.png)

        * [5.2.1.2 SchemaMigration](5/5.2.1.2.md) ![NOT DONE](images/red.png)

        * [5.2.1.3 ConfigRepository](5/5.2.1.3.md) ![NOT DONE](images/red.png)

        * [5.2.1.4 ConfigMerge](5/5.2.1.4.md) ![NOT DONE](images/red.png)

        * [5.2.1.5 ConfigDiff](5/5.2.1.5.md) ![NOT DONE](images/red.png)

    * [5.2.2 Database Management](5/5.2.2.md) ![IN PROGRESS](images/yellow.png)

        * [5.2.2.1 Schema](5/5.2.2.1.md) ![NOT DONE](images/red.png)

        * [5.2.2.2 Migration - DBDeploy](5/5.2.2.2.md) ![NOT DONE](images/red.png)

        * [5.2.2.3 Backup](5/5.2.2.3.md) ![NOT DONE](images/red.png)

    * [5.2.3 Material Polling](5/5.2.3.md) ![NOT DONE](images/red.png)

        * [5.2.3.1 Material Fingerprint & Flyweights](5/5.2.3.1.md) ![NOT DONE](images/red.png)

        * [5.2.3.2 Supported Materials](5/5.2.3.2.md) ![NOT DONE](images/red.png)

    * [5.2.4 Build Cause Production](5/5.2.4.md) ![NOT DONE](images/red.png)

    * [5.2.5 Pipeline Scheduling](5/5.2.5.md) ![NOT DONE](images/red.png)

    * [5.2.6 Work Assignment](5/5.2.6.md) ![NOT DONE](images/red.png)

        * [5.2.6.1 Resource & Environment Mapping](5/5.2.6.1.md) ![NOT DONE](images/red.png)

    * [5.2.7 Artifact Management](5/5.2.7.md) ![NOT DONE](images/red.png)

    * [5.2.8 User Management](5/5.2.8.md) ![NOT DONE](images/red.png)

        * [5.2.8.1 Authentication Management](5/5.2.8.1.md) ![NOT DONE](images/red.png)

        * [5.2.8.2 Enable, disable & delete users](5/5.2.8.2.md) ![NOT DONE](images/red.png)

        * [5.2.8.3 User Role Management](5/5.2.8.3.md) ![NOT DONE](images/red.png)

    * [5.2.9 Agent Management](5/5.2.9.md) ![NOT DONE](images/red.png)

    * [5.2.10 UI Architecture](5/5.2.10.md) ![IN PROGRESS](images/yellow.png)

    * [5.2.11 APIs, CCTray & Feeds](5/5.2.11.md) ![NOT DONE](images/red.png)

* [5.3 Go Agent](5/5.3.md) ![NOT DONE](images/red.png)

    * [5.3.1 Bootstrapper](5/5.3.1.md) ![NOT DONE](images/red.png)

    * [5.3.2 Launcher](5/5.3.2.md) ![NOT DONE](images/red.png)

    * [5.3.3 Agent](5/5.3.3.md) ![NOT DONE](images/red.png)

* [5.4 Common](5/5.4.md) ![NOT DONE](images/red.png)

    * [5.4.1 Plugin Architecture](5/5.4.1.md) ![NOT DONE](images/red.png)

    * [5.4.2 Agent - Server Communication](5/5.4.2.md) ![NOT DONE](images/red.png)

* [5.5 Build Infrastructure](5/5.5.md) ![IN PROGRESS](images/yellow.png)

    * [5.5.1 Packaging](5/5.5.1.md) ![IN PROGRESS](images/yellow.png)

    * [5.5.2 Documentation Creation](5/5.5.2.md) ![IN PROGRESS](images/yellow.png)

    * [5.5.3 Installer Creation](5/5.5.3.md) ![IN PROGRESS](images/yellow.png)

        * [5.5.3.1 zip](5/5.5.3.1.md) ![IN PROGRESS](images/yellow.png)

        * [5.5.3.2 rpm](5/5.5.3.2.md) ![IN PROGRESS](images/yellow.png)

        * [5.5.3.3 deb](5/5.5.3.3.md) ![IN PROGRESS](images/yellow.png)

        * [5.5.3.4 exe](5/5.5.3.4.md) ![IN PROGRESS](images/yellow.png)

        * [5.5.3.5 mac](5/5.5.3.5.md) ![IN PROGRESS](images/yellow.png)

        * [5.5.3.6 sol](5/5.5.3.6.md) ![IN PROGRESS](images/yellow.png)

#### 6. Features

* [6.1 Dashboard](6/6.1.md) ![NOT DONE](images/red.png)

    * [6.1.1 Overview](6/6.1.1.md) ![NOT DONE](images/red.png)

    * [6.1.2 All Active Pipelines](6/6.1.2.md) ![NOT DONE](images/red.png)

* [6.2 Fan-in](6/6.2.md) ![NOT DONE](images/red.png)

    * [6.2.1 Overview](6/6.2.1.md) ![NOT DONE](images/red.png)

    * [6.2.2 Pipeline Timeline](6/6.2.2.md) ![NOT DONE](images/red.png)

    * [6.2.3 Corner Cases](6/6.2.3.md) ![NOT DONE](images/red.png)

* [6.3 Value Stream Map](6/6.3.md) ![NOT DONE](images/red.png)

    * [6.3.1 Overview](6/6.3.1.md) ![NOT DONE](images/red.png)

    * [6.3.2 Layer Assignment ](6/6.3.2.md) ![NOT DONE](images/red.png)

    * [6.3.3 Dummy Node Creation   ](6/6.3.3.md) ![NOT DONE](images/red.png)

    * [6.3.4 Edge Cross Minimisation   ](6/6.3.4.md) ![NOT DONE](images/red.png)

    * [6.3.5 Optimisation](6/6.3.5.md) ![NOT DONE](images/red.png)

* [6.4 Compare Pipeline](6/6.4.md) ![IN PROGRESS](images/yellow.png)

    * [6.4.1 Overview](6/6.4.1.md) ![NOT DONE](images/red.png)

    * [6.4.2 Corner Cases](6/6.4.2.md) ![NOT DONE](images/red.png)

* [6.5 PackageRepository](6/6.5.md) ![NOT DONE](images/red.png)

    * [6.5.1 Overview](6/6.5.1.md) ![NOT DONE](images/red.png)

    * [6.5.2 Plugins](6/6.5.2.md) ![NOT DONE](images/red.png)

* [6.6 Command Repository](6/6.6.md) ![NOT DONE](images/red.png)

* [6.7 Environments](6/6.7.md) ![NOT DONE](images/red.png)

* [6.8 Templates](6/6.8.md) ![NOT DONE](images/red.png)

* [6.9 Shine](6/6.9.md) ![NOT DONE](images/red.png)

    * [6.9.1 Test Artifact Parser](6/6.9.1.md) ![NOT DONE](images/red.png)

    * [6.9.2 Reporting](6/6.9.2.md) ![NOT DONE](images/red.png)

    * [6.9.3 Stage Graph](6/6.9.3.md) ![NOT DONE](images/red.png)

* [6.10 OAuth Gadgets](6/6.10.md) ![NOT DONE](images/red.png)

* [6.11 Backup](6/6.11.md) ![NOT DONE](images/red.png)

#### 7. CD in practice

* [7.1 Build Go Using Go](7/7.1.md) ![NOT DONE](images/red.png)

* [7.2 Test Infrastructure](7/7.2.md) ![NOT DONE](images/red.png)

    * [7.2.1 Unit & Integration Tests](7/7.2.1.md) ![NOT DONE](images/red.png)

    * [7.2.2 jsunit tests](7/7.2.2.md) ![NOT DONE](images/red.png)

    * [7.2.3 Acceptance Tests](7/7.2.3.md) ![NOT DONE](images/red.png)

    * [7.2.4 Test Parallelization](7/7.2.4.md) ![NOT DONE](images/red.png)

* [7.3 Continuous Deployment](7/7.3.md) ![NOT DONE](images/red.png)

#### 8. Conclusion
