# Awesome .NET
A curated collection of awesome .NET libraries, tools, frameworks, and software.

Inspired by [awesome-python](https://github.com/vinta/awesome-python) and [awesome-go](https://raw.githubusercontent.com/avelino/awesome-go).

:m: - Indicates a project maintained by Microsoft.

## Contents

Add ToC

**[⬆ back to top](#contents)**

## Caching

- [CacheManager](https://cachemanager.michaco.net/) - CacheManager is an open-source caching abstraction layer for .NET written in C#.
- [Microsoft.Extensions.Caching](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/memory?view=aspnetcore-6.0) - Microsoft.Extensions.Caching is a simple in-memory cache for .NET.
- 

## Command Line

### Advanced Console UIs

- [Spectre.Console](https://spectreconsole.net/) - A .NET library that makes it easier to create beautiful console applications.
- [Colorful.Console](https://github.com/tomakita/Colorful.Console) - Colorful.Console is a C# library that wraps around the System.Console class, exposing enhanced styling functionality.

**[⬆ back to top](#contents)**

### Standard CLI

- :m: [System.CommandLine](https://learn.microsoft.com/en-us/dotnet/standard/commandline/) - The System.CommandLine library provides functionality such as parsing the command-line input and displaying help text.

**[⬆ back to top](#contents)**

## Database Drivers

### Relational Database Drivers
- [BigQuery](https://cloud.google.com/dotnet/docs/reference/Google.Cloud.BigQuery.V2/latest) - Google BigQuery ADO.NET Data provider. 
- [DuckDB.NET](https://github.com/Giorgi/DuckDB.NET) - DuckDB.NET is a .NET wrapper for the DuckDB in-memory database.
- [FirebirdSql.Data.FirebirdClient](https://www.nuget.org/packages/FirebirdSql.Data.FirebirdClient/) - Firebird ADO.NET Data provider.
- [MySql.Data](https://dev.mysql.com/doc/connector-net/en/) - MySQL Connector/NET enables .NET developers to create database applications using MySQL. 
- [NPgsql](https://www.npgsql.org/) - Npgsql is the .NET data provider for PostgreSQL.
- [SQLite-net](https://github.com/praeclarum/sqlite-net) - SQLite-net is an open source, minimal library to allow .NET applications to store data in SQLite 3 databases.
- [System.Data.SQLite](https://system.data.sqlite.org/index.html/doc/trunk/www/index.wiki) - System.Data.SQLite is an ADO.NET provider for SQLite.  
- :m: [System.Data.SqlClient](https://docs.microsoft.com/en-us/dotnet/api/system.data.sqlclient?view=net-6.0) - System.Data.SqlClient is the .NET data provider for SQL Server.

### NoSQL Database Drivers
- [StackExchange.Redis](https://stackexchange.github.io/StackExchange.Redis/) - High performance Redis client, incorporating both synchronous and asynchronous usage.
- [MongoDB.Driver](https://mongodb.github.io/mongo-csharp-driver/) - The official .NET driver for MongoDB.

**[⬆ back to top](#contents)**

## Dependency Injection
- [Autofac](https://autofac.org/) - Autofac is an .NET IoC container.

**[⬆ back to top](#contents)**

## Distributed Systems
- [Polly](https://github.com/App-vNext/Polly) - Polly is a .NET resilience and transient-fault-handling library.

**[⬆ back to top](#contents)**

## File Handling\
- [SharpZipLib](https://github.com/icsharpcode/SharpZipLib) - SharpZipLib is a Zip, GZip, Tar, and BZip2 library written entirely in C# for the .NET platform.
- [SharpCompress](https://github.com/adamhathcock/sharpcompress) - SharpCompress is a compression library for .NET Standard 2.0 that can unrar, unzip, and untar.

**[⬆ back to top](#contents)**

## HTTP Clients
- [RestSharp](https://restsharp.dev/) - RestSharp is a simple REST and HTTP API Client for .NET.

**[⬆ back to top](#contents)**

## Job Scheduling
- [Hangfire](https://www.hangfire.io/) - Hangfire is an easy way to perform fire-and-forget, delayed, and recurring tasks inside ASP.NET applications.

**[⬆ back to top](#contents)**

## Logging
- [log4net](https://logging.apache.org/log4net/) - log4net is a tool to help the programmer output log statements to a variety of output targets.
- [NLog](https://nlog-project.org/) - NLog is a free logging platform for .NET with rich log routing and management capabilities.
- [OpenTelemetry](https://opentelemetry.io/docs/languages/net/) - OpenTelemetry is a set of APIs, libraries, agents, and instrumentation to provide observability for your applications.
- [Sentry.Extensions.Logging](https://docs.sentry.io/platforms/dotnet/) - Official Microsoft.Extensions.Logging integration for Sentry.
- [Serilog](https://serilog.net/) - Serilog is a diagnostic logging library for .NET applications.
- :m: [System.Diagnostics.EventLog](https://www.nuget.org/packages/System.Diagnostics.EventLog) - System.Diagnostics.EventLog is a .NET library for logging to the Windows Event Log.

**[⬆ back to top](#contents)**

## Messaging
- :m: [Microsoft.Azure.Amqp](https://www.nuget.org/packages/Microsoft.Azure.Amqp) - Microsoft.Azure.Amqp is a .NET library for AMQP.
- [MassTransit](https://masstransit-project.com/) - MassTransit is a free, open-source distributed application framework for .NET.
- [MediatR]() - Simple, unambitious mediator implementation in .NET
- [RabbitMQ.Client](https://www.rabbitmq.com/dotnet.html) - RabbitMQ.Client is the .NET client for RabbitMQ.

**[⬆ back to top](#contents)**

## Metrics
- [App Metrics](https://www.app-metrics.io/) - App Metrics is an open-source and cross-platform .NET library used to record metrics within an application.
- [OpenTelemetry](https://opentelemetry.io/docs/languages/net/) - OpenTelemetry is a set of APIs, libraries, agents, and instrumentation to provide observability for your applications.

**[⬆ back to top](#contents)**

## Mocking
- [Moq](https://github.com/devlooped/moq) - Moq is the most popular and friendly mocking framework for .NET.

**[⬆ back to top](#contents)**

## Networking
- [DnsClient](https://dnsclient.michaco.net/) - DnsClient is a simple yet very powerful and high-performance open-source library to do DNS lookups in .NET.

**[⬆ back to top](#contents)**

## ORM
_Object relational mapping (ORM) libraries that provide a high-level abstraction for interacting with databases._

- :m: [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/) - Entity Framework Core is a modern object-database mapper for .NET.
- [Dapper](https://dapper-tutorial.net/) - Dapper is a simple object mapper for .NET and owns the title of King of Micro ORM in terms of speed.

**[⬆ back to top](#contents)**

## RPC
- [gRPC](https://grpc.io/) - gRPC is a high-performance, open-source universal RPC framework.

**[⬆ back to top](#contents)**

## Security
- [BouncyCastle.Cryptography](https://www.nuget.org/packages/BouncyCastle.Cryptography/) - BouncyCastle.NET is a popular cryptography library for .NET

**[⬆ back to top](#contents)**

## Serialization
_Libraries and tools for binary serialization._

- [Google.Protobuf](https://github.com/protocolbuffers/protobuf/tree/main/csharp) - Google's Protocol Buffers is a language-neutral, platform-neutral extensible mechanism for serializing structured data.
- [MongoDB.Bson](https://mongodb.github.io/mongo-csharp-driver/) - MongoDB.Bson is a .NET library for BSON serialization.
- [Parquet.NET](https://github.com/aloneguid/parquet-dotnet) - Parquet.NET is a .NET library to read and write Apache Parquet files.
- :m: [System.Formats.Asn1](https://www.nuget.org/packages/System.Formats.Asn1) - System.Formats.Asn1 is a .NET library for encoding and decoding Abstract Syntax Notation One (ASN.1) data.

**[⬆ back to top](#contents)**

## Testing
- [AutoFixture](https://github.com/AutoFixture/AutoFixture) - AutoFixture is an open-source library for .NET designed to minimize the 'Arrange' phase of your unit tests.
- [FluentAssertions](https://fluentassertions.com/) - FluentAssertions is a set of .NET extension methods that allow you to more naturally specify the expected outcome of a test.
- [NUnit](https://nunit.org/) - NUnit is a unit-testing framework for all .Net languages.
- [SpecFlow](https://specflow.org/) - SpecFlow is the #1 .NET open source framework for Behavior-Driven Development, Acceptance Test-Driven Development, and Specification by Example.
- [xUnit](https://xunit.net/) - xUnit.net is a free, open-source, community-focused unit testing tool for the .NET Framework.

**[⬆ back to top](#contents)**

## Text Processing
- [CsvHelper](https://joshclose.github.io/CsvHelper/) - CsvHelper is a library to help read and write CSV files.
- [HtmlAgilityPack](https://html-agility-pack.net/) - HtmlAgilityPack is an HTML parser library for .NET.
- [Json.NET](https://www.newtonsoft.com/json) - Json.NET is a popular high-performance JSON framework for .NET.
- :m: [System.Text.Json](https://docs.microsoft.com/en-us/dotnet/api/system.text.json?view=net-6.0) - System.Text.Json is a high-performance JSON framework for .NET.
- [YamlDotNet](https://github.com/aaubry/YamlDotNet) - YamlDotNet is a .NET library for YAML.

**[⬆ back to top](#contents)**

## Tracing
- [OpenTelemetry](https://opentelemetry.io/docs/languages/net/) - OpenTelemetry is a set of APIs, libraries, agents, and instrumentation to provide observability for your applications.

**[⬆ back to top](#contents)**

## Utility
- [AutoMapper](https://automapper.org/) - AutoMapper is a simple library that allows you to map objects in .NET.

**[⬆ back to top](#contents)**

## Validation
- [FluentValidation](https://fluentvalidation.net/) - A popular .NET library for building strongly-typed validation rules.

**[⬆ back to top](#contents)**