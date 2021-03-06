[![Build status](https://ci.appveyor.com/api/projects/status/3tnqdrpd8f6gfmp5?retina=true)](https://ci.appveyor.com/project/Marknumskull/azert-pipeline)

[![NuGet](https://img.shields.io/nuget/dt/Azert.Pipeline.Synchronous.svg)](https://www.nuget.org/packages/Azert.Pipeline.Synchronous/)
[![NuGet](https://img.shields.io/nuget/v/Azert.Pipeline.Synchronous.svg)](https://www.nuget.org/packages/Azert.Pipeline.Synchronous/)
# Azert.Pipeline

A simple synchronous pipeline utilising the pipes and filters pattern, similar to that described here https://msdn.microsoft.com/en-gb/library/dn568100.aspx

This contains a pipeline contract as well as implementation which you can use in your projects.

Incldued is an IFilter contract. This should be implemented for each stage (filter) of your pipeline process. Each filter should then be registered with the pipeline, usually at application start.

To get a better understanding of how to use the library, check the projects in the examples folder of this repo.

There is also a nuget package available for this to easily consume in your applications https://www.nuget.org/packages/Azert.Pipeline.Synchronous/
