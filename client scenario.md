# Client Scenario

Applying DevOps for Product Development in Medical Devices 

While the example is taken from the real world, the company names and products are made up for the purpose of this example.

---

Client Profile 

acmeHealthElectonics develops advanced sensor technologies and AI-powered digital health solutions that can assist healthcare professionals and empower patients to achieve better outcomes.

A leader in providing a broad range of diagnostics and information technology-based products and services. 

Its flagship product is Respiro, a connected platform that offers connected devices, applications and analytics to upgrade respiratory care.


Business Challenge 
The client was facing issues with multi project builds, release management, dependency management and virtual environment setup using existing tools for one of their product lines. 

Solution 
eInfochips, as a solution partner, was involved in product testing, including for unit testing, web testing and automation of 250+ test cases using a well-defined framework. eInfochips, with its DevOps tools evaluation expertise, enabled migration to DevOps tools to carry out smooth build and release implementation. 
•	Hardware boards for the product were based on Catone using C++ and Snap! Pro using Java programming. 
•	CMake was used for build management which was not suitable for combinations of different platforms, third party libraries/packages and OS components. 
•	There was a need for a tool that could save application build time by having pre–built packages and managing remote dependencies. 
•	Due to over-usage of various tools, the build system with CMake, Puppet, Docker, Jenkins, Bash, Groovy etc. was particularly, not very portable. 
• Hence, build and configuration management was migrated to Gradle based on Apache Ivy solving multi project dependency, on open source and with native C++ support. 
•	Continuous integration was enabled by Jenkins to verify code changes every night. 
•	Vagrant, used for virtual environment management, was not able to handle large file sizes of 10GB. Hence, Docker was used to manage the development of virtualization environment. 

Tools and Technologies 
• Jenkins, Docker, Vagrant, CMake, Gradle, Puppet, ANT, Selenium, CxxTest, Coverity, Lua Scripts, Python 

Client Benefits 
eInfochips’ DevOps tools migration and implementation enabled file size reduction by 70% (from 10GB to 3GB) enabling faster testing and reduced release implementation time.
