# Awesome .NET Core with stars

Inspired by [awesome](https://github.com/sindresorhus/awesome) ⭐ 497,571 | 🐛 102 | 📅 2026-08-18, [awesome-dotnet](https://github.com/quozd/awesome-dotnet) ⭐ 21,561 | 🐛 139 | 📅 2026-03-26,  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) ⭐ 66,556 | 🐛 26 | 📅 2026-05-03, [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) ⭐ 47,393 | 🐛 133 | 📅 2024-05-21.

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/thangchung/awesome-dotnet-core/blob/master/contributing.md) ⭐ 21,363 | 🐛 212 | 🌐 C# | 📅 2026-02-27 pages first. We accept proprietary and commercial software too.

Thanks to all [contributors](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors) ⭐ 21,363 | 🐛 212 | 🌐 C# | 📅 2026-02-27, you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

Check out my [blog](https://dev.to/thangchung) or say hi on [Twitter](https://twitter.com/thangchung)!

## Contents

* [General](#general)
* [Frameworks, Libraries and Tools](#frameworks-libraries-and-tools)
  * [API](#api)
  * [Application Frameworks](#application-frameworks)
  * [Application Templates](#application-templates)
  * [Authentication and Authorization](#authentication-and-authorization)
  * [Blockchain](#blockchain)
  * [Bot](#bot)
  * [Build Automation](#build-automation)
  * [Bundling and Minification](#bundling-and-minification)
  * [Caching](#caching)
  * [CMS](#cms)
  * [Code Analysis and Metrics](#code-analysis-and-metrics)
  * [Compression](#compression)
  * [Compilers, Transpilers and Languages](#compilers-transpilers-and-languages)
  * [Cryptography](#cryptography)
  * [Database](#database)
  * [Database Drivers](#database-drivers)
  * [Database Tools and Utilities](#database-tools-and-utilities)
  * [Date and Time](#date-and-time)
  * [Distributed Computing](#distributed-computing)
  * [E-Commerce and Payments](#e-commerce-and-payments)
  * [Exceptions](#exceptions)
  * [Functional Programming](#functional-programming)
  * [Graphics](#graphics)
  * [GUI](#gui)
  * [IDE](#ide)
  * [Internationalization](#internationalization)
  * [IOC](#ioc)
  * [Logging](#logging)
  * [Machine Learning and Data Science](#machine-learning-and-data-science)
  * [Mail](#mail)
  * [Mathematics](#mathematics)
  * [Media](#media)
  * [Networking](#networking)
  * [Misc](#misc)
  * [Office](#office)
  * [ORM](#orm)
  * [Profiling](#profiling)
  * [Queue and Messaging](#queue-and-messaging)
  * [Query Builders](#query-builders)
  * [Scheduler and Job](#scheduler-and-job)
  * [SDKs](#sdks)
  * [Security](#security)
  * [Searching](#searching)
  * [Serialization](#serialization)
  * [Template Engine](#template-engine)
  * [Testing](#testing)
  * [Tools](#tools)
  * [Web Framework](#web-framework)
  * [Web Socket](#web-socket)
  * [Windows Service](#windows-service)
  * [Workflow](#workflow)
* [Roadmaps](#roadmaps)
* [Starter Kits](#starter-kits)
* [Sample Projects](#sample-projects)
* [Articles](#articles)
* [Books](#books)
* [Videos](#videos)
* [Podcasts](#podcasts)
* [Community](#community)

## General

* [.NET Core SDK](https://www.microsoft.com/net/core) - .NET Core SDK is a general purpose development platform maintained by Microsoft and the .NET community on [GitHub](https://github.com/dotnet/core) ⭐ 22,032 | 🐛 350 | 🌐 PowerShell | 📅 2026-08-19.
* [.NET Platform Standard](https://github.com/dotnet/corefx/blob/1719a3fe2a5c81b67a4909787da4a02fb0d0d419/Documentation/architecture/net-platform-standard.md) ⚠️ Archived - The different between the old version and the new version of .NET.
* [Clean Code .NET/.NET Core](https://github.com/thangchung/clean-code-dotnet) ⭐ 7,723 | 🐛 46 | 🌐 C# | 📅 2026-02-27 - Clean Code concepts adapted for .NET / .NET Core.
* [ASP.NET Core Documentation](https://docs.asp.net/en/latest/) - The official ASP.NET Core documentation site.
* [.NET Core Documentation](https://docs.microsoft.com/en-us/dotnet/articles/welcome) - Home of the technical documentation for .NET Core, C#, F# and Visual Basic, including basic concepts, getting started instructions, tutorials and samples.
* [Introducing .NET Standard 2.0](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) - The description of what will be going on for .NET Standard 2.0 and the roadmap for some missing parts of the current .NET Standard.

## Frameworks, Libraries and Tools

### API

* [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) ⭐ 26,679 | 🐛 5,711 | 🌐 Java | 📅 2026-08-19 - OpenAPI Generator allows generation of API client libraries (e.g. C#, TypeScript, etc), server stubs (ASP.NET Core, NancyFx, etc), documentation and configuration automatically given an OpenAPI Spec (v2, v3).
* [Restsharp](https://github.com/restsharp/RestSharp) ⭐ 9,822 | 🐛 39 | 🌐 C# | 📅 2026-06-02 - Simple REST and HTTP API Client for .NET
* [NSwag](https://github.com/RSuter/NSwag) ⭐ 7,358 | 🐛 2,054 | 🌐 C# | 📅 2026-06-21 - The Swagger/OpenAPI toolchain for .NET, Web API and TypeScript. <http://NSwag.org>.
* [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) ⭐ 5,495 | 🐛 175 | 🌐 C# | 📅 2026-08-12 - Seamlessly adds a swagger to WebApi projects.
  * [Swashbuckle.AspNetCore.Filters](https://github.com/mattfrear/Swashbuckle.AspNetCore.Filters) ⭐ 441 | 🐛 21 | 🌐 C# | 📅 2025-11-24 - A bunch of useful filters for Swashbuckle.AspNetCore.
  * [MicroElements.Swashbuckle.FluentValidation](https://github.com/micro-elements/MicroElements.Swashbuckle.FluentValidation) ⭐ 396 | 🐛 28 | 🌐 C# | 📅 2026-07-13 - Adds FluentValidation rules to swagger.
* [autorest](https://github.com/Azure/autorest) ⭐ 4,799 | 🐛 22 | 🌐 TypeSpec | 📅 2026-08-12 - Swagger (OpenAPI) Specification code generator featuring C# and Razor templates. Supports C#, Java, Node.js, TypeScript, Python and Ruby. `4.5.x or above`
* [Flurl](https://github.com/tmenier/Flurl) ⭐ 4,403 | 🐛 64 | 🌐 C# | 📅 2025-01-01 - Fluent URL builder and testable HTTP for .NET <https://flurl.dev>.
* [aspnet-api-versioning](https://github.com/Microsoft/aspnet-api-versioning) ⭐ 3,205 | 🐛 8 | 🌐 C# | 📅 2026-08-12 - set of libraries which add service API versioning to ASP.NET Web API, OData with ASP.NET Web API, and ASP.NET Core.
* [AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit) ⭐ 3,173 | 🐛 185 | 🌐 C# | 📅 2024-07-26 - ASP.NET Core rate limiting middleware.
* [RestEase](https://github.com/canton7/RestEase) ⭐ 1,116 | 🐛 15 | 🌐 C# | 📅 2023-12-10 - Easy-to-use typesafe REST API client library, which is simple and customisable.
* [OData](https://github.com/OData/WebApi/tree/feature/netcore) ⭐ 864 | 🐛 635 | 🌐 C# | 📅 2026-07-28 - The Open Data Protocol (OData) enables the creation of HTTP-based data services, which allow resources identified using Uniform Resource Identifiers (URIs) and defined in an abstract data model, to be published and edited by Web clients using simple HTTP messages.
* [JSON API .NET Core](https://github.com/Research-Institute/json-api-dotnet-core) ⭐ 715 | 🐛 22 | 🌐 C# | 📅 2026-08-19 - Framework for building json:api compliant APIs with the goal of eliminating RESTful boilerplate.
* [Restier](https://github.com/OData/RESTier) ⭐ 480 | 🐛 34 | 🌐 C# | 📅 2026-05-01 - RESTier is a RESTful API development framework for building standardized, OData V4 based RESTful services on .NET platform.
* [WebAPIContrib for ASP.NET CORE](https://github.com/WebApiContrib/WebAPIContrib.Core) ⭐ 461 | 🐛 56 | 🌐 C# | 📅 2023-02-09 - Community Contributions for ASP.NET Core.
* [RestClient.Net](https://github.com/MelbourneDeveloper/RestClient.Net) ⭐ 404 | 🐛 8 | 🌐 C# | 📅 2026-01-27 - Cross Platform REST Client for all C# platforms
* [LightNode](https://github.com/neuecc/LightNode) ⚠️ Archived - Micro RPC/REST Framework built on OWIN <http://neuecc.github.io/LightNode>.
* [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet) ⭐ 165 | 🐛 14 | 🌐 C# | 📅 2022-12-08 - API Condenser / Reverse Proxy using Kestrel and Consul, Including light weight consul library.
* [RestLess](https://github.com/letsar/RestLess) ⭐ 112 | 🐛 8 | 🌐 C# | 📅 2022-12-07 - The automatic type-safe-reflectionless REST API client library for .Net Standard.
* [halcyon](https://github.com/visualeyes/halcyon) ⭐ 81 | 🐛 15 | 🌐 C# | 📅 2018-10-07 - HAL implementation for ASP.NET.
* [NetCoreStack.Proxy](https://github.com/NetCoreStack/Proxy) ⭐ 42 | 🐛 0 | 🌐 C# | 📅 2023-10-10 - The type-safe, distributed REST library for .NET Standard 2.0 (NetCoreStack Flying Proxy)
* [WebAnchor](https://github.com/mattiasnordqvist/Web-Anchor) ⭐ 25 | 🐛 22 | 🌐 C# | 📅 2025-08-15 - Web Anchor provides type-safe, testable and flexible, runtime-generated access to web resources.
* [refit](https://github.com/paulcbetts/refit) ⭐ 0 | 🐛 0 | 📅 2025-08-09 - The automatic type-safe REST library for Xamarin and .NET.
* GraphQL
  * [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) ⭐ 5,992 | 🐛 134 | 🌐 C# | 📅 2026-08-18 - GraphQL for .NET.
  * [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) ⭐ 5,751 | 🐛 379 | 🌐 C# | 📅 2026-08-19 - GraphQL server for .Net Core and .NET Framework.
  * [graphql-dotnet-server](https://github.com/graphql-dotnet/server) ⭐ 604 | 🐛 23 | 🌐 C# | 📅 2026-08-03 - GraphQL for .NET - Subscription Transport WebSockets.
  * [FSharp.Data.GraphQL](https://github.com/fsprojects/FSharp.Data.GraphQL) ⭐ 409 | 🐛 87 | 🌐 F# | 📅 2026-08-13 - FSharp implementation of Facebook GraphQL query language <https://fsprojects.github.io/FSharp.Data.GraphQL>.
  * [Dapper.GraphQL](https://github.com/landmarkhw/Dapper.GraphQL) ⭐ 298 | 🐛 12 | 🌐 C# | 📅 2024-05-10 - A library designed to integrate the Dapper and graphql-dotnet projects with ease-of-use in mind and performance as the primary concern.
  * [graphql-convention](https://github.com/graphql-dotnet/conventions) ⭐ 230 | 🐛 15 | 🌐 C# | 📅 2026-03-16 - This library is a complementary layer on top that allows you to automatically wrap your .NET classes into GraphQL schema definitions using existing property getters and methods as field resolvers
  * [parser](https://github.com/graphql-dotnet/parser) ⭐ 219 | 🐛 9 | 🌐 C# | 📅 2026-04-10 - A lexer and parser for GraphQL in .NET.
  * [graphql-aspnetcore](https://github.com/JuergenGutsch/graphql-aspnetcore) ⚠️ Archived - ASP.NET Core MiddleWare to create a GraphQL end-point.
  * [graphiql-dotnet](https://github.com/JosephWoodward/graphiql-dotnet) ⭐ 138 | 🐛 14 | 🌐 CSS | 📅 2020-03-27 - GraphiQL middleware for ASP.NET Core.
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) ⚠️ Archived - GraphQL for .NET Core based on <https://github.com/graphql/graphql-js> ⭐ 20,343 | 🐛 97 | 🌐 TypeScript | 📅 2026-08-18.
  * [tanka-graphql](https://github.com/pekkah/tanka-graphql) ⭐ 63 | 🐛 12 | 🌐 C# | 📅 2026-07-10 - GraphQL execution and server libraries supporting SignalR, Apollo, schema manipulation and other features familiar from Apollo and graphql-js

### Application Frameworks

* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp) ⭐ 45,230 | 🐛 1,373 | 🌐 C++ | 📅 2026-08-19 - Remote Procedure Calls (RPCs) provide a useful abstraction for building distributed applications and services. The libraries in this repository provide a concrete implementation of the gRPC protocol, layered over HTTP/2. These libraries enable communication between clients and servers using any combination of the supported languages.
* [ASP.NET MVC](https://github.com/dotnet/aspnetcore/tree/master/src/Mvc) ⭐ 38,375 | 🐛 4,108 | 🌐 C# | 📅 2026-08-19 - Model view controller framework for building dynamic web sites with clean separation of concerns, including the merged MVC, Web API, and Web Pages w/ Razor.
* [Abp vNext](https://github.com/abpframework/abp) ⭐ 14,407 | 🐛 325 | 🌐 C# | 📅 2026-08-19 - Abp vNext is the next generation of the open source [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) ⭐ 12,002 | 🐛 64 | 🌐 C# | 📅 2026-07-28 framework. It's a complete architecture and strong infrastructure to create modern web applications!
  Follows best practices and conventions to provide you a SOLID development experience.
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) ⭐ 12,002 | 🐛 64 | 🌐 C# | 📅 2026-07-28 - ASP.NET Boilerplate is a general purpose application framework especially designed for new modern web applications. It uses already familiar tools and implements best practices around them to provide you a SOLID development experience.
* [orleans](https://github.com/dotnet/orleans) ⭐ 10,835 | 🐛 652 | 🌐 C# | 📅 2026-08-19 - Framework that provides a straight-forward approach to building distributed high-scale computing applications, without the need to learn and apply complex concurrency or other scaling patterns.
* [fission](https://github.com/fission/fission) ⭐ 8,902 | 🐛 56 | 🌐 Go | 📅 2026-08-18 - Fast Serverless Functions for Kubernetes.
* [MassTransit](https://github.com/MassTransit/MassTransit) ⭐ 7,797 | 🐛 1 | 🌐 C# | 📅 2026-06-04 - Distributed Application Framework for .NET.
* [ElectronNET](https://github.com/ElectronNET/Electron.NET) ⭐ 7,603 | 🐛 20 | 🌐 C# | 📅 2026-08-14 - Build cross platform desktop apps with ASP.NET NET Core.
* [CAP](https://github.com/dotnetcore/CAP) ⭐ 7,105 | 🐛 8 | 🌐 C# | 📅 2026-08-01 - An EventBus with local persistent message functionality for system integration in SOA or Microservice architecture.
* [Nancy](https://github.com/NancyFx/Nancy) ⚠️ Archived - Lightweight, low-ceremony, framework for building HTTP based services on .NET and Mono.
* [Prism](https://github.com/PrismLibrary/Prism) ⭐ 6,832 | 🐛 27 | 🌐 C# | 📅 2026-08-06 - Prism is a framework for building loosely coupled, maintainable, and testable XAML applications in WPF, Windows 10 UWP, and Xamarin Forms.
* [opencvsharp](https://github.com/shimat/opencvsharp) ⭐ 6,065 | 🐛 9 | 🌐 C# | 📅 2026-08-19 - .NET Framework wrapper for OpenCV.
* [ServiceStack](https://github.com/ServiceStack/ServiceStack) ⭐ 5,500 | 🐛 35 | 🌐 C# | 📅 2026-08-18 - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all <https://servicestack.net>.
* [akka.net](https://github.com/akkadotnet/akka.net) ⭐ 5,076 | 🐛 461 | 🌐 C# | 📅 2026-08-11 - Toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono.
* [MagicOnion](https://github.com/neuecc/MagicOnion) ⭐ 4,440 | 🐛 9 | 🌐 C# | 📅 2026-08-14 - gRPC based HTTP/2 RPC Streaming Framework for .NET, .NET Core and Unity.
* [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) ⭐ 4,405 | 🐛 34 | 🌐 C# | 📅 2026-07-06 - Lightweight and fast library written in C# for reading Microsoft Excel files.
* [DotNetty](https://github.com/Azure/DotNetty) ⭐ 4,251 | 🐛 174 | 🌐 C# | 📅 2026-01-12 - Port of netty, event-driven asynchronous network application framework.
* [DotnetSpider](https://github.com/dotnetcore/DotnetSpider) ⭐ 4,139 | 🐛 6 | 🌐 C# | 📅 2026-04-03 - DotnetSpider, a .NET Standard web crawling library similar to WebMagic and Scrapy. It is a lightweight ,efficient and fast high-level web crawling & scraping framework for .NET.
* [MoreLINQ](https://github.com/morelinq/MoreLINQ) ⭐ 3,834 | 🐛 109 | 🌐 C# | 📅 2025-11-25 - Extensions to LINQ to Objects.
* [AsyncEx](https://github.com/StephenCleary/AsyncEx) ⭐ 3,723 | 🐛 70 | 🌐 C# | 📅 2024-01-01 - A helper library for async/await.
* [surging](https://github.com/dotnetcore/surging) ⭐ 3,263 | 🐛 255 | 🌐 C# | 📅 2026-04-10 - Surging is a micro-service engine that provides a lightweight, high-performance, modular RPC request pipeline. The service engine supports http, TCP, WS, Mqtt, UDP, and DNS protocols. It uses ZooKeeper and Consul as a registry,  Hash Algorithms, random, polling, pressure minimum priority as a load balancing algorithm, built-in service governance to ensure reliable RPC communication.
* [Chromely](https://github.com/mattkol/Chromely) ⚠️ Archived - Lightweight Alternative to Electron.NET, Electron for .NET/.NET Core.
* [EventFlow](https://github.com/eventflow/EventFlow) ⭐ 2,565 | 🐛 13 | 🌐 C# | 📅 2026-07-31 - Async/await first CQRS+ES and DDD framework for .NET.
* [Carter](https://github.com/CarterCommunity/Carter) ⭐ 2,445 | 🐛 5 | 🌐 C# | 📅 2026-07-04 - Carter is a library that allows Nancy-esque routing for use with ASP.Net Core.
* [protoactor-dotnet](https://github.com/AsynkronIT/protoactor-dotnet) ⭐ 1,894 | 🐛 23 | 🌐 C# | 📅 2026-03-13 - Ultra fast distributed actors for Golang and C# <http://proto.actor>.
* [DotNetCorePlugins](https://github.com/natemcmaster/DotNetCorePlugins) ⭐ 1,819 | 🐛 4 | 🌐 C# | 📅 2026-03-16 - .NET Core library for loading assemblies as a plugin.
* [Finbuckle.MultiTenant](https://github.com/Finbuckle/Finbuckle.MultiTenant) ⭐ 1,617 | 🐛 30 | 🌐 C# | 📅 2026-08-18 - Finbuckle.MultiTenant is a .NET Standard library for multitenant support designed for ASP.NET 2.0+. It provides functionality for tenant resolution, per-tenant app configuration, and per-tenant data isolation.
* [EmbedIO](https://github.com/unosquare/embedio) ⚠️ Archived - A tiny, cross-platform, module based web server for .NET Framework and .NET Core.
* [microdot](https://github.com/gigya/microdot) ⚠️ Archived - An open source .NET microservices framework.
* [CQRSlite](https://github.com/gautema/CQRSlite) ⭐ 1,119 | 🐛 6 | 🌐 C# | 📅 2025-11-21 - Lightweight framework for helping writing CQRS and Eventsourcing applications in C#.
* [X.PagedList](https://github.com/dncuug/X.PagedList) ⭐ 926 | 🐛 0 | 🌐 C# | 📅 2026-08-17 - Library for easily paging through any IEnumerable/IQueryable in ASP.NET/ASP.NET Core.
* [Cinchoo ETL](https://github.com/Cinchoo/ChoETL) ⭐ 859 | 🐛 77 | 🌐 C# | 📅 2026-06-20 - ETL Framework for .NET (Parser / Writer for CSV, Flat, Xml, JSON, Key-Value formatted files).
* [dotvvm](https://github.com/riganti/dotvvm) ⭐ 806 | 🐛 161 | 🌐 C# | 📅 2026-08-16 - Open source MVVM framework for Web Apps.
* [resin](https://github.com/kreeben/resin) ⭐ 577 | 🐛 4 | 🌐 C# | 📅 2026-06-12 - 16-bit wide vector space search engine with HTTP API and pluggable read/write pipelines.
* [Aeron.NET](https://github.com/AdaptiveConsulting/Aeron.NET) ⭐ 521 | 🐛 3 | 🌐 C# | 📅 2026-08-18 - Efficient reliable UDP unicast, UDP multicast, and IPC message transport - .NET port of Aeron.
* [Aggregates.NET](https://github.com/volak/Aggregates.NET) ⭐ 441 | 🐛 7 | 🌐 C# | 📅 2025-05-30 - Aggregates.NET is a framework to help developers integrate the excellent NServiceBus and EventStore libraries together.
* [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore) ⭐ 314 | 🐛 3 | 🌐 C# | 📅 2024-07-08 - Lightweight and Extensible Infrastructure for Building High Quality Web Applications Based on ASP.NET Core.
* [Butterfly Server .NET](https://github.com/firesharkstudios/butterfly-server-dotnet) ⭐ 273 | 🐛 32 | 🌐 C# | 📅 2023-01-04 - Allows building real-time web apps and native apps with minimal effort. Define a Web API and Subscription API that automatically synchronizes datasets across connected clients.
* [dataaccess\_aspnetcore](https://github.com/digipolisantwerp/dataaccess_aspnetcore) ⭐ 141 | 🐛 12 | 🌐 C# | 📅 2019-09-25 - The DataAccess Toolbox contains the base classes for data access in ASP.NET Core with Entity Framework Core 1.0 using the unit-of-work and repository pattern.
* [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) ⭐ 103 | 🐛 2 | 🌐 C# | 📅 2018-05-29 - A simple library for creating applications based on the CQRS pattern with support for attribute routing and hosted handlers. Developed in C# targeting .NET Standard 1.0.
* [Strathweb.TypedRouting.AspNetCore](https://github.com/filipw/Strathweb.TypedRouting.AspNetCore) ⭐ 75 | 🐛 9 | 🌐 C# | 📅 2019-01-22 - A library enabling strongly typed routing in ASP.NET Core MVC projects.
* [RService.io](https://github.com/Stoom/RService.IO) ⭐ 50 | 🐛 2 | 🌐 C# | 📅 2020-06-25 - ASP.Net Core RESTful microservice framework that focusing on speed and ease of use.
* [Halibut](https://github.com/OctopusDeploy/Halibut) ⭐ 24 | 🐛 52 | 🌐 C# | 📅 2026-08-18 - A secure communication stack for .NET using JSON-RPC over SSL.
* [Ether.Network](https://github.com/aloisdg/Ether.Network) ⭐ 12 | 🐛 0 | 🌐 C# | 📅 2016-11-02 - Ether.Network is an open source networking library that allow developers to create simple, fast and scalable socket server or client applications over the TCP/IP protocol.
* [ExtCore](https://github.com/ExtCore) - Free, open source and cross-platform framework for creating modular and extendable web applications based on ASP.NET Core 1.0.
* [Steeltoe OSS](https://github.com/SteelToeOSS) - .NET toolkit for common microservice patterns.

### Application Templates

* [CleanArchitecture (SPA)](https://github.com/JasonGT/CleanArchitecture) ⭐ 20,465 | 🐛 21 | 🌐 C# | 📅 2026-08-16 - Solution template for creating a Single Page App (SPA) with Angular 8 and ASP.NET Core 3 following the principles of Clean Architecture
* [CleanArchitecture](https://github.com/ardalis/CleanArchitecture) ⭐ 18,409 | 🐛 37 | 🌐 C# | 📅 2026-08-18 - A starting point for Clean Architecture with ASP.NET Core. Clean Architecture is just the latest in a series of names for the same loosely-coupled, dependency-inverted architecture. You will also find it named hexagonal, ports-and-adapters, or onion architecture.
* [.NET Boxed](https://github.com/Dotnet-Boxed/Templates) ⭐ 3,485 | 🐛 51 | 🌐 C# | 📅 2026-08-11 - Project templates with batteries included, providing the minimum amount of code required to get you going. Includes ASP.NET Core API and GraphQL Templates.
* [JavaScriptServices](https://github.com/aspnet/JavaScriptServices) ⚠️ Archived - Microsoft ASP.NET Core JavaScript Services.
* [Serenity](https://github.com/volkanceylan/Serenity) ⭐ 2,694 | 🐛 0 | 🌐 C# | 📅 2026-08-18 - Serenity is an ASP.NET MVC / TypeScript application platform designed to simplify and shorten development of data-centric business applications with a service based architecture.
* [kendo-ui-core](https://github.com/telerik/kendo-ui-core) ⭐ 2,584 | 🐛 703 | 🌐 JavaScript | 📅 2026-08-18 - An HTML5, jQuery-based widget library for building modern web apps. <http://www.telerik.com/kendo-ui>.
* [AspNetCoreSpa](https://github.com/asadsahi/AspNetCoreSpa) ⭐ 1,533 | 🐛 12 | 🌐 C# | 📅 2023-11-24 - Asp.Net Core 2+ & Angular 6 SPA with Angular CLI full featured application.
* [QuickApp](https://github.com/emonney/QuickApp) ⭐ 1,350 | 🐛 11 | 🌐 TypeScript | 📅 2026-01-03 - ASP.NET Core / Angular4 startup project template with complete login, user and role management.
* [ASP.NET-MVC-Template](https://github.com/NikolayIT/ASP.NET-MVC-Template) ⭐ 1,187 | 🐛 8 | 🌐 C# | 📅 2026-03-14 - A ready-to-use templates for ASP.NET MVC 5 and ASP.NET Core with repositories, services, models mapping and DI and StyleCop warnings fixed.
* [aspnet-core-react-template](https://github.com/bradymholt/aspnet-core-react-template) ⭐ 626 | 🐛 1 | 🌐 C# | 📅 2023-02-23 - ASP.NET Core 2.0 / React SPA Template App.
* [Angular Visual Studio Webpack Starter](https://github.com/damienbod/AngularWebpackVisualStudio) ⭐ 484 | 🐛 21 | 🌐 JavaScript | 📅 2022-12-10 - Template for Webpack, Visual Studio, ASP.NET Core and Angular. Both the client and the server side of the application are implemented inside one ASP.NET Core project which makes it easier to deploy.
* [dotnet new caju](https://github.com/ivanpaulovich/dotnet-new-caju) ⭐ 252 | 🐛 1 | 🌐 C# | 📅 2019-09-22 - dotnet new templates with awesome architecture styles! Increases productivity to design layered applications based on Hexagonal, Clean or Event Sourcing architectures styles. It supports multiple data access frameworks (MongoDB, EntityFramework, Dapper or Kafka) and it is completely testable.
* [AddFeatureFolders](https://github.com/OdeToCode/AddFeatureFolders) ⭐ 250 | 🐛 6 | 🌐 C# | 📅 2022-10-07 - Enable feature folders for MVC controllers and views in ASP.NET Core.
* [EISK](https://github.com/EISK/eisk.webapi) ⭐ 236 | 🐛 7 | 🌐 C# | 📅 2023-09-30 - Provides developer resources with simple use cases to build scalable applications on top of .NET Core with [architectural best practices](https://docs.microsoft.com/en-us/dotnet/standard/modern-web-apps-azure-architecture/common-web-application-architectures) (DDD, onion architecture etc)
* [Toucan](https://github.com/mrellipse/toucan) ⚠️ Archived - Boilerplate for building single page apps. Server is multi-project .Net Core solution designed around SOLID principles. Client is TypeScript 2, Vuejs 2, Vuex 2.
* [DNTFrameworkCoreTemplate](https://github.com/rabbal/DNTFrameworkCoreTemplate) ⚠️ Archived - Boilerplate project templates based on [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore) ⭐ 314 | 🐛 3 | 🌐 C# | 📅 2024-07-08

### Authentication and Authorization

* [openiddict](https://github.com/openiddict/openiddict-core) ⭐ 5,230 | 🐛 6 | 🌐 C# | 📅 2026-08-14 - Easy-to-use OpenID Connect server for ASP.NET Core.
  * [oidc-debugger](https://github.com/nbarbettini/oidc-debugger) ⭐ 250 | 🐛 31 | 🌐 HTML | 📅 2026-02-16 - OAuth 2.0 and OpenID Connect debugging tool.
* [Identity](https://github.com/aspnet/Identity) ⚠️ Archived - ASP.NET Core Identity is the membership system for building ASP.NET Core web applications, including membership, login, and user data.
* [Casbin.NET](https://github.com/casbin-net/Casbin.NET) ⭐ 1,331 | 🐛 7 | 🌐 C# | 📅 2026-08-15 - Authorization library that supports access control models like ACL, RBAC, ABAC in C#
* [AspNet.Security.OpenIdConnect.Server](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server) ⚠️ Archived - OpenID Connect/OAuth2 server framework for OWIN/Katana and ASP.NET Core.
* [Auth0](https://github.com/auth0/auth0.net) ⭐ 361 | 🐛 12 | 🌐 C# | 📅 2026-08-18 - Hosted, enterprise-grade platform for modern identity.
* [stuntman](https://github.com/ritterim/stuntman) ⚠️ Archived - Library for impersonating users during development leveraging ASP.NET Identity.
* [Okta](https://github.com/okta/okta-aspnet) ⭐ 104 | 🐛 1 | 🌐 C# | 📅 2026-02-19 - Hosted, enterprise-grade platform for modern identity.
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4) ⚠️ Archived - IdentityServer for ASP.NET Core 1.0 & 2.0
  * [IdentityServer4.MongoDB](https://github.com/diogodamiani/IdentityServer4.MongoDB) ⭐ 107 | 🐛 6 | 🌐 C# | 📅 2023-03-03 - MongoDB persistence layer
  * [IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) ⚠️ Archived - Entity Framework Core persistence layer
  * [IdentityServer4.EntityFramework](https://github.com/IdentityServer/IdentityServer4.EntityFramework) - EntityFramework persistence layer
  * [IdentityServer4.Templates](https://github.com/IdentityServer/IdentityServer4.Templates) - dotnet cli templates for IdentityServer4.
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) ⚠️ Archived - Build [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) ⚠️ Archived with Stormpath and ASP.NET Core.
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) ⚠️ Archived - Build [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) ⚠️ Archived with Stormpath and ASP.NET Core.(Deprecated: It will longer get updated as of March 2017 after joining OKTA)

### Blockchain

* [BTCPayServer](https://github.com/btcpayserver/btcpayserver) ⭐ 7,713 | 🐛 84 | 🌐 C# | 📅 2026-08-07 - A cross platform, self-hosted server compatible with Bitpay API.
* [NEO](https://github.com/neo-project/neo) ⭐ 3,535 | 🐛 258 | 🌐 C# | 📅 2026-08-09 - Open Network For Smart Economy.
* [WalletWasabi](https://github.com/zkSNACKs/WalletWasabi) ⭐ 2,602 | 🐛 346 | 🌐 C# | 📅 2026-08-18 - Privacy focused, ZeroLink compliant Bitcoin wallet.
* [NBitcoin](https://github.com/MetacoSA/NBitcoin) ⭐ 1,942 | 🐛 116 | 🌐 C# | 📅 2026-08-12 - Comprehensive Bitcoin library for the .NET framework.
* [Nethermind](https://github.com/NethermindEth/nethermind) ⭐ 1,584 | 🐛 386 | 🌐 C# | 📅 2026-08-19 - .NET Core Ethereum client
* [StratisBitcoinFullNode](https://github.com/stratisproject/StratisBitcoinFullNode) ⚠️ Archived - Simple and affordable end-to-end solutions for development, testing and deployment of native C# blockchain applications on the .Net framework.
* [NBXplorer](https://github.com/dgarage/NBXplorer) ⭐ 369 | 🐛 47 | 🌐 C# | 📅 2026-08-13 - A Bitcoin and Altcoin lightweight block explorer.
* [Meadow](https://github.com/MeadowSuite/Meadow) ⭐ 143 | 🐛 18 | 🌐 C# | 📅 2022-12-08 - An integrated Ethereum implementation and tool suite focused on Solidity testing and development.
* [NBlockchain](https://github.com/danielgerlag/NBlockchain) ⭐ 85 | 🐛 9 | 🌐 C# | 📅 2025-01-18 - .NET standard library for building blockchain enabled applications
* [Trezor.Net](https://github.com/MelbourneDeveloper/Trezor.Net) ⭐ 43 | 🐛 12 | 🌐 C# | 📅 2022-12-08 - Cross platform C# library for talking to the Trezor Hardwarewallet
* [Nethereum](https://github.com/Nethereum) - Bringing the love of Ethereum to .NET.

### Bot

* [Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot) ⭐ 3,644 | 🐛 0 | 🌐 C# | 📅 2026-08-02 - C# Telegram Bot API library.
* [BotSharp](https://github.com/SciSharp/BotSharp) ⭐ 3,093 | 🐛 46 | 🌐 C# | 📅 2026-08-19 - The Open Source AI Chatbot Platform Builder in 100% C# Running in .NET Core with Machine Learning algorithm.
* [Funogram](https://github.com/Dolfik1/Funogram) ⭐ 109 | 🐛 0 | 🌐 F# | 📅 2026-07-16 - F# Telegram Bot Api library.
* [NadekoBot](https://github.com/Kwoth/NadekoBot) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-11-29 - Open source, general-purpose Discord chat bot written in C#.

### Build Automation

* [msbuild](https://github.com/Microsoft/msbuild) ⭐ 5,541 | 🐛 1,667 | 🌐 C# | 📅 2026-08-19 - The Microsoft Build Engine is a platform for building applications.
* [dotnet-docker](https://github.com/dotnet/dotnet-docker) ⭐ 4,867 | 🐛 136 | 🌐 Dockerfile | 📅 2026-08-18 - The base Docker images for working with .NET Core and the .NET Core Tools.
* [Opserver](https://github.com/opserver/Opserver) ⭐ 4,564 | 🐛 76 | 🌐 C# | 📅 2024-11-30 - Stack Exchange's Monitoring System.
* [cake-build](https://github.com/cake-build/cake) ⭐ 4,184 | 🐛 248 | 🌐 C# | 📅 2026-07-17 - Cross platform build automation system.
* [Nuke](https://github.com/nuke-build/nuke) ⭐ 3,748 | 🐛 122 | 🌐 C# | 📅 2025-12-02 - Cross-platform build automation system.
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) ⭐ 1,911 | 🐛 224 | 🌐 C# | 📅 2026-08-19 - Visual Studio Team Services Build and Release Agent.
* [GitVersioning](https://github.com/AArnott/Nerdbank.GitVersioning) ⭐ 1,580 | 🐛 13 | 🌐 C# | 📅 2026-08-18 - Stamp your assemblies and NuGet packages with a version from a single, simple version.txt file and include git commit IDs for non-official builds.
* [Colorful.Console](https://github.com/tomakita/Colorful.Console) ⭐ 1,329 | 🐛 34 | 🌐 C# | 📅 2024-06-06 - Style your C# console output!
* [FlubuCore](https://github.com/dotnetcore/FlubuCore) ⭐ 938 | 🐛 31 | 🌐 C# | 📅 2026-03-25 - A cross platform build and deployment automation system for building projects and executing deployment scripts using C# code.
* [GitInfo](https://github.com/kzu/GitInfo) ⭐ 650 | 🐛 2 | 🌐 Pascal | 📅 2026-08-17 - Git and SemVer Info from MSBuild, C# and VB.
* [go-dotnet](https://github.com/matiasinsaurralde/go-dotnet) ⭐ 495 | 🐛 7 | 🌐 C++ | 📅 2018-05-24 - Go wrapper for the .NET Core Runtime.
* [Image2Docker](https://github.com/docker/communitytools-image2docker-win) ⚠️ Archived - PowerShell module which ports existing Windows application workloads to Docker.
* [Dockerize.NET](https://github.com/brthor/Dockerize.NET) ⭐ 180 | 🐛 5 | 🌐 C# | 📅 2022-12-07 - .NET Cli Tool to package your .NET Core Application into a docker image: 'dotnet dockerize'
* [LocalAppVeyor](https://github.com/joaope/LocalAppVeyor) ⭐ 124 | 🐛 14 | 🌐 C# | 📅 2024-11-11 - Run your AppVeyor builds, locally.
* [CatLight](https://catlight.io) - Status notifier for developers that monitors builds and tasks in the project. Built using .Net Core and Electron.

### Bundling and Minification

* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier) ⭐ 626 | 🐛 312 | 🌐 C# | 📅 2024-05-03 - Visual Studio extension that let's you configure bundling and minification of JS, CSS and HTML files.
* [Web Markup Minifier](https://github.com/Taritsyn/WebMarkupMin) ⭐ 497 | 🐛 5 | 🌐 C# | 📅 2026-08-04 - .NET library that contains a set of markup minifiers. The objective of this project is to improve the performance of web applications by reducing the size of HTML, XHTML and XML code.
* [Smidge](https://github.com/Shazwazza/Smidge/) ⭐ 374 | 🐛 32 | 🌐 C# | 📅 2026-07-15 - Lightweight runtime CSS/JavaScript file minification, combination, compression & management library for ASP.NET Core.
* [JavaScriptViewEngine](https://github.com/pauldotknopf/JavaScriptViewEngine) ⭐ 72 | 🐛 1 | 🌐 C# | 📅 2017-12-03 - ASP.NET MVC ViewEngine for rendering markup in a JavaScript environment. Ideal for React and Angular server-side rendering.

### Caching

* [Faster](https://github.com/Microsoft/FASTER/tree/master/cs) ⭐ 6,637 | 🐛 35 | 🌐 C# | 📅 2026-08-19 - Fast key-value store from Microsoft Research.
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis) ⭐ 6,194 | 🐛 224 | 🌐 C# | 📅 2026-08-19 - High performance general purpose redis client for .NET languages (C# etc).
* [CacheManager](https://github.com/MichaCo/CacheManager) ⭐ 2,420 | 🐛 13 | 🌐 C# | 📅 2026-02-18 - Open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features. <http://cachemanager.michaco.net>
* [Foundatio](https://github.com/exceptionless/Foundatio) ⭐ 2,097 | 🐛 13 | 🌐 C# | 📅 2026-08-17 - Pluggable foundation blocks for building distributed apps.
* [EasyCaching](https://github.com/dotnetcore/EasyCaching) ⭐ 2,094 | 🐛 51 | 🌐 C# | 📅 2025-03-17 - Open source caching library that contains basic usages and some advanced usages of caching which can help us to handle caching more easier.
* [Microsoft Caching](https://github.com/aspnet/Caching) ⚠️ Archived - Libraries for in-memory caching and distributed caching.

### CMS

* [Orchard Core CMS](https://github.com/OrchardCMS/OrchardCore) ⭐ 8,157 | 🐛 852 | 🌐 C# | 📅 2026-08-19 - Open Source Content Management System built with ASP.NET Core on top of a Modular and Extensible Application Framework.
* [Umbraco](https://github.com/umbraco/umbraco-cms) ⭐ 5,227 | 🐛 481 | 🌐 C# | 📅 2026-08-19 - An extensible and friendly Open source ASP.NET Core CMS
* [ZKEACMS](https://github.com/SeriaWei/ZKEACMS.Core) ⭐ 2,836 | 🐛 5 | 🌐 C# | 📅 2026-08-09 - Visual design, build site onlie by drag and drop.
* [Squidex](https://github.com/Squidex/squidex) ⭐ 2,509 | 🐛 4 | 🌐 C# | 📅 2026-08-05 - Headless CMS, based on MongoDB, CQRS and Event Sourcing.
* [Piranha CMS](https://github.com/piranhacms/piranha.core) ⭐ 2,190 | 🐛 99 | 🌐 C# | 📅 2026-08-09 - A Lightweight & Unobtrusive Open Source CMS for ASP.NET Core and Entity Framework Core.
* [Miniblog](https://github.com/madskristensen/Miniblog.Core) ⭐ 1,520 | 🐛 63 | 🌐 C# | 📅 2026-01-19 - An ASP.NET Core blogging engine.
* [Blogifier.Core](https://github.com/blogifierdotnet/Blogifier.Core) ⭐ 1,295 | 🐛 29 | 🌐 C# | 📅 2026-03-16 - ASP.NET applications to provide common blogging functionality.
* [Cofoundry](https://github.com/cofoundry-cms/cofoundry) ⭐ 901 | 🐛 113 | 🌐 C# | 📅 2026-02-13 - Open source .NET Core CMS and modular application framework. Code-first, unobtrusive and extensible.
* [Mixcore CMS](https://github.com/mixcore/mix.core) ⭐ 887 | 🐛 2 | 🌐 C# | 📅 2026-01-29 - Open Source CMS powered by DotNet Core. Mixcore CMS is a scalable, open platform for web content management and digital experiences. Mixcore CMS provides deep capabilities and endless flexibility on the web.
* [dasblog-core](https://github.com/poppastring/dasblog-core) ⭐ 480 | 🐛 12 | 🌐 C# | 📅 2026-08-14 - The original DasBlog reimagined with ASP.NET Core
* [CoreWiki](https://github.com/csharpfritz/CoreWiki) ⭐ 438 | 🐛 71 | 🌐 CSS | 📅 2021-07-15 - Simple ASP.NET Core wiki that we are working on during live coding streams.
* [Awesome-CMS-Core](https://github.com/SaiGonSoftware/Awesome-CMS-Core) ⭐ 427 | 🐛 24 | 🌐 C# | 📅 2022-12-08 - Awesome CMS Core is an open source CMS built using ASP.Net Core & ReactJS with module separation concern in mind and provide lastest trend of technology
* [Lynicon](https://github.com/jamesej/lyniconanc) ⭐ 186 | 🐛 4 | 🌐 C# | 📅 2022-12-08 - O/S ASP.Net Core/.Net Core CMS with paid for modules: JSON content, works with variety of data stores, c# content types
* [NetCoreCMS](https://github.com/OnnoRokomSoftware/NetCoreCMS) ⭐ 167 | 🐛 8 | 🌐 JavaScript | 📅 2022-08-16 - An Open source ASP.NET Core 2.0 CMS. It currently supports MySQL and planned to implement MSSQL, SQLite and PostgreSQL. Also it is a modular CMS supports theme, skin, custom layout, widgets, multiple language (En, BN).
* [Wyam](https://github.com/Wyamio/Wyam) ⭐ 147 | 🐛 13 | 🌐 C# | 📅 2023-07-26 - Modular static content and static site generator.
* [Swastika I/O Core CMS](https://github.com/Swastika-IO/Swastika-IO-Core) ⭐ 133 | 🐛 19 | 🌐 C# | 📅 2022-09-14 - Open source ASP.NET Core 2.x CMS. It currently supports MS SQL and planned to implement MSSQL, SQLite in the near future. It has many built-in features out of the box like multilanguage support, theme, template...
* [Weapsy](https://github.com/Weapsy/Weapsy) ⚠️ Archived - Open source ASP.NET Core CMS based on DDD and CQRS. It supports MSSQL, MySQL, SQLite and PostgreSQL out of the box.
* [SimpleContent](https://github.com/joeaudette/cloudscribe.SimpleContent) ⭐ 1 | 🐛 0 | 📅 2026-04-07 - Simple, yet flexible content and blog engine for ASP.NET Core that can work with or without a database.
* [Platformus](https://github.com/Platformus) - Free, open source and cross-platform CMS based on ASP.NET Core 1.0 and ExtCore framework.

### Code Analysis and Metrics

* [awesome-static-analysis](https://github.com/mre/awesome-static-analysis) ⭐ 14,737 | 🐛 28 | 🌐 Rust | 📅 2026-06-10 - Curated list of static analysis tools, linters and code quality checkers for various programming languages.
* Code Analysis
  * [StyleCopAnalyzers](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) ⭐ 2,854 | 🐛 451 | 🌐 C# | 📅 2025-12-31 - StyleCop rules using the .NET Compiler Platform.
  * [roslyn-analyzers](https://github.com/dotnet/roslyn-analyzers) ⭐ 1,672 | 🐛 1,063 | 📅 2026-08-17 - .NET Compiler Platform ("Roslyn") Analyzers.
  * [CodeFormatter](https://github.com/dotnet/codeformatter) ⚠️ Archived - Tool that uses Roslyn to automatically rewrite the source to follow netfx coding styles. [Nuget Package](https://www.nuget.org/packages/Dotnet.CodeFormatter.BuildTask.Fork)
  * [DevSkim](https://github.com/Microsoft/DevSkim) ⭐ 1,002 | 🐛 74 | 🌐 C# | 📅 2026-08-16 - A set of IDE plugins and rules that provide security "linting" capabilities.
  * [RefactoringEssentials](https://github.com/icsharpcode/RefactoringEssentials) ⚠️ Archived - Refactoring Essentials for Visual Studio.
* Metrics
  * [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet) ⭐ 11,474 | 🐛 174 | 🌐 C# | 📅 2026-08-16 - Powerful .NET library for benchmarking.
  * [coverlet](https://github.com/tonerdo/coverlet) ⭐ 3,173 | 🐛 13 | 🌐 C# | 📅 2026-08-08 - Cross platform code coverage library for .NET Core.
  * [Audit.NET](https://github.com/thepirat000/Audit.NET) ⭐ 2,644 | 🐛 5 | 🌐 C# | 📅 2026-08-19 - Small framework to audit .NET object changes.
  * [AppMetrics](https://github.com/alhardy/AppMetrics) ⭐ 2,248 | 🐛 111 | 🌐 C# | 📅 2025-07-23 - App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application and reports it's health.
  * [Foundatio](https://github.com/exceptionless/Foundatio#metrics) ⭐ 2,097 | 🐛 13 | 🌐 C# | 📅 2026-08-17 - A common interface with in memory, redis, StatsD, and Metrics.NET implementations.
  * [prometheus-net](https://github.com/prometheus-net/prometheus-net) ⭐ 2,093 | 🐛 139 | 🌐 C# | 📅 2024-04-11 - .NET Client for <https://prometheus.io>.
  * [OpenCover](https://github.com/OpenCover/opencover) ⚠️ Archived - Code coverage tool for .NET 2 and above (WINDOWS OS only), support for 32 and 64 processes with both branch and sequence points.
  * [NBench](https://github.com/petabridge/NBench) ⭐ 540 | 🐛 36 | 🌐 C# | 📅 2024-09-10 - Performance benchmarking and testing framework for .NET applications.
  * [PerformanceMonitor](https://github.com/dotnet-architecture/PerformanceMonitor) ⚠️ Archived - .NET Core Application Performance Monitor.
  * [MiniCover](https://github.com/lucaslorentz/minicover) ⭐ 215 | 🐛 6 | 🌐 C# | 📅 2026-08-13 - Minimalist Code Coverage Tool for .NET Core.
  * [Prometheus.Client](https://github.com/PrometheusClientNet/Prometheus.Client) ⭐ 142 | 🐛 1 | 🌐 C# | 📅 2026-08-18 - .NET Client for [Prometheus](https://prometheus.io).
    * [Prometheus.Client.MetricPusher](https://github.com/PrometheusClientNet/Prometheus.Client.MetricPusher) ⭐ 19 | 🐛 2 | 🌐 C# | 📅 2026-08-15 -  Push metrics to a PushGateaway for the Prometheus.Client.
    * [Prometheus.Client.MetricServer](https://github.com/PrometheusClientNet/Prometheus.Client.MetricServer) ⭐ 16 | 🐛 2 | 🌐 C# | 📅 2026-08-15 -  MetricServer for the Prometheus.Client.
    * [Prometheus.Client.HttpRequestDurations](https://github.com/PrometheusClientNet/Prometheus.Client.HttpRequestDurations) ⭐ 11 | 🐛 2 | 🌐 C# | 📅 2026-08-15 -  Metrics logging of request durations for the Prometheus.Client.
    * [Prometheus.Client.AspNetCore](https://github.com/PrometheusClientNet/Prometheus.Client.AspNetCore) ⭐ 10 | 🐛 2 | 🌐 C# | 📅 2026-08-15 -  Middleware for the Prometheus.Client.
  * [Nexogen.Libraries.Metrics](https://github.com/nexogen-international/Nexogen.Libraries.Metrics) ⭐ 60 | 🐛 10 | 🌐 C# | 📅 2025-02-12 - Library for collecting application metrics in .NET and exporting them to Prometheus.

### Compression

* [sharpcompress](https://github.com/adamhathcock/sharpcompress) ⭐ 2,577 | 🐛 294 | 🌐 C# | 📅 2026-08-13 - Fully managed C# library to deal with many compression types and formats.
* [lz4net](https://github.com/MiloszKrajewski/K4os.Compression.LZ4) ⭐ 812 | 🐛 17 | 🌐 C# | 📅 2026-03-28 - Ultra fast compression algorithm for all .NET platforms.

### Compilers, Transpilers and Languages

* [roslyn](https://github.com/dotnet/roslyn) ⭐ 20,613 | 🐛 6,294 | 🌐 C# | 📅 2026-08-19 - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs.
* [Fable](https://github.com/fable-compiler/Fable) ⭐ 3,145 | 🐛 175 | 🌐 F# | 📅 2026-08-19 - F# to JavaScript Compiler.
* [peachpie](https://github.com/peachpiecompiler/peachpie) ⭐ 2,485 | 🐛 90 | 🌐 C# | 📅 2026-06-09 - Open-source PHP compiler to .NET.
* [Sprache](https://github.com/sprache/Sprache) ⭐ 2,473 | 🐛 22 | 🌐 C# | 📅 2024-04-18 - Tiny C# Monadic Parser Framework.
* [Pidgin](https://github.com/benjamin-hodgson/Pidgin) ⭐ 1,099 | 🐛 23 | 🌐 C# | 📅 2026-06-29 - A lightweight, fast and flexible parsing library for C#, developed at Stack Overflow.
* [fparsec](https://github.com/stephan-tolksdorf/fparsec) ⭐ 558 | 🐛 30 | 🌐 F# | 📅 2023-11-13 - A parser combinatory library for F# and C#.
* [IL2C](https://github.com/kekyo/IL2C) ⭐ 449 | 🐛 43 | 🌐 C# | 📅 2022-06-19 - A translator for ECMA-335 CIL/MSIL to C language.
* [Mond](https://github.com/Rohansi/Mond) ⭐ 396 | 🐛 7 | 🌐 C# | 📅 2026-08-03 - A dynamically typed scripting language written in C# with a REPL, debugger, and simple embedding API.

### Cryptography

* [BCrypt.Net](https://github.com/BcryptNet/bcrypt.net) ⭐ 997 | 🐛 5 | 🌐 C# | 📅 2026-07-09 - Bringing updates to the original bcrypt package.
* [nsec](https://github.com/ektrah/nsec) ⭐ 449 | 🐛 2 | 🌐 C# | 📅 2026-04-30 - NSec is a new cryptographic library for .NET Core based on libsodium.
* [BCrypt.NET-Core](https://github.com/neoKushan/BCrypt.Net-Core) ⭐ 221 | 🐛 0 | 🌐 C# | 📅 2020-07-11 - .NET Core port of BCrypt.NET used to store passwords securely.
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL) ⚠️ Archived - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols.
* [multiformats](https://github.com/multiformats/cs-multihash) ⚠️ Archived - A general purpose hashing library, but a library to encode/decode Multihashes which is a "container" describing what hash algorithm the digest is calculated with.
* [SecurityDriven.Inferno](github.com/sdrapkin/SecurityDriven.Inferno) - Hig level crypto library used .Net primitives, has been professionally audited.

### Database

* [LiteDB](https://github.com/mbdavid/LiteDB) ⭐ 9,458 | 🐛 755 | 🌐 C# | 📅 2026-08-11 - .NET NoSQL Document Store in a single data file - <http://www.litedb.org>.
* [marten](https://github.com/JasperFx/marten) ⭐ 3,443 | 🐛 5 | 🌐 C# | 📅 2026-08-18 - Postgresql as a Document Database and Event Store for .NET Applications <http://jasperfx.github.io/marten>.
* [yessql](https://github.com/sebastienros/yessql) ⭐ 1,357 | 🐛 150 | 🌐 C# | 📅 2026-08-17 - .NET document database working on any RDBMS.
* [DBreeze](https://github.com/hhblaze/DBreeze) ⭐ 577 | 🐛 1 | 🌐 C# | 📅 2026-08-18 - C# .NET MONO NOSQL (key value store embedded) ACID multi-paradigm database management system.
* [JsonFlatFileDataStore](https://github.com/ttu/json-flatfile-datastore) ⭐ 478 | 🐛 18 | 🌐 C# | 📅 2026-08-04 - Simple JSON flat file data store with support for typed and dynamic data.
* [StringDB](https://github.com/SirJosh3917/StringDB) ⭐ 71 | 🐛 4 | 🌐 C# | 📅 2023-02-24 - StringDB is a modular, key/value pair archival DB designed to consume *tiny* amounts of ram & produce *tiny* databases.
* [NoDb](https://github.com/joeaudette/NoDb) ⭐ 0 | 🐛 0 | 📅 2022-12-07 - "no database" file system storage for .NET Core/ASP.NET Core because not every project needs a database.

### Database Drivers

* [npgsql](https://github.com/npgsql/npgsql) ⭐ 3,719 | 🐛 227 | 🌐 C# | 📅 2026-08-18 - .NET data provider for PostgreSQL. It allows any program developed for .NET framework to access a PostgreSQL database server. It is implemented in 100% C# code. PostgreSQL versions since 9.1 are officially supported, others may work. <http://www.npgsql.org>
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver) ⭐ 3,240 | 🐛 14 | 🌐 C# | 📅 2026-08-18 - .NET Driver for MongoDB.
* [cassandra-csharp-driver](https://github.com/datastax/csharp-driver) ⭐ 669 | 🐛 15 | 🌐 C# | 📅 2026-08-13 - DataStax C# Driver for Apache Cassandra.
* [MongoDB.Entities](https://github.com/dj-nitehawk/MongoDB.Entities) ⭐ 571 | 🐛 5 | 🌐 C# | 📅 2026-08-02 - A data access library for MongoDB with an elegant api, LINQ support and built-in entity relationship management
* [couchbase-lite-net](https://github.com/couchbase/couchbase-lite-net) ⭐ 445 | 🐛 1 | 🌐 C# | 📅 2026-07-29 - A lightweight, document-oriented (NoSQL), syncable database engine for .NET.
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver) ⭐ 381 | 🐛 24 | 🌐 C# | 📅 2020-12-12 - C#/.NET RethinkDB driver with 100% ReQL API coverage.
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) ⭐ 296 | 🐛 21 | 🌐 C# | 📅 2026-08-19 - Linq enabled document database for .NET.
* [confluent-kafka-dotnet](https://github.com/confluentinc/confluent-kafka-dotnet) ⭐ 269 | 🐛 476 | 🌐 C# | 📅 2026-08-17 - Confluent's Apache Kafka .NET client.
* [progaudi.tarantool](https://github.com/progaudi/progaudi.tarantool) ⭐ 48 | 🐛 31 | 🌐 C# | 📅 2024-01-15 - .NET client for Tarantool NoSql database.
* MySQL
  * [MySqlConnector](https://github.com/mysql-net/MySqlConnector) ⭐ 1,500 | 🐛 96 | 🌐 C# | 📅 2026-08-11 - Async MySQL Connector for .NET and .NET Core.
  * [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/8.0) ⭐ 332 | 🐛 3 | 🌐 C# | 📅 2026-06-26 - Connector/Net is a fully-managed ADO.NET driver for MySQL.
* Neo4j
  * [Neo4jClient](https://github.com/Readify/Neo4jClient) ⭐ 428 | 🐛 87 | 🌐 C# | 📅 2024-12-19 - .NET client binding for Neo4j.
  * [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) ⭐ 247 | 🐛 5 | 🌐 C# | 📅 2026-07-24 - Neo4j Bolt driver for .NET.

### Database Tools and Utilities

* [fluentmigrator](https://github.com/fluentmigrator/fluentmigrator) ⭐ 3,508 | 🐛 214 | 🌐 C# | 📅 2026-08-12 - Migration framework for .NET much like Ruby on Rails Migrations.
* [DbUp](https://github.com/DbUp/DbUp) ⭐ 2,619 | 🐛 80 | 🌐 C# | 📅 2026-02-23 - .NET library that helps you to deploy changes to SQL Server databases. It tracks which SQL scripts have been run already, and runs the change scripts that are needed to get your database up to date.
* [EFCorePowerTools](https://github.com/ErikEJ/EFCorePowerTools) ⭐ 2,509 | 🐛 5 | 🌐 C# | 📅 2026-08-19 - Entity Framework Core Power Tools - reverse engineering, migrations and model visualization for EF Core.
* [roundhouse](https://github.com/chucknorris/roundhouse) ⭐ 916 | 🐛 81 | 🌐 C# | 📅 2024-03-10 - Database Migration Utility for .NET using sql files and versioning based on source control.
* [Evolve](https://github.com/lecaillon/Evolve) ⭐ 907 | 🐛 46 | 🌐 C# | 📅 2025-09-30 - Simple database migration tool that uses plain SQL scripts. Inspired by Flyway.
* [monitor-table-change-with-sqltabledependency](https://github.com/christiandelbianco/monitor-table-change-with-sqltabledependency) ⭐ 665 | 🐛 60 | 🌐 C# | 📅 2024-01-16 - Get SQL Server notification on record table change.
* [SharpRepository](https://github.com/SharpRepository/SharpRepository) ⭐ 655 | 🐛 38 | 🌐 C# | 📅 2023-03-04 - SharpRepository is a generic repository written in C# which includes support for various relational, document and object databases including Entity Framework, RavenDB, MongoDb and Db4o. SharpRepository includes Xml and InMemory repository implementations as well.
* [SapphireDb](https://github.com/SapphireDb/SapphireDb) ⭐ 406 | 🐛 12 | 🌐 C# | 📅 2022-12-08 - Server implementation of SapphireDb, a framework for easy development of applications with realtime data synchronization and a self hosted alternative to firebase realtime database/firestore for asp.net core and ef core. Check out the documentation for more details: [Documentation](https://sapphire-db.com)
* [EntityFrameworkCore.DataEncryption](https://github.com/Eastrall/EntityFrameworkCore.DataEncryption) ⭐ 349 | 🐛 7 | 🌐 C# | 📅 2025-12-17 - A plugin for Microsoft.EntityFrameworkCore to add support of encrypted fields using built-in or custom encryption providers.
* [Mongo.Migration](https://github.com/SRoddis/Mongo.Migration) ⭐ 183 | 🐛 34 | 🌐 C# | 📅 2026-03-18 - Mongo.Migration is designed for the [MongoDB C# Driver](https://github.com/mongodb/mongo-csharp-driver) ⭐ 3,240 | 🐛 14 | 🌐 C# | 📅 2026-08-18 to migrate your documents easily and on-the-fly. No more downtime for schema-migrations. Just write small and simple migrations. [Link](https://github.com/SRoddis/Mongo.Migration) ⭐ 183 | 🐛 34 | 🌐 C# | 📅 2026-03-18
* [TrackableEntities.Core](https://github.com/TrackableEntities/TrackableEntities.Core) ⭐ 81 | 🐛 1 | 🌐 C# | 📅 2025-12-04 - Change-tracking across service boundaries with .NET Core.
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData) - In-memory data cube with OLAP operations and PivotTable data model.

### Date and Time

* [nodatime](https://github.com/nodatime/nodatime) ⭐ 2,996 | 🐛 34 | 🌐 C# | 📅 2026-07-16 - Better date and time API for .NET <http://nodatime.org>.
* [FluentDateTime](https://github.com/FluentDateTime/FluentDateTime) ⭐ 697 | 🐛 1 | 🌐 C# | 📅 2026-07-23 - Allows you to write cleaner DateTime expressions and operation. Partially inspired by Ruby DateTime Extensions.
* [Exceptionless.DateTimeExtensions](https://github.com/exceptionless/Exceptionless.DateTimeExtensions) ⭐ 247 | 🐛 5 | 🌐 C# | 📅 2026-08-17 - DateTimeRange, Business Day and various DateTime, DateTimeOffset, TimeSpan extension methods.

### Distributed Computing

* [Polly](https://github.com/App-vNext/Polly) ⭐ 14,229 | 🐛 5 | 🌐 C# | 📅 2026-08-16 - .NET 3.5 / 4.0 / 4.5 / PCL library that allows developers to express transient exception and fault handling policies such as Retry, Retry Forever, Wait and Retry or Circuit Breaker in a fluent manner
* [Ocelot](https://github.com/ThreeMammals/Ocelot) ⭐ 8,715 | 🐛 60 | 🌐 C# | 📅 2026-08-18 - API Gateway created using .NET Core
* [AspNetCore.Diagnostics.HealthChecks](https://github.com/xabaril/AspNetCore.Diagnostics.HealthChecks) ⭐ 4,372 | 🐛 379 | 🌐 C# | 📅 2026-06-22 - Enterprise HealthChecks for ASP.NET Core Diagnostics Package
  * [BeatPulse](https://github.com/Xabaril/BeatPulse) ⚠️ Archived - Enable load balancers to monitor the status of deployed Web applications
* [Foundatio](https://github.com/exceptionless/Foundatio) ⭐ 2,097 | 🐛 13 | 🌐 C# | 📅 2026-08-17 - Pluggable foundation blocks for building distributed apps
* [ProxyKit](https://github.com/damianh/ProxyKit) ⚠️ Archived - Toolkit to create code-first HTTP reverse proxies on ASP.NET Core
* [OpenTracing](https://github.com/opentracing/opentracing-csharp) ⚠️ Archived - Vendor-neutral APIs and instrumentation for distributed tracing
* [jasper](https://github.com/JasperFx/jasper) ⚠️ Archived - Next generation application development framework for .NET
* [Obvs](https://github.com/christopherread/Obvs) ⭐ 338 | 🐛 7 | 🌐 C# | 📅 2025-04-23 - An observable microservice bus .NET library that wraps the underlying transport in simple Rx based interfaces
* [Rafty](https://github.com/ThreeMammals/Rafty) ⭐ 200 | 🐛 5 | 🌐 C# | 📅 2025-07-15 - RAFT consensus in .NET Core

### E-Commerce and Payments

* [nopCommerce](https://github.com/nopSolutions/nopCommerce) ⭐ 10,126 | 🐛 167 | 🌐 C# | 📅 2026-08-18 - Free open-source ecommerce shopping cart (ASP.NET MVC / ASP.NET Core MVC ) with a vast community and a market place full of new features, themes and plugins.
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce) ⭐ 4,418 | 🐛 172 | 🌐 C# | 📅 2026-06-08 - Super simple ecommerce system built on .NET Core.
* [GrandNode](https://github.com/grandnode/grandnode) ⚠️ Archived - Multi-platform, free, open source ecommerce shopping cart based on ASP.NET Core 2.1 and MongoDB derived from [nopCommerce](https://github.com/nopSolutions/nopCommerce) ⭐ 10,126 | 🐛 167 | 🌐 C# | 📅 2026-08-18.
* [Stripe](https://github.com/ServiceStack/Stripe) ⚠️ Archived - Typed .NET clients for stripe.com REST APIs.
* [PayPal](https://github.com/paypal/PayPal-NET-SDK) - .NET SDK for PayPal's RESTful APIs.

### Exceptions

* [Demystifier](https://github.com/benaadams/Ben.Demystifier) ⭐ 2,866 | 🐛 56 | 🌐 C# | 📅 2024-03-14 - High performance understanding for stack traces (Make error logs more productive).
* [Sentry](https://github.com/getsentry/sentry-dotnet) ⭐ 770 | 🐛 319 | 🌐 C# | 📅 2026-08-19 - .NET SDK for Sentry, an Open-source error tracking that helps developers monitor and fix crashes in real time.
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) ⭐ 572 | 🐛 13 | 🌐 C# | 📅 2026-08-13 - Exceptionless .NET Client
* [GlobalExceptionHandlerDotNet](https://github.com/JosephWoodward/GlobalExceptionHandlerDotNet) ⭐ 269 | 🐛 13 | 🌐 C# | 📅 2022-12-08 - GlobalExceptionHandlerDotNet allows you to configure exception handling as a convention with your ASP.NET Core application pipeline as opposed to explicitly handling them within each controller action.

### Functional Programming

* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) ⭐ 8,534 | 🐛 3 | 🌐 C# | 📅 2026-08-18 - A MVVM framework that integrates with the Reactive Extensions for .NET to create elegant, testable User Interfaces that run on any mobile or desktop platform.
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) ⭐ 7,187 | 🐛 180 | 🌐 C# | 📅 2026-07-17 - The [Reactive Extensions](http://reactivex.io) for .NET.
* [language-ext](https://github.com/louthy/language-ext) ⭐ 7,082 | 🐛 15 | 🌐 C# | 📅 2026-07-29 - C# functional language extensions and 'Erlang like' concurrency system.
* [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) ⭐ 2,825 | 🐛 101 | 🌐 C# | 📅 2026-03-02 - Functional Extensions for C#.
* [Giraffe](https://github.com/dustinmoris/Giraffe) ⭐ 2,250 | 🐛 45 | 🌐 F# | 📅 2026-08-18 - A native functional ASP.NET Core web framework for F# developers.
* [DynamicData](https://github.com/RolandPheasant/DynamicData) ⭐ 1,896 | 🐛 55 | 🌐 C# | 📅 2026-08-08 - Reactive collections based on Rx.NET.
* [FsCheck](https://github.com/fscheck/FsCheck) ⭐ 1,247 | 🐛 22 | 🌐 F# | 📅 2026-08-18 - Random Testing for .NET.
* [Optional](https://github.com/nlkl/Optional) ⭐ 921 | 🐛 26 | 🌐 C# | 📅 2023-08-31 - A robust option type for C#.
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/) ⭐ 851 | 🐛 28 | 🌐 C# | 📅 2026-08-17 - Functional Reactive Programming (FRP) Library. `4.x.x or above`
* [LaYumba.Functional](https://github.com/la-yumba/functional-csharp-code) ⭐ 610 | 🐛 10 | 🌐 C# | 📅 2022-12-07 - Utility library for programming functionally in C#.
* [reactive-streams-dotnet](https://github.com/reactive-streams/reactive-streams-dotnet) ⭐ 202 | 🐛 11 | 🌐 C# | 📅 2021-07-15 - [Reactive Streams](http://www.reactive-streams.org/) for .NET.
* [Qactive](https://github.com/RxDave/Qactive) ⭐ 160 | 🐛 23 | 🌐 C# | 📅 2017-10-13 - Reactive queryable observable framework. `4.x.x or above`
* [echo-process](https://github.com/louthy/echo-process) ⭐ 124 | 🐛 9 | 🌐 C# | 📅 2023-05-03 - Actor library for C# with additional modules that support persistence to Redis, as well as JS integration.
* [NetMQ.ReactiveExtensions](https://github.com/NetMQ/NetMQ.ReactiveExtensions) ⭐ 68 | 🐛 9 | 🌐 C# | 📅 2017-12-14 - Effortlessly send messages anywhere on the network using Reactive Extensions (RX). Transport protocol is ZeroMQ.

### Graphics

* [ImageSharp](https://github.com/SixLabors/ImageSharp) ⭐ 8,028 | 🐛 25 | 🌐 C# | 📅 2026-08-11 - Cross-platform library for processing of image files written in C#.
* [QRCoder](https://github.com/codebude/QRCoder) ⭐ 5,151 | 🐛 29 | 🌐 C# | 📅 2026-07-23 - A pure C# Open Source QR Code implementation.
* [Magick.NET](https://github.com/dlemstra/Magick.NET) ⭐ 3,970 | 🐛 53 | 🌐 C# | 📅 2026-08-13 - The .NET library for ImageMagick.
* [ZXing.Net](https://github.com/micjahn/ZXing.Net/) ⭐ 3,085 | 🐛 78 | 🌐 C# | 📅 2026-07-06 - .Net port of the original java-based barcode reader and generator library zxing.
* [veldrid](https://github.com/mellinoe/veldrid) ⭐ 2,696 | 🐛 159 | 🌐 C# | 📅 2026-03-17 - A low-level, hardware-accelerated 3D graphics library for .NET.
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) ⚠️ Archived - A fluent wrapper around System.Drawing for the processing of image files <http://imageprocessor.org>. `4.5.x or above`
* [LibVLCSharp](https://github.com/videolan/libvlcsharp) ⭐ 1,806 | 🐛 5 | 🌐 C# | 📅 2026-08-05: .NET/Mono bindings for libvlc, the multimedia framework powering the VLC applications made by VideoLAN.
* [MagicScaler](https://github.com/saucecontrol/PhotoSauce) ⭐ 734 | 🐛 30 | 🌐 C# | 📅 2025-04-10 - MagicScaler high-performance, high-quality image processing pipeline for .NET
* [SharpBgfx](https://github.com/MikePopoloski/SharpBgfx) ⚠️ Archived - C# bindings for the bgfx graphics library.
* [Structure.Sketching](https://github.com/JaCraig/Structure.Sketching) ⭐ 83 | 🐛 0 | 🌐 C# | 📅 2017-03-23 - Image processing library for use in .NET applications that supports .NET Core.
* [GLFWDotNet](https://github.com/smack0007/GLFWDotNet) ⚠️ Archived - .NET bindings for GLFW.

### GUI

* [Avalonia](https://github.com/AvaloniaUI/Avalonia) ⭐ 31,348 | 🐛 1,935 | 🌐 C# | 📅 2026-08-19 - A multi-platform .NET UI framework (formerly known as Perspex).
* [AdonisUI](https://github.com/benruehl/adonis-ui) ⭐ 1,866 | 🐛 50 | 🌐 C# | 📅 2022-09-29 - Lightweight UI toolkit for WPF applications offering classic but enhanced windows visuals.
* [ShellProgressBar](https://github.com/Mpdreamz/shellprogressbar) ⭐ 1,481 | 🐛 35 | 🌐 C# | 📅 2024-07-16 - library to create progress bars in console programs
* [Qml.Net](https://github.com/pauldotknopf/Qml.Net) ⭐ 1,413 | 🐛 52 | 🌐 C# | 📅 2022-12-08 - A cross-platform Qml/.NET integration for Mono/.NET/.NET Core.
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/) ⭐ 1,122 | 🐛 90 | 🌐 C# | 📅 2026-06-05 - The Avalonia-based text editor component forked from [AvalonEdit](https://github.com/icsharpcode/AvalonEdit) ⭐ 2,074 | 🐛 114 | 🌐 C# | 📅 2025-12-04
  [HandyControls](https://github.com/ghost1372/HandyControls) ⭐ 1,305 | 🐛 11 | 🌐 C# | 📅 2026-05-28 - Contains some simple and commonly used WPF controls.
* [WinApi](https://github.com/prasannavl/WinApi) ⭐ 846 | 🐛 28 | 🌐 C# | 📅 2022-12-07 - A simple, direct, ultra-thin CLR library for high-performance Win32 Native Interop with automation, windowing, DirectX, OpenGL and Skia helpers.
* [Lara](https://github.com/integrativesoft/lara) ⭐ 160 | 🐛 10 | 🌐 C# | 📅 2026-04-08 - Lara Web Engine is a library for developing Web user interfaces in C#

### IDE

* [Visual Studio Code](https://github.com/Microsoft/vscode) ⭐ 188,918 | 🐛 19,965 | 🌐 TypeScript | 📅 2026-08-19 - New type of tool that combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. Code provides comprehensive editing and debugging support, an extensibility model, and lightweight integration with existing tools.
* [Mono](https://github.com/mono/monodevelop) ⚠️ Archived - MonoDevelop enables developers to quickly write desktop and web applications on Linux, Windows and Mac OS X. It also makes it easy for developers to port .NET applications created with Visual Studio to Linux and Mac OS X maintaining a single code base for all platforms.
* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop) ⚠️ Archived - SharpDevelop is a free Integrated Development Environment (IDE) for C#, VB.NET, Boo, IronPython, IronRuby and F# projects on Microsoft's .NET platform. It is written (almost) entirely in C#, and comes with features you would expect in an IDE plus a few more.
* [rider](https://www.jetbrains.com/rider/) - Cross-platform C# IDE based on the IntelliJ platform and ReSharper.
* [Omnisharp](http://www.omnisharp.net/) - Family of Open Source projects, each with one goal: To enable a great .NET experience in YOUR editor of choice.
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - Free editor for individual developers, open source projects, academic research, education, and small professional teams.

### Internationalization

* [Westwind.Globalization](https://github.com/RickStrahl/Westwind.Globalization) ⭐ 549 | 🐛 73 | 🌐 C# | 📅 2023-03-19 - Database driven resource localization for .NET applications.
* [Localization](https://github.com/aspnet/Localization) ⚠️ Archived - Localization abstractions and implementations for ASP.NET Core applications.
* [NetCoreStack.Localization](https://github.com/NetCoreStack/Localization) ⭐ 85 | 🐛 1 | 🌐 C# | 📅 2019-01-06 - Database Resource Localization for .NET Core with Entity Framework and In Memory Cache

### IOC

* [Autofac](https://github.com/autofac/Autofac) ⭐ 4,656 | 🐛 6 | 🌐 C# | 📅 2026-08-01 - Addictive .NET IoC container.
* [Unity](https://github.com/unitycontainer/unity) ⭐ 1,695 | 🐛 1 | 📅 2024-01-21 - A lightweight, extensible dependency injection container.
* [Castle.Windsor](https://github.com/castleproject/Windsor) ⭐ 1,535 | 🐛 94 | 🌐 C# | 📅 2024-07-11 Castle Windsor is a best of breed, mature Inversion of Control container available for .NET.
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) ⭐ 1,262 | 🐛 31 | 🌐 C# | 📅 2026-07-02 - Easy, flexible, and fast Dependency Injection library that promotes best practice to steer developers towards the pit of success.
* [DryIoc](https://github.com/dadhi/DryIoc) ⭐ 1,127 | 🐛 55 | 🌐 C# | 📅 2026-05-28 - Fast, small, full-featured IoC Container for .NET.
* [LightInject](https://github.com/seesharper/LightInject) ⭐ 633 | 🐛 104 | 🌐 C# | 📅 2026-05-21 - Ultra lightweight IoC container.
* [Lamar](https://github.com/JasperFx/lamar) ⭐ 606 | 🐛 35 | 🌐 C# | 📅 2026-05-29 - Fast Inversion of Control Tool and Sundry Items of Roslyn Chicanery.
* [Grace](https://github.com/ipjohnson/Grace) ⭐ 338 | 🐛 40 | 🌐 C# | 📅 2026-08-06 - Grace is a feature rich Dependency Injection Container designed with ease of use and performance in mind.
* [Stashbox](https://github.com/z4kn4fein/stashbox) ⭐ 155 | 🐛 2 | 🌐 C# | 📅 2026-08-10 - A lightweight, portable dependency injection framework for .NET based solutions.
* [AutoDI](https://github.com/Keboo/AutoDI) ⭐ 99 | 🐛 18 | 🌐 C# | 📅 2023-05-22 - Super-fast compile-time dependency injection using IL weaving.
* [Inyector](https://github.com/davidrevoledo/Inyector) ⭐ 13 | 🐛 4 | 🌐 C# | 📅 2019-10-31 - Dependency Injection Automation for AspNetCore

### Logging

* [serilog](https://github.com/serilog/serilog) ⭐ 8,032 | 🐛 17 | 🌐 C# | 📅 2026-07-31 - Simple .NET logging with fully-structured events.
  * [serilog-aspnetcore](https://github.com/serilog/serilog-aspnetcore) ⭐ 1,428 | 🐛 22 | 🌐 C# | 📅 2026-08-17 - Serilog integration for ASP.NET Core 2+.
  * [Serilog.Exceptions](https://github.com/RehanSaeed/Serilog.Exceptions) ⭐ 538 | 🐛 32 | 🌐 C# | 📅 2026-08-12 - Serilog.Exceptions is an add-on to [Serilog](https://serilog.net/) to log exception details and custom properties that are not output in Exception.ToString().
  * [Serilog.Settings.Configuration](https://github.com/serilog/serilog-settings-configuration) ⭐ 495 | 🐛 39 | 🌐 C# | 📅 2026-06-15 - A Serilog configuration provider that reads from Microsoft.Extensions.Configuration.
* [NLog](https://github.com/NLog/NLog) ⭐ 6,547 | 🐛 51 | 🌐 C# | 📅 2026-08-16 - Advanced .NET, Silverlight and Xamarin Logging with support for structured and non structured logging.
  * [NLog.Extensions.Logging](https://github.com/NLog/NLog.Extensions.Logging) ⭐ 402 | 🐛 2 | 🌐 C# | 📅 2026-08-16 - NLog Provider for Microsoft.Extensions.Logging for .NET Standard libraries and .NET Core applications
  * [NLog for ASP.NET and ASP.NET Core](https://github.com/NLog/NLog.Web) ⭐ 329 | 🐛 9 | 🌐 C# | 📅 2026-08-16 - NLog integration for ASP.NET & ASP.NET Core 1-3
  * [NLog.Windows.Forms](https://github.com/NLog/NLog.Windows.Forms) ⭐ 49 | 🐛 0 | 🌐 C# | 📅 2026-07-14 - NLog targets specific for Windows.Forms
  * [NLog.MailKit](https://github.com/NLog/NLog.MailKit) ⭐ 17 | 🐛 0 | 🌐 C# | 📅 2026-08-08 - Alternative Mail target using the using MailKit library
* [Foundatio](https://github.com/exceptionless/Foundatio#logging) ⭐ 2,097 | 🐛 13 | 🌐 C# | 📅 2026-08-17 - A fluent logging api that can be used to log messages throughout your application.
* [log4net](https://github.com/apache/logging-log4net) ⭐ 934 | 🐛 5 | 🌐 C# | 📅 2026-08-18 - log4net is a port of the excellent Apache log4j™ framework to the Microsoft® .NET runtime.
* [LibLog](https://github.com/damianh/LibLog) ⚠️ Archived - Single file for you to either copy/paste or install via nuget, into your library/ framework/ application to provide a logging abstraction.
* [common-logging](https://github.com/net-commons/common-logging) ⭐ 651 | 🐛 62 | 🌐 C# | 📅 2021-09-23 - Portable logging abstraction for .NET.
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) ⭐ 572 | 🐛 13 | 🌐 C# | 📅 2026-08-13 - Exceptionless .NET Client
* [ElmahCore](https://github.com/ElmahCore/ElmahCore) ⭐ 312 | 🐛 89 | 🌐 C# | 📅 2024-04-03 - Error logging library that includes features like error filtering and the ability to view the error log from a web page.
* [Karambolo.Extensions.Logging.File](https://github.com/adams85/filelogger) ⭐ 170 | 🐛 2 | 🌐 C# | 📅 2026-07-03 - A lightweight library which implements file logging for the built-in .NET Core logging framework (Microsoft.Extensions.Logging).
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2016-04-17 - Logstash logging extension for .NET Core applications with UDP and Redis transports.
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights) ⚠️ Archived - Log appender for the build in ASP.NET Core logging to send all logs to Application Insights.
* [SEQ](https://getseq.net) - Seq collects data over HTTP, while your applications use the best available structured logging APIs for your platform.

### Machine Learning and Data Science

* [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) ⭐ 25,279 | 🐛 9 | 🌐 C# | 📅 2026-03-22 - itmap & tilemap generation from a single example with the help of ideas from quantum mechanics.
* [ML.NET](https://github.com/dotnet/machinelearning) ⭐ 9,349 | 🐛 1,008 | 🌐 C# | 📅 2026-08-17 - Cross-platform open-source machine learning framework which makes machine learning accessible to .NET developers <http://dot.net/ml>.
* [Accord](https://github.com/accord-net/framework) ⚠️ Archived - Machine learning, computer vision, statistics and general scientific computing for .NET.
* [TensorFlowSharp](https://github.com/migueldeicaza/TensorFlowSharp) ⚠️ Archived - TensorFlow API for .NET languages.
* [Catalyst](https://github.com/curiosity-ai/catalyst) ⭐ 858 | 🐛 50 | 🌐 C# | 📅 2026-08-07 Cross-platform Natural Language Processing (NLP) library inspired by spaCy, with pre-trained models, out-of-the box support for training word and document embeddings, and flexible entity recognition models. Part of the [SciSharp Stack](https://scisharp.github.io/SciSharp/)
* [Spreads](https://github.com/Spreads/Spreads/) ⭐ 433 | 🐛 12 | 🌐 C# | 📅 2023-04-16 - Series and Panels for Real-time and Exploratory Analysis of Data Streams.
* [SiaNet](https://github.com/SciSharp/SiaNet) ⚠️ Archived - A C# deep learning library, human friendly, CUDA/OpenCL supported, well structured, easy to extend

### Mail

* [MailKit](https://github.com/jstedfast/MailKit) ⭐ 6,840 | 🐛 9 | 🌐 C# | 📅 2026-08-17 - Cross-platform .NET library for IMAP, POP3, and SMTP.
* [Papercut](https://github.com/ChangemakerStudios/Papercut) ⭐ 3,325 | 🐛 2 | 🌐 C# | 📅 2026-08-19 - Simple Desktop SMTP Server
* [FluentEmail](https://github.com/lukencode/FluentEmail) ⭐ 3,214 | 🐛 130 | 🌐 C# | 📅 2024-03-30 - All in one email sender for .NET and .NET Core
* [MimeKit](https://github.com/jstedfast/MimeKit) ⭐ 2,000 | 🐛 12 | 🌐 C# | 📅 2026-08-15 - Cross-platform .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
* [SmtpServer](https://github.com/cosullivan/SmtpServer) ⭐ 817 | 🐛 37 | 🌐 C# | 📅 2026-04-18 - Library to create your own SMTP server.
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net) ⭐ 688 | 🐛 17 | 🌐 C# | 📅 2026-08-17 - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.
* [StrongGrid](https://github.com/Jericho/StrongGrid) ⭐ 197 | 🐛 12 | 🌐 C# | 📅 2026-03-20 - Client for SendGrid's v3 API. Not only allows you to send emails, but also allows you to bulk import contacts, manage lists and segments, create custom fields for your lists, etc. Also includes a parser for SendGrid Webhooks.
* [MailBody](https://github.com/doxakis/MailBody) ⭐ 158 | 🐛 1 | 🌐 HTML | 📅 2024-06-21 - Create transactional email with a fluent interface (.NET).
* [netDumbster](https://github.com/cmendible/netDumbster) ⭐ 131 | 🐛 2 | 🌐 C# | 📅 2024-07-22 - a .Net Fake SMTP Server used for testing. Clone of the popular Dumbster.
* [MailMergeLib](https://github.com/axuno/MailMergeLib) ⭐ 114 | 🐛 0 | 🌐 C# | 📅 2026-08-07 - SMTP mail client library which provides comfortable mail merge capabilities for text, inline images and attachments, as well as good throughput and fault tolerance for sending mail messages.
* [SendGrid Client](https://github.com/0xdeafcafe/sendgrid-dotnet) ⚠️ Archived - C# library for the SendGrid v3 mail endpoint.

### Mathematics

* [UnitsNet](https://github.com/angularsen/UnitsNet) ⭐ 2,967 | 🐛 22 | 🌐 C# | 📅 2026-08-02 - Units.NET gives you all the common units of measurement and the conversions between them.
* [UnitConversion](https://github.com/Stratajet/UnitConversion) ⭐ 186 | 🐛 6 | 🌐 C# | 📅 2022-02-07 - Expansible Unit Conversion Library for .NET Core and .NET Framework.
* [AutoDiff](https://github.com/alexshtf/autodiff) ⭐ 99 | 🐛 3 | 🌐 C# | 📅 2023-03-27 - A library that provides fast, accurate and automatic differentiation (computes derivative / gradient) of mathematical functions.

### Media

* [MetadataExtractor](https://github.com/drewnoakes/metadata-extractor-dotnet) ⭐ 1,068 | 🐛 69 | 🌐 C# | 📅 2026-07-15 - Extracts metadata from media (images, video, audio) with a simple to use API.

### Misc

* [AutoMapper](https://github.com/AutoMapper/AutoMapper) ⭐ 10,193 | 🐛 5 | 🌐 C# | 📅 2026-07-02 - Convention-based object-object mapper in .NET.
* [Humanizer](https://github.com/Humanizr/Humanizer) ⭐ 9,813 | 🐛 6 | 🌐 C# | 📅 2026-08-12 - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities.
* [AngleSharp](https://github.com/AngleSharp/AngleSharp) ⭐ 5,526 | 🐛 8 | 🌐 C# | 📅 2026-08-08 - The ultimate angle brackets parser library. It parses HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specification. Comparable to beautifulsoup4 of python.
* [markdig](https://github.com/lunet-io/markdig) ⭐ 5,302 | 🐛 115 | 🌐 C# | 📅 2026-08-18 - Fast, powerfull, CommonMark compliant, extensible Markdown processor for .NET.
* [CliWrap](https://github.com/Tyrrrz/CliWrap) ⭐ 4,996 | 🐛 4 | 🌐 C# | 📅 2026-08-01 - Wrapper for command line interfaces.
* [Fody](https://github.com/Fody/Fody) ⭐ 4,538 | 🐛 4 | 🌐 C# | 📅 2026-08-19 - Extensible tool for weaving .net assemblies
* [Scrutor](https://github.com/khellang/Scrutor) ⭐ 4,330 | 🐛 44 | 🌐 C# | 📅 2026-01-23 - Assembly scanning extensions for Microsoft.Extensions.DependencyInjection.
* [PuppeteerSharp](https://github.com/kblok/puppeteer-sharp) ⭐ 3,912 | 🐛 10 | 🌐 C# | 📅 2026-08-17 - Puppeteer Sharp is a .NET port of the official Node.JS Puppeteer API.
* [YoutubeExplode](https://github.com/Tyrrrz/YoutubeExplode) ⭐ 3,711 | 🐛 10 | 🌐 C# | 📅 2026-08-07 - Ultimate library for extracting metadata and downloading Youtube videos and playlists.
* [FluentFTP](https://github.com/robinrodricks/FluentFTP/) ⭐ 3,391 | 🐛 21 | 🌐 C# | 📅 2026-05-27 - FTP and FTPS client, with extensive FTP commands, SSL/TLS connections, hashing/checksums and more.
* [Dotnet Script](https://github.com/filipw/dotnet-script) ⭐ 3,007 | 🐛 127 | 🌐 C# | 📅 2026-07-19 - Run C# scripts from the .NET CLI.
* [Baget](https://github.com/loic-sharma/BaGet) ⭐ 2,799 | 🐛 252 | 🌐 C# | 📅 2024-07-09 - A lightweight NuGet server.
* [Castle.Core](https://github.com/castleproject/Core) ⭐ 2,314 | 🐛 34 | 🌐 C# | 📅 2026-04-14 - Castle Core, including Castle DynamicProxy, Logging Services and DictionaryAdapter <http://www.castleproject.org>.
* [Vanara](https://github.com/dahall/Vanara) ⭐ 2,090 | 🐛 7 | 🌐 C# | 📅 2026-08-17 - A set of .NET libraries for Windows implementing PInvoke calls to many native Windows APIs with supporting wrappers.
* [Enums.NET](https://github.com/TylerBrinkley/Enums.NET) ⭐ 1,832 | 🐛 3 | 🌐 C# | 📅 2025-10-05 - Enums.NET is a high-performance type-safe .NET enum utility library
* [System.Linq.Dynamic.Core](https://github.com/StefH/System.Linq.Dynamic.Core) ⭐ 1,711 | 🐛 60 | 🌐 C# | 📅 2026-07-11 - The .NET Standard (.NET Core) version from the System Linq Dynamic functionality.
* [Downloader](https://github.com/bezzad/Downloader) ⭐ 1,702 | 🐛 0 | 🌐 C# | 📅 2026-08-16 - Downloader is a modern, fluent, asynchronous, testable and portable library for .NET. This is a multipart downloader with asynchronous progress events.
* [Dotnet outdated](https://github.com/dotnet-outdated/dotnet-outdated) ⭐ 1,693 | 🐛 120 | 🌐 C# | 📅 2026-08-17 - A .NET Core global tool to display and update outdated NuGet packages in a project
* [Scientist](https://github.com/github/Scientist.net) ⭐ 1,487 | 🐛 12 | 🌐 C# | 📅 2025-11-26 - .NET library for carefully refactoring critical paths. It's a port of GitHub's Ruby Scientist library.
* [FluentDocker](https://github.com/mariotoffia/FluentDocker) ⭐ 1,388 | 🐛 5 | 🌐 C# | 📅 2026-07-19 - Commands, Services and Fluent API for docker, docker-compose & docker-machine, for win/mac/linux and native docker.
* [FastExpressionCompiler](https://github.com/dadhi/FastExpressionCompiler) ⭐ 1,372 | 🐛 23 | 🌐 C# | 📅 2026-08-14 - Fast ExpressionTree compiler to delegate.
* [Otp.NET](https://github.com/kspearrin/Otp.NET) ⭐ 1,316 | 🐛 20 | 🌐 C# | 📅 2025-12-01 - An implementation TOTP RFC 6238 and HOTP RFC 4226 in C#.
* [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET) ⭐ 1,254 | 🐛 3 | 🌐 C# | 📅 2026-08-01 - An extensible replacement for string.Format.
* [DinkToPdf](https://github.com/rdvojmoc/DinkToPdf) ⭐ 1,194 | 🐛 136 | 🌐 C# | 📅 2020-04-18 - C# .NET Core wrapper for wkhtmltopdf library that uses Webkit engine to convert HTML pages to PDF.
* [pose](https://github.com/tonerdo/pose) ⭐ 1,104 | 🐛 68 | 🌐 C# | 📅 2022-09-23 - Replace any .NET method (including static and non-virtual) with a delegate
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) ⭐ 1,013 | 🐛 15 | 🌐 C# | 📅 2020-03-27 - The implementation of CommonMark specification in C# for converting Markdown documents to HTML.
* [Bullseye](https://github.com/adamralph/bullseye/) ⭐ 954 | 🐛 13 | 🌐 C# | 📅 2026-07-21 - A .NET package for describing and running targets and their dependencies.
* [Dotnet Serve](https://github.com/natemcmaster/dotnet-serve) ⭐ 878 | 🐛 1 | 🌐 C# | 📅 2025-12-28 - Simple command-line HTTP server for .NET Core CLI.
* [readline](https://github.com/tsolarin/readline) ⭐ 828 | 🐛 27 | 🌐 C# | 📅 2021-08-19 - Pure C# GNU-Readline like library for .NET/.NET Core.
* [Xabe.FFmpeg](https://github.com/tomaszzmuda/Xabe.FFmpeg) ⭐ 775 | 🐛 54 | 🌐 C# | 📅 2025-08-07 - .NET Standard wrapper for FFmpeg. It allows to process media without know how FFmpeg works, and can be used to pass customized arguments to FFmpeg from C# application.
* [impromptu-interface](https://github.com/ekonbenefits/impromptu-interface) ⭐ 678 | 🐛 19 | 🌐 C# | 📅 2026-04-14 - Static interface to dynamic implementation (duck casting). Uses the DLR combined with Reflect.Emit.
* [commanddotnet](https://github.com/bilal-fazlani/commanddotnet) ⭐ 615 | 🐛 23 | 🌐 C# | 📅 2025-11-24 - Model your command line application interface in a class.
* [dotnet-env](https://github.com/tonerdo/dotnet-env) ⭐ 560 | 🐛 1 | 🌐 C# | 📅 2026-04-26 - A .NET library to load environment variables from .env files.
* [Relinq](https://github.com/re-motion/Relinq) ⭐ 528 | 🐛 2 | 🌐 C# | 📅 2023-03-28 - With re-linq, it's now easier than ever to create full-featured LINQ providers.
* [AdvanceDLSupport](https://github.com/Firwood-Software/AdvanceDLSupport) ⭐ 511 | 🐛 9 | 🌐 C# | 📅 2024-09-04 - Library to improve P/Invoke-ing native code. Interact with native objects as if they were first class objects.
* [NetCoreBeauty](https://github.com/nulastudio/NetCoreBeauty) ⭐ 505 | 🐛 9 | 🌐 C# | 📅 2025-12-01 - Simple library to move a .NET Core app runtime components and dependencies into a sub-directory and make it beauty.
* [AgileMapper](https://github.com/agileobjects/AgileMapper) ⭐ 463 | 🐛 14 | 🌐 C# | 📅 2026-03-16 - AgileMapper is a zero-configuration, highly-configurable object-object mapper with viewable execution plans.
* [DotNet.Glob](https://github.com/dazinator/DotNet.Glob) ⭐ 402 | 🐛 11 | 🌐 C# | 📅 2025-11-15 - A fast globbing library for .NET / .NETStandard applications. Outperforms Regex.
* [ReverseMarkdown](https://github.com/mysticmind/reversemarkdown-net) ⭐ 397 | 🐛 0 | 🌐 HTML | 📅 2026-08-13 - Html to Markdown converter library.
* [httpclient-interception](https://github.com/justeat/httpclient-interception) ⭐ 385 | 🐛 20 | 🌐 C# | 📅 2026-08-11 - .NET Standard library for intercepting server-side HTTP dependencies.
* [CoordinateSharp](https://github.com/Tronald/CoordinateSharp) ⭐ 381 | 🐛 2 | 🌐 C# | 📅 2026-01-16 - A library that can quickly format and convert geographic coordinates as well as provide location based sun and moon information (sunset, sunrise, moon illumination, etc...).
* [PdfReport.Core](https://github.com/VahidN/PdfReport.Core) ⭐ 372 | 🐛 7 | 🌐 C# | 📅 2026-08-17 - PdfReport.Core is a code first reporting engine, which is built on top of the iTextSharp.LGPLv2.Core and EPPlus.Core libraries.
* [Remote.Linq](https://github.com/6bee/Remote.Linq) ⭐ 356 | 🐛 0 | 🌐 C# | 📅 2026-06-29 - Remote Linq is a small and easy to use - yet very powerful - library to translate LINQ expression trees to strongly typed, serializable expression trees and vice versa.
* [ConsoleTableExt](https://github.com/minhhungit/ConsoleTableExt) ⭐ 348 | 🐛 5 | 🌐 C# | 📅 2024-07-18 - Fluent library to create table for .NET console application.
* [ReflectionMagic](https://github.com/ReflectionMagic/ReflectionMagic) ⭐ 347 | 🐛 0 | 🌐 C# | 📅 2024-01-29 - Framework to drastically simplify your private reflection code using C# dynamic
* [WebEssentials.AspNetCore.ServiceWorker](https://github.com/madskristensen/WebEssentials.AspNetCore.ServiceWorker) ⭐ 345 | 🐛 56 | 🌐 C# | 📅 2025-10-31 - ASP.NET Core Progressive Web Apps.
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser) ⭐ 313 | 🐛 14 | 🌐 C# | 📅 2025-10-17 - Parses string expressions (formulas, methods calls, conditions) to LINQ expression tree that can be compiled to lambda and evaluated.
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) ⚠️ Archived - Microsoft ASP.NET server-side support and helpers for jQuery DataTables.
* [JqueryDataTablesServerSide](https://github.com/fingers10/JqueryDataTablesServerSide) ⭐ 235 | 🐛 17 | 🌐 C# | 📅 2022-06-22 - ASP.NET Core Server Side Processing library for Jquery DataTables with Multiple Column Filtering, Sorting and Pagination at database level with Excel Export and TagHelper support.
* [NuGet Trends](https://github.com/NuGetTrends/nuget-trends) ⭐ 187 | 🐛 36 | 🌐 C# | 📅 2026-08-17 - Website with statistics of NuGet packages download count.
* [Chessie](https://github.com/fsprojects/Chessie) ⭐ 185 | 🐛 15 | 🌐 F# | 📅 2018-08-26 - Railway-oriented programming for .NET <http://fsprojects.github.io/Chessie>.
* [HdrHistogram.NET](https://github.com/HdrHistogram/HdrHistogram.NET) ⭐ 184 | 🐛 33 | 🌐 C# | 📅 2026-03-30 - High Dynamic Range (HDR) Histogram.
* [AspNetCore Extension Library](https://github.com/sgjsakura/AspNetCore) ⭐ 158 | 🐛 10 | 🌐 C# | 📅 2025-06-13 - ASP.NET Core Extension Library.
* [Sheller](https://github.com/twitchax/Sheller) ⭐ 108 | 🐛 0 | 🌐 C# | 📅 2020-03-17 - A .NET library that makes shelling out commands super easy and fluent.
* [LibSass Host](https://github.com/Taritsyn/LibSassHost) ⭐ 88 | 🐛 2 | 🌐 C++ | 📅 2026-02-03 - .NET wrapper around the [libSass](http://sass-lang.com/libsass) library with the ability to support a virtual file system.
* [NFlags](https://github.com/bartoszgolek/NFlags) ⭐ 50 | 🐛 2 | 🌐 C# | 📅 2021-12-20 - Simple library to made parsing CLI arguments easy. Library also allow to print usage help "out of box".
* [Eighty](https://github.com/benjamin-hodgson/Eighty) ⭐ 46 | 🐛 8 | 🌐 C# | 📅 2026-06-15 - A simple HTML generation library
* [Humidifier](https://github.com/jakejscott/Humidifier) ⭐ 46 | 🐛 4 | 🌐 C# | 📅 2022-12-08 - Write and maintain AWS Cloudformation templates using C#.
* [Bleak](https://github.com/Akaion/Bleak) - A Windows native DLL injection library.
* [NYoutubeDL](https://gitlab.com/BrianAllred/NYoutubeDL) - A simple youtube-dl library for C#/.NET.
* Stocks
  * [Trady](https://github.com/lppkarl/Trady) ⭐ 567 | 🐛 44 | 🌐 C# | 📅 2021-02-07 - Handy library for computing technical indicators, and it targets to be an automated trading system that provides stock data feeding, indicator computing, strategy building and automatic trading.
* Validation
  * [FluentValidation](https://github.com/JeremySkinner/FluentValidation) ⭐ 9,755 | 🐛 3 | 🌐 C# | 📅 2026-08-12 - Small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules.
  * [Guard](https://github.com/safakgur/guard) ⚠️ Archived - A high-performance, extensible argument validation library.
  * [Valit](https://github.com/valit-stack/Valit) ⭐ 321 | 🐛 11 | 🌐 C# | 📅 2019-12-24 - A dead simple validation for .NET Core. No more if-statements all around your code. Write nice and clean fluent validators instead!
  * [FormHelper](https://github.com/SinanBozkus/FormHelper) ⭐ 288 | 🐛 9 | 🌐 JavaScript | 📅 2022-11-29 - Form & Validation Helper for ASP.NET Core. Form Helper helps you to create ajax forms and validations without writing any javascript code. (Compatible with Fluent Validation).
* [warden-stack](https://github.com/warden-stack) - "health checks" for your applications, resources and infrastructure. Keep your Warden on the watch.

### Networking

* [SharpPcap](https://github.com/chmorgan/sharppcap) ⭐ 1,478 | 🐛 29 | 🌐 C# | 📅 2026-08-14 - Fully managed, cross platform (Windows, Mac, Linux) .NET library for capturing packets from live and file based devices.
* [AspNetCore.Proxy](https://github.com/twitchax/AspNetCore.Proxy) ⭐ 551 | 🐛 28 | 🌐 C# | 📅 2024-09-26 - ASP.NET Core Proxies made easy.
* [Networker](https://github.com/MarkioE/Networker) ⚠️ Archived - A simple to use TCP and UDP networking library for .NET, designed to be flexible, scalable and FAST.
* [CurlThin](https://github.com/stil/CurlThin) ⭐ 71 | 🐛 14 | 🌐 C# | 📅 2023-11-23 - Lightweight cURL binding library for C# with support for multiple simultaneous transfers through curl\_multi interface.
* [NETStandard.HttpListener](https://github.com/StefH/NETStandard.HttpListener) ⭐ 40 | 🐛 1 | 🌐 HTML | 📅 2018-02-24 - HttpListener for .NET Core (NETStandard).

### Office

* [Open-XML-SDK](https://github.com/OfficeDev/Open-XML-SDK) ⭐ 4,583 | 🐛 123 | 🌐 C# | 📅 2026-08-18 - The Open XML SDK provides tools for working with Office Word, Excel, and PowerPoint documents.
* [EPPlus](https://github.com/EPPlusSoftware/EPPlus) ⭐ 2,029 | 🐛 98 | 🌐 C# | 📅 2026-08-19 - Create advanced Excel spreadsheets using .NET.
* [npoi](https://github.com/tonyqus/npoi) ⭐ 159 | 🐛 1 | 🌐 C# | 📅 2026-07-29 - .NET library that can read/write Office formats without Microsoft Office installed. No COM+, no interop.

### Operating System

* [CosmosOS](https://github.com/CosmosOS/Cosmos) ⭐ 3,183 | 🐛 138 | 🌐 C# | 📅 2026-08-13 - Cosmos is an operating system "construction kit". Build your own OS using managed languages such as C#, VB.NET, and more!

### ORM

* [Dapper](https://github.com/StackExchange/Dapper) ⭐ 18,366 | 🐛 547 | 🌐 C# | 📅 2026-08-18 - Simple object mapper for .NET.
  * [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories) ⭐ 705 | 🐛 2 | 🌐 C# | 📅 2026-08-15 - CRUD for Dapper.
  * [Dommel](https://github.com/henkmollema/Dommel) ⭐ 692 | 🐛 9 | 🌐 C# | 📅 2026-06-24 - Simple CRUD operations for Dapper.
  * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap) ⚠️ Archived - Provides a simple API to fluently map POCO properties to database columns when using Dapper.
* [Entity Framework Core](https://github.com/aspnet/EntityFramework) ⭐ 14,770 | 🐛 2,375 | 🌐 C# | 📅 2026-08-18 - Familiar developer experience to previous versions of EF, including LINQ, POCO, and Code First support.
  * [EFCore.BulkExtensions](https://github.com/borisdj/EFCore.BulkExtensions) ⭐ 4,000 | 🐛 127 | 🌐 C# | 📅 2026-08-14 - EntityFrameworkCore Bulk Batch Extensions for Insert Update Delete Read (CRUD) ops
  * [Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql) ⭐ 2,976 | 🐛 216 | 🌐 C# | 📅 2025-08-17 - Entity Framework Core provider for MySql built on top of mysql-net/MySqlConnector.
  * [EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus) ⭐ 2,341 | 🐛 138 | 🌐 C# | 📅 2026-08-18 - Entity Framework Utilities | Bulk Operations | Batch Delete | Batch Update | Query Cache | Query Filter | Query Future | Query Include | Audit.
  * [Npgsql.EntityFrameworkCore.PostgreSQL](https://github.com/npgsql/Npgsql.EntityFrameworkCore.PostgreSQL) ⭐ 1,836 | 🐛 292 | 🌐 C# | 📅 2026-08-18 - Entity Framework Core provider for PostgreSQL.
  * [LINQKit](https://github.com/scottksmith95/LINQKit) ⭐ 1,830 | 🐛 47 | 🌐 C# | 📅 2026-02-07 - A free set of extensions for LINQ to SQL and Entity Framework power users.
  * [EntityFramework.Exceptions](https://github.com/Giorgi/EntityFramework.Exceptions) ⭐ 1,735 | 🐛 2 | 🌐 C# | 📅 2026-03-29 - Use typed Exceptions for EntityFrameworkCore when your SQL query violates database constraints in SqlServer, MySql, or PostgreSQL.
  * [EntityFramework.Triggers](https://github.com/NickStrupat/EntityFramework.Triggers) ⭐ 379 | 🐛 9 | 🌐 C# | 📅 2025-01-05 - Trigger events for EF.
  * [EntityFrameworkCore.SqlServer.SimpleBulks](https://github.com/phongnguyend/EntityFrameworkCore.SqlServer.SimpleBulks) ⭐ 203 | 🐛 1 | 🌐 C# | 📅 2026-03-10 - Simple library that can help to sync a large number of records in-memory into the database. Lambda Expression is supported.
  * [EntityFramework.Rx](https://github.com/NickStrupat/EntityFramework.Rx) ⭐ 133 | 🐛 2 | 🌐 C# | 📅 2019-10-02 - Reactive **hot** observables of your EF operations.
  * [EntityFramework.PrimaryKey](https://github.com/NickStrupat/EntityFramework.PrimaryKey) ⭐ 44 | 🐛 1 | 🌐 C# | 📅 2020-06-25 - Easily get the primary key of any entity (including composite keys).
  * [EntityFramework.VersionedProperties](https://github.com/NickStrupat/EntityFramework.VersionedProperties) ⭐ 42 | 🐛 1 | 🌐 C# | 📅 2021-08-06 - Classes which auto-magically keep an audit history of the changes to the specified property.
  * [spectre.query](https://github.com/spectresystems/spectre.query) ⚠️ Archived - A simple query language for Entity Framework Core.
  * [EntityFramework.TypedOriginalValues](https://github.com/NickStrupat/EntityFramework.TypedOriginalValues) ⭐ 35 | 🐛 2 | 🌐 C# | 📅 2017-08-28 - Get a proxy object of the original values of your entity (typed access to Property("...").OriginalValue).
  * [EFCore.Visualizer](https://marketplace.visualstudio.com/items?itemName=GiorgiDalakishvili.EFCoreVisualizer) - View Entity Framework Core query plan directly in Visual Studio.
* [querybuilder](https://github.com/sqlkata/querybuilder) ⭐ 3,378 | 🐛 179 | 🌐 C# | 📅 2026-04-10 - SqlKata Query Builder is a powerful Sql Query Builder written in C#.
* [nhibernate-core](https://github.com/nhibernate/nhibernate-core) ⭐ 2,172 | 🐛 671 | 🌐 C# | 📅 2026-08-18 - NHibernate Object Relational Mapper.
* [PetaPoco](https://github.com/CollaboratingPlatypus/PetaPoco) ⭐ 2,141 | 🐛 111 | 🌐 C# | 📅 2025-11-30 - A tiny ORM-ish thing for your POCO's.
* [RepoDb](https://github.com/mikependon/RepoDb) ⭐ 1,892 | 🐛 159 | 🌐 C# | 📅 2026-08-19 - A hybrid ORM library for .NET.
* [NEventStore](https://github.com/NEventStore/NEventStore) ⭐ 1,615 | 🐛 24 | 🌐 C# | 📅 2026-07-22 - Persistence library used to abstract different storage implementations when using event sourcing as storage mechanism. This library is developed with a specific focus on DDD/CQRS applications.
* [Chloe](https://github.com/shuxinqin/Chloe) ⭐ 1,543 | 🐛 22 | 🌐 C# | 📅 2026-07-27 - A lightweight and high-performance Object/Relational Mapping(ORM) library for .NET.
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) ⚠️ Archived - Light, simple and fast convention-based POCO ORM.
* [SmartSql](https://github.com/Ahoo-Wang/SmartSql) ⭐ 1,131 | 🐛 41 | 🌐 C# | 📅 2026-08-15 - SmartSql = MyBatis + Cache(Memory | Redis) + ZooKeeper + R/W Splitting +Dynamic Repository ....
* [NPoco](https://github.com/schotime/NPoco) ⭐ 879 | 🐛 47 | 🌐 C# | 📅 2026-02-11 - Simple microORM that maps the results of a query onto a POCO object. Project based on Schotime's branch of PetaPoco.
* [SQLStreamStore](https://github.com/SQLStreamStore/SQLStreamStore) ⚠️ Archived - Stream Store library targeting SQL based implementations for .NET.
* [SqlFu](https://github.com/sapiens/SqlFu) ⭐ 230 | 🐛 4 | 🌐 C# | 📅 2024-03-29 - Fast and versatile Micro-ORM.
* [NReco.Data](https://github.com/nreco/data) ⭐ 195 | 🐛 6 | 🌐 C# | 📅 2025-07-14 - Lightweight provider-independent DAL for SQL commands generation, CRUD operations and simple POCO mapping.
* [FreeSql](https://github.com/2881099/FreeSql) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-06-25 - a convenient ORM in dotnet,supports Mysql, Postgresql, SqlServer, Oracle and Sqlite.
* [Limebean](https://nick-lucas.github.io/LimeBean/) - Hybrid-ORM, designed to be simple to use and not totally hide SQL, while having all the nice things you expect from an ORM. Inspired by RedBeanPHP.
* [LINQ to DB (linq2db)](https://linq2db.github.io/) - The fastest LINQ database access library offering a simple, lightweight, fast, and type-safe layer between your POCO objects and your database for more than 10 database engines with full SQL support.

### Profiling

* [MiniProfiler](https://github.com/MiniProfiler/dotnet) ⭐ 3,009 | 🐛 75 | 🌐 C# | 📅 2025-08-03 - A simple but effective mini-profiler for ASP.NET websites.
* [Glimpse](https://github.com/Glimpse/Glimpse.Prototype) ⚠️ Archived - Lightweight, open-source, real-time diagnostics and insights profiler for .NET. `Unstable version`

### Query Builders

* [SqlKata](https://github.com/sqlkata/querybuilder) ⭐ 3,378 | 🐛 179 | 🌐 C# | 📅 2026-04-10 - Elegant Sql Query Builder, that supports complex queries, joins, sub queries, nested where conditions, vendor engine targets and more

### Queue and Messaging

* [MediatR](https://github.com/jbogard/MediatR) ⭐ 11,852 | 🐛 2 | 🌐 C# | 📅 2026-07-02 - Simple, unambitious mediator implementation in .NET.
* [EventStore](https://github.com/EventStore/EventStore) ⭐ 5,843 | 🐛 148 | 🌐 C# | 📅 2026-08-18 - The open-source, functional database with Complex Event Processing in JavaScript.
* [MQTTnet](https://github.com/chkr1011/MQTTnet) ⭐ 5,056 | 🐛 190 | 🌐 C# | 📅 2026-08-09 - MQTTnet is a high performance .NET library for MQTT based communication.
* [netmq](https://github.com/zeromq/netmq) ⭐ 3,179 | 🐛 135 | 🌐 C# | 📅 2026-07-30 - 100% native C# implementation of ZeroMQ for .NET.
* [EasyNetQ](https://github.com/EasyNetQ/EasyNetQ) ⭐ 3,057 | 🐛 1 | 🌐 C# | 📅 2026-08-06 - An easy to use .NET API for RabbitMQ.
* [Rebus](https://github.com/rebus-org/Rebus) ⭐ 2,655 | 🐛 22 | 🌐 C# | 📅 2026-08-18 - Simple and lean service bus implementation for .NET.
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) ⭐ 2,279 | 🐛 61 | 🌐 C# | 📅 2026-08-13 - RabbitMQ .NET client <https://www.rabbitmq.com>.
* [NServiceBus](https://github.com/particular/nservicebus) ⭐ 2,168 | 🐛 287 | 🌐 C# | 📅 2026-08-17 - NServiceBus is part of the [Particular Service Platform](https://particular.net/service-platform), which contains tools to build, monitor, and debug distributed systems.
* [Foundatio](https://github.com/exceptionless/Foundatio#queues) ⭐ 2,097 | 🐛 13 | 🌐 C# | 📅 2026-08-17 - A common interface with in memory, redis and azure implementations.
* [RawRabbit](https://github.com/pardahlman/RawRabbit) ⭐ 740 | 🐛 56 | 🌐 C# | 📅 2022-12-07 - Modern .NET framework for communication over RabbitMq.
* [Mediator.Net](https://github.com/mayuanyang/Mediator.Net) ⭐ 533 | 🐛 11 | 🌐 C# | 📅 2026-05-11 - A simple mediator for .Net for sending command, publishing event and request response with pipelines supported.
* [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) ⚠️ Archived - MediatR extensions for Microsoft.Extensions.DependencyInjection.
* [Silverback](https://github.com/BEagle1984/silverback) ⭐ 284 | 🐛 13 | 🌐 C# | 📅 2026-08-16 - Framework to build event-driven applications (support for Kafka, RabbitMQ, MQTT).
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus) ⭐ 211 | 🐛 10 | 🌐 C# | 📅 2020-07-10 - Simple in process mediator for .NET.
* [Tossit](https://github.com/turgayozgur/tossit) ⚠️ Archived - Simple, easy to use library for distributed job/worker logic. Distributed messages handled by built in RabbitMQ implementation.
* [OpenCQRS](https://github.com/OpenCQRS/OpenCQRS) ⭐ 28 | 🐛 14 | 🌐 C# | 📅 2026-05-17 - .NET Core library for DDD, CQRS and Event Sourcing with Azure Service Bus integration. Supported database providers for the Command and the Event stores are: DocumentDB, MongoDB, SQL Server, MySQL, PostgreSQL and SQLite.
* [emitter](https://emitter.io/) - Free open source real-time messaging service that connects all devices. This publish-subscribe messaging API is built for speed and security.
* [Restbus](http://restbus.org) - Messaging library for RabbitMq.

### Reporting

* [FastReport](https://github.com/FastReports/FastReport) ⭐ 3,085 | 🐛 24 | 🌐 C# | 📅 2026-06-11 - The open source report generator for .NET Core 2.x/.Net Framework 4.x. FastReport can be used in MVC, Web API applications.

### Scheduler and Job

* [HangfireIO](https://github.com/HangfireIO/Hangfire) ⭐ 10,118 | 🐛 945 | 🌐 C# | 📅 2026-07-20 - Easy way to perform fire-and-forget, delayed and recurring tasks inside ASP.NET apps <http://hangfire.io>.
* [quartznet](https://github.com/quartznet/quartznet/) ⭐ 7,067 | 🐛 27 | 🌐 C# | 📅 2026-08-15 - Quartz Enterprise Scheduler .NET <http://www.quartz-scheduler.net>.
* [stateless](https://github.com/dotnet-state-machine/stateless) ⭐ 6,238 | 🐛 81 | 🌐 C# | 📅 2026-04-04 - Simple library for creating state machines in C# code.
* [Coravel](https://github.com/jamesmh/coravel) ⭐ 4,284 | 🐛 84 | 🌐 C# | 📅 2025-07-20 - .Net Core meets Laravel: Scheduling, Queuing, etc.
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) ⭐ 2,774 | 🐛 21 | 🌐 C# | 📅 2026-03-19 - Automated job scheduler with fluent interface.
* [NCrontab](https://github.com/atifaziz/NCrontab) ⭐ 989 | 🐛 21 | 🌐 C# | 📅 2025-11-27 - Crontab for .NET.
* [Gofer.NET](https://github.com/brthor/Gofer.NET) ⭐ 561 | 🐛 16 | 🌐 C# | 📅 2022-12-08 - Easy C# API for Distributed Background Tasks/Jobs for .NET Core. Inspired by celery for python.
* [LiquidState](https://github.com/prasannavl/LiquidState) ⭐ 250 | 🐛 6 | 🌐 C# | 📅 2020-10-03 - Efficient asynchronous and synchronous state machines for .NET.
* [Chroniton.NetCore](https://github.com/leosperry/Chroniton) ⭐ 181 | 🐛 16 | 🌐 C# | 📅 2016-10-23 - Lightweight robust library for running tasks(jobs) on schedules.

### SDKs

* [octokit.net](https://github.com/octokit/octokit.net) ⭐ 2,857 | 🐛 42 | 🌐 C# | 📅 2026-08-17 - GitHub API client library for .NET.
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) ⭐ 2,412 | 🐛 187 | 🌐 C# | 📅 2025-08-28 - .NET (C#) Client Library for Docker API.
* [SendGrid-csharp](https://github.com/sendgrid/sendgrid-csharp) ⭐ 1,121 | 🐛 43 | 🌐 C# | 📅 2026-06-25 - C# client library for using the full SendGrid API.
* [google-cloud-dotnet](https://github.com/GoogleCloudPlatform/google-cloud-dotnet) ⭐ 1,089 | 🐛 18 | 🌐 C# | 📅 2026-08-18 - Google Cloud Client Libraries for .NET.
* [tweetinvi](https://github.com/linvi/tweetinvi) ⭐ 997 | 🐛 246 | 🌐 C# | 📅 2024-08-11 - Intuitive .NET C# library to access the Twitter REST and STREAM API.
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) ⚠️ Archived - .NET API for Consul.
* [csharp-nats](https://github.com/nats-io/csharp-nats) ⭐ 651 | 🐛 10 | 🌐 C# | 📅 2025-10-15 - C# .NET client for the NATS messaging system.
* [Microphone](https://github.com/rogeralsing/Microphone) ⚠️ Archived - Lightweight framework to run self hosting REST services using Web Api or NancyFx ontop of a Consul or ETCD cluster.
* [firebase-admin-dotnet](https://github.com/firebase/firebase-admin-dotnet) ⭐ 407 | 🐛 62 | 🌐 C# | 📅 2026-08-13 - Firebase Admin .NET SDK
* [AWS SDK](https://github.com/aws/aws-sdk-net) ⭐ 132 | 🐛 36 | 🌐 C# | 📅 2026-08-18 - The Amazon Web Services (AWS) .NET Core SDK components. Each AWS service has its own NuGet package.
* [Manatee.Trello](https://github.com/gregsdennis/Manatee.Trello) ⭐ 120 | 🐛 31 | 🌐 C# | 📅 2023-01-25 - A fully object-oriented .Net wrapper for Trello's RESTful API written in C#.
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client) ⚠️ Archived - .NET Standard compatible C# client to interface with Etsy's excellent [statsd](https://github.com/etsy/statsd) ⭐ 18,075 | 🐛 90 | 🌐 JavaScript | 📅 2025-05-20 server.
* [azure-event-hubs-dotnet](https://github.com/azure/azure-event-hubs-dotnet) ⚠️ Archived - .NET Standard client library for Azure Event Hubs.
* [DarkSkyCore](https://github.com/amweiss/dark-sky-core) ⚠️ Archived - A .NET Standard wrapper for the [Dark Sky API](https://darksky.net/dev/docs).
* [PreStorm](https://github.com/jshirota/PreStorm) ⭐ 16 | 🐛 2 | 🌐 C# | 📅 2022-06-22 - Parallel REST Client for ArcGIS Server.
* [CakeMail.RestClient](https://github.com/Jericho/CakeMail.RestClient) ⚠️ Archived - Client for CakeMail's API. Allows you to send transactional emails, bulk emails, manage lists and contacts, etc.
* Blockchain clients
  * [Binance.Net](https://github.com/JKorf/Binance.Net) ⭐ 1,173 | 🐛 11 | 🌐 C# | 📅 2026-08-14 - .Net API wrapper for the Binance web API.
  * [Bittrex.Net](https://github.com/JKorf/Bittrex.Net) - C# .Net wrapper for the Bittrex web API including all features easily accessible and usable.

### Security

* [Jwt.Net](https://github.com/jwt-dotnet/jwt) ⭐ 2,195 | 🐛 10 | 🌐 C# | 📅 2026-08-12 - Jwt.Net, a JWT (JSON Web Token) implementation for .NET.
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) ⭐ 1,708 | 🐛 17 | 🌐 C# | 📅 2026-08-18 - Cleans HTML to avoid XSS attacks.
* [Security](https://github.com/aspnet/Security) ⚠️ Archived - Middleware for security and authorization of web apps.
* [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) ⭐ 1,023 | 🐛 42 | 🌐 C# | 📅 2026-03-27 - Library for processing JOSE objects (JWT, JWA, JWS and related).
* [SecurityHeaders](https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders) ⭐ 855 | 🐛 3 | 🌐 C# | 📅 2026-07-22 - Small package to allow adding security headers to ASP.NET Core websites.
* [NWebsec](https://github.com/NWebsec/NWebsec) ⭐ 550 | 🐛 48 | 🌐 C# | 📅 2023-03-03 - Security libraries for ASP.NET <http://www.nwebsec.com>.
* [OwaspHeaders](https://github.com/GaProgMan/OwaspHeaders.Core) ⭐ 314 | 🐛 15 | 🌐 C# | 📅 2026-08-14 - .NET Core middleware for injecting the Owasp recommended HTTP Headers for increased security.
* [aspnetcore-security-headers](https://github.com/juunas11/aspnetcore-security-headers) ⭐ 276 | 🐛 37 | 🌐 C# | 📅 2025-03-27 - Middleware for adding security headers to an ASP.NET Core application.
* [roslyn-security-guard](https://github.com/dotnet-security-guard/roslyn-security-guard) ⚠️ Archived - Roslyn analyzers that aim to help security audit on .NET applications.
* [JWT Simple Server](https://github.com/Xabaril/JWTSimpleServer) ⚠️ Archived - A lightweight, dynamic jwt server for ASP.NET Core.
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) ⭐ 135 | 🐛 17 | 🌐 C# | 📅 2022-06-22 - reCAPTCHA 2.0 for ASP.NET Core.

### Searching

* [Elasticsearch.Net & NEST](https://github.com/elastic/elasticsearch-net) ⭐ 3,649 | 🐛 73 | 🌐 C# | 📅 2026-08-14 - Repository for both NEST and Elasticsearch.NET, the two official elasticsearch .NET clients.
* [SearchExtensions](https://github.com/ninjanye/SearchExtensions) ⭐ 342 | 🐛 21 | 🌐 C# | 📅 2024-07-05 - Advanced search capabilities for IQueryable interfaces, such as Entity Framework queries.
* [AutoComplete](https://github.com/omerfarukz/autocomplete) ⭐ 226 | 🐛 0 | 🌐 C# | 📅 2025-10-22 - Persistent, simple, powerful and portable autocomplete library.
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD) ⭐ 177 | 🐛 33 | 🌐 C# | 📅 2020-10-01 - Elasticsearch .NET API.
* [SimMetrics.Net](https://github.com/StefH/SimMetrics.Net) ⭐ 149 | 🐛 4 | 🌐 C# | 📅 2026-01-14 - A Similarity Metric Library, e.g. from edit distance's (Levenshtein, Gotoh, Jaro etc) to other metrics, (e.g Soundex, Chapman)
* [Algolia.Search](https://github.com/algolia/algoliasearch-client-csharp) ⭐ 128 | 🐛 5 | 🌐 C# | 📅 2026-08-18 - Repository for the official Algolia .NET client.
* [SolrExpress](https://github.com/solr-express/solr-express) ⚠️ Archived - Simple and lightweight query .NET library for Solr, in a controlled, buildable and fail fast way.

### Serialization

* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) ⭐ 11,310 | 🐛 826 | 🌐 C# | 📅 2026-08-13 - Popular high-performance JSON framework for .NET.
* [CsvHelper](https://github.com/JoshClose/CsvHelper) ⭐ 5,208 | 🐛 353 | 🌐 C# | 📅 2025-06-27 - Library to help reading and writing CSV files.
* [protobuf-net](https://github.com/mgravell/protobuf-net/) ⭐ 4,967 | 🐛 538 | 🌐 C# | 📅 2026-08-19 - Protocol Buffers library for idiomatic .NET.
* [YamlDotNet](https://github.com/aaubry/YamlDotNet) ⭐ 2,851 | 🐛 139 | 🌐 C# | 📅 2026-06-26 - .NET
* [bond](https://github.com/Microsoft/bond) ⚠️ Archived - Cross-platform framework for working with schematized data. It supports cross-language de/serialization and powerful generic mechanisms for efficiently manipulating data. Bond is broadly used at Microsoft in high scale services.
* [ZeroFormatter](https://github.com/neuecc/ZeroFormatter) ⚠️ Archived - Fast binary (de)serializer for .NET.
* [Utf8Json](https://github.com/neuecc/Utf8Json) ⚠️ Archived - Definitely Fastest and Zero Allocation JSON Serializer for C#(NET, .NET Core, Unity, Xamarin).
* [Jil](https://github.com/kevin-montrose/Jil) ⭐ 2,140 | 🐛 54 | 🌐 C# | 📅 2024-04-17 - Fast .NET JSON (De)Serializer, Built On Sigil.
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) ⚠️ Archived - JSON, JSV and CSV Text Serializers.
* [Schema.NET](https://github.com/RehanSaeed/Schema.NET) ⭐ 686 | 🐛 66 | 🌐 C# | 📅 2026-08-17 - Schema.org objects turned into strongly typed C# POCO classes for use in .NET. All classes can be serialized into JSON/JSON-LD and XML, typically used to represent structured data in the head section of html page.
* [Edi.Net](https://github.com/indice-co/EDI.Net) ⭐ 491 | 🐛 89 | 🌐 C# | 📅 2025-12-01 - EDI Serializer/Deserializer. Supports EDIFact, X12 and TRADACOMS format.
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser) ⭐ 404 | 🐛 0 | 🌐 C# | 📅 2026-07-16 - Easy to use, easy to extend and high-performance library for CSV parsing with .NET.
* [Wire](https://github.com/rogeralsing/Wire) ⭐ 374 | 🐛 1 | 🌐 C# | 📅 2022-12-08 - Binary serializer for POCO objects.
* [ExtendedXmlSerializer](https://github.com/wojtpl2/ExtendedXmlSerializer) ⭐ 344 | 🐛 4 | 🌐 C# | 📅 2026-01-26 - Extended Xml Serializer for .NET.
* [BinarySerializer](https://github.com/jefffhaynes/BinarySerializer) ⭐ 313 | 🐛 53 | 🌐 C# | 📅 2026-04-07 - Serialization for custom packet and protocol formats, supports bit-twiddling.
* [Channels](https://github.com/davidfowl/Channels) ⚠️ Archived - Push based .NET Streams.
* [YAXLib](https://github.com/sinairv/YAXLib) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2021-08-27 - XML Serialization Library for the .NET Framework and .NET Core. Extremely flexible and powerful.
* MessagePack
  * [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp) ⭐ 6,772 | 🐛 146 | 🌐 C# | 📅 2026-08-14 - Extremely Fast MessagePack Serializer for C#(.NET, .NET Core, Unity, Xamarin).
  * [msgpack-cli](https://github.com/msgpack/msgpack-cli) ⭐ 858 | 🐛 85 | 🌐 C# | 📅 2024-07-12 - MessagePack implementation for Common Language Infrastructure / [msgpack.org](http://msgpack.org).

### Template Engine

* [Scriban](https://github.com/lunet-io/scriban) ⭐ 3,956 | 🐛 0 | 🌐 C# | 📅 2026-07-29 - A fast, powerful, safe and lightweight text templating language and engine for .NET.
* [fluid](https://github.com/sebastienros/fluid) ⭐ 1,770 | 🐛 35 | 🌐 C# | 📅 2026-08-19 - Open-source .NET template engine that is as close as possible to the Liquid template language.
* [RazorLight](https://github.com/toddams/RazorLight) ⭐ 1,661 | 🐛 77 | 🌐 C# | 📅 2024-07-06 - Template engine based on Microsoft's Razor parsing engine for .NET Core.
* [dotliquid](https://github.com/dotliquid/dotliquid) ⭐ 1,095 | 🐛 63 | 🌐 C# | 📅 2025-04-02 - .NET Port of Tobias Lütke's Liquid template language.
* [Razor](https://github.com/aspnet/Razor) ⚠️ Archived - Parser and code generator for CSHTML files used in view pages for MVC web apps.
* [Portable.Xaml](https://github.com/cwensley/Portable.Xaml) ⭐ 161 | 🐛 8 | 🌐 C# | 📅 2023-09-04 - Portable .NET library for reading/writing xaml files.

### Testing

* [Bogus](https://github.com/bchavez/Bogus) ⭐ 9,727 | 🐛 91 | 🌐 C# | 📅 2025-12-22 - Simple and sane fake data generator for C#. Based on and ported from the famed faker.js.
* [moq.netcore](https://github.com/Moq/moq4) ⭐ 6,402 | 🐛 20 | 🌐 C# | 📅 2026-08-17 - Most popular and friendly mocking framework for .NET.
* [xUnit.net](https://github.com/xunit/xunit) ⭐ 4,599 | 🐛 42 | 🌐 C# | 📅 2026-08-17 - A free, open source, community-focused unit testing tool for the .NET Framework.
* [FluentAssertions](https://github.com/fluentassertions/fluentassertions) ⭐ 3,816 | 🐛 69 | 🌐 C# | 📅 2026-08-19 - Set of .NET extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style test.
* [shouldly](https://github.com/shouldly/shouldly) ⭐ 3,406 | 🐛 88 | 🌐 C# | 📅 2026-08-18 - Should testing for .NET - the way Asserting *Should* be! <http://shouldly.readthedocs.org/en/latest>
* [NSubstitute](https://github.com/nsubstitute/NSubstitute) ⭐ 2,970 | 🐛 110 | 🌐 C# | 📅 2026-08-17 - A friendly substitute for .NET mocking frameworks.
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy) ⭐ 1,845 | 🐛 4 | 🌐 C# | 📅 2026-08-17 - The easy mocking library for .NET.
* [mockhttp](https://github.com/richardszalay/mockhttp) ⭐ 1,766 | 🐛 16 | 🌐 C# | 📅 2026-08-08 - Testing layer for Microsoft's HttpClient library.
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) ⭐ 1,711 | 🐛 172 | 🌐 C# | 📅 2025-03-04 - Fluent testing
  framework for ASP.NET Core MVC.
* [Netling](https://github.com/hallatore/Netling) ⭐ 1,347 | 🐛 13 | 🌐 C# | 📅 2022-12-05 - Load tester client for easy web testing.
* [MSpec](https://github.com/machine/machine.specifications) ⭐ 898 | 🐛 33 | 🌐 C# | 📅 2026-07-17 - Popular testing framework for writing BDD-style tests.
* [GenFu](https://github.com/MisterJames/GenFu) ⭐ 831 | 🐛 49 | 🌐 C# | 📅 2022-11-30 - Library you can use to generate realistic test data.
* [Atata](https://github.com/atata-framework/atata) ⭐ 501 | 🐛 10 | 🌐 C# | 📅 2026-08-08 - Web UI test automation full-featured framework based on Selenium WebDriver. <https://atata.io>
* [LightBDD](https://github.com/LightBDD/LightBDD) ⭐ 476 | 🐛 24 | 🌐 C# | 📅 2026-06-27 - BDD framework allowing to create easy to read and maintain tests.
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) ⭐ 434 | 🐛 21 | 🌐 C# | 📅 2026-06-10 - The simplest BDD framework EVER!
* [xBehave.net](https://github.com/xbehave/xbehave.net) ⚠️ Archived - An xUnit.net extension for describing your tests using natural language. <http://xbehave.github.io>
* [Storyteller](https://github.com/storyteller/Storyteller) ⭐ 269 | 🐛 59 | 🌐 JavaScript | 📅 2022-12-08 - Executable Specifications for .NET <http://storyteller.github.io>.
* [NSpec](https://github.com/nspec/NSpec) ⭐ 260 | 🐛 31 | 🌐 C# | 📅 2022-06-22 - Battle hardened testing framework for C# that's heavily inspired by Mocha and RSpec.
* [nunit](https://github.com/nunit/dotnet-test-nunit) ⚠️ Archived - NUnit test runner for .NET Core.
* [Testavior](https://github.com/geeklearningio/Testavior) ⭐ 41 | 🐛 4 | 🌐 C# | 📅 2023-04-17 - Testavior is a lightweight solution to help you develop Behavior Tests for ASP.NET Core.
* [CoreBDD](https://github.com/stevenknox/CoreBDD) ⭐ 18 | 🐛 7 | 🌐 C# | 📅 2020-02-18 - BDD framework for xUnit.net
* [SpecFlow](https://github.com/techtalk/SpecFlow) - Pragmatic BDD solution for .NET. It uses the Gherkin specification language and integrates to Visual Studio.
* [Stubbery](https://markvincze.github.io/Stubbery/) - A simple library for creating and running Api stubs in .NET.

### Tools

* [ShareX](https://github.com/ShareX/ShareX) ⭐ 39,195 | 🐛 664 | 🌐 C# | 📅 2026-08-18 - Free and open source program that lets you capture or record any area of your screen and share it with a single press of a key. It also allows uploading images, text or other types of files to over 80 supported destinations you can choose from. <https://getsharex.com>

* [scoop](https://github.com/lukesampson/scoop) ⭐ 24,555 | 🐛 541 | 🌐 PowerShell | 📅 2026-06-13 - A command-line installer for Windows.

* [mRemoteNG](https://github.com/mRemoteNG/mRemoteNG) ⭐ 11,056 | 🐛 868 | 🌐 C# | 📅 2026-08-18 - The next generation of mRemote, open source, tabbed, multi-protocol, remote connections manager

* [gitignore.io](https://github.com/joeblau/gitignore.io) ⭐ 8,734 | 🐛 69 | 🌐 Swift | 📅 2024-12-23 - Create useful .gitignore files for your project <https://www.gitignore.io>.

* [letsencrypt-win-simple](https://github.com/Lone-Coder/letsencrypt-win-simple) ⭐ 5,779 | 🐛 44 | 🌐 C# | 📅 2026-06-09 - A Simple ACME Client for Windows.

* [OctoLinker](https://github.com/OctoLinker/browser-extension) ⭐ 5,384 | 🐛 62 | 🌐 HTML | 📅 2023-10-02 - Navigate through `projects.json` files efficiently with the OctoLinker browser extension for GitHub.

* [docfx](https://github.com/dotnet/docfx) ⭐ 4,445 | 🐛 450 | 🌐 C# | 📅 2026-08-19 - Tools for building and publishing API documentation for .NET projects <http://dotnet.github.io/docfx>

* [SharpZipLib](https://github.com/icsharpcode/SharpZipLib) ⭐ 3,925 | 🐛 118 | 🌐 C# | 📅 2024-09-03 - #ziplib is a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform.

* [System.CommandLine](https://github.com/dotnet/command-line-api) ⭐ 3,672 | 🐛 481 | 🌐 C# | 📅 2026-08-19 - System.CommandLine, a set of libraries for command line parsing, invocation, and rendering of terminal output.

* [SharpLab](https://github.com/ashmind/SharpLab) ⭐ 2,973 | 🐛 488 | 🌐 C# | 📅 2024-11-18 - .NET code playground that shows intermediate steps and results of code compilation. <https://sharplab.io>

* [NuGetPackageExplorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer) ⭐ 2,546 | 🐛 108 | 🌐 C# | 📅 2026-08-05 - Create, update and deploy Nuget Packages with a GUI.

* [CommandLineUtils](https://github.com/natemcmaster/CommandLineUtils) ⭐ 2,274 | 🐛 7 | 🌐 C# | 📅 2026-07-01 - Command line parsing and utilities for .NET Core and .NET Framework.

* [CliFx](https://github.com/Tyrrrz/CliFx) ⭐ 1,613 | 🐛 4 | 🌐 C# | 📅 2026-08-01 - Declarative framework for building command line interfaces.

* [NJsonSchema](https://github.com/RSuter/NJsonSchema) ⭐ 1,581 | 🐛 442 | 🌐 C# | 📅 2026-06-20 - NJsonSchema is a .NET library to read, generate and validate JSON Schema draft v4+ schemas.

* [dotnet-tools](https://github.com/natemcmaster/dotnet-tools) ⚠️ Archived - A list of tool extensions for .NET Core Command Line (dotnet CLI).
  * [LibMan CLI](https://github.com/aspnet/LibraryManager) ⭐ 485 | 🐛 93 | 🌐 C# | 📅 2026-06-28 - Client-side content manager for web apps.

* [sourcelink](https://github.com/dotnet/sourcelink) ⭐ 1,349 | 🐛 142 | 🌐 C# | 📅 2026-08-19 - SourceLink is a language- and source-control agnostic system for providing first-class source debugging experiences for binaries.

* [Linq\_Faster](https://github.com/jackmott/LinqFaster) ⭐ 761 | 🐛 16 | 🌐 C# | 📅 2025-09-26 - Linq-like extension functions for Arrays, Span<T>, and List<T> that are faster and allocate less.

* [Rin](https://github.com/mayuki/Rin) ⭐ 665 | 🐛 13 | 🌐 C# | 📅 2024-02-03 - Request/response Inspector middleware for ASP.NET Core. like Glimpse.

* [SmartCode](https://github.com/Ahoo-Wang/SmartCode) ⭐ 578 | 🐛 16 | 🌐 C# | 📅 2023-12-15 – SmartCode= IDataSource -> IBuildTask -> IOutput => Build Everything!!! (Including \[Code generator])

* [NuKeeper](https://github.com/NuKeeperDotNet/NuKeeper) ⚠️ Archived - Automagically update nuget packages in .NET projects.

* [Fake JSON Server](https://github.com/ttu/dotnet-fake-json-server) ⭐ 407 | 🐛 9 | 🌐 C# | 📅 2026-03-30 - Fake REST API for prototyping or as a CRUD Back End. No need to define types, uses dynamic typing. Data is stored to a single JSON file. Has authentication, WebSocket notifications, async long running operations, random generation for errors/delays and experimental GraphQL support.

* [SerilogAnalyzer](https://github.com/Suchiman/SerilogAnalyzer) ⭐ 313 | 🐛 23 | 🌐 C# | 📅 2024-04-02 - Roslyn-based analysis for code using the Serilog logging library. Checks for common mistakes and usage problems.

* [Typin](https://github.com/adambajguz/Typin) ⭐ 252 | 🐛 32 | 🌐 C# | 📅 2025-06-18 - Simple to use declarative framework for interactive CLI applications and command line tools (direct mode) that has its roots in CliFx.

* [EntryPoint](https://github.com/Nick-Lucas/EntryPoint) ⭐ 139 | 🐛 3 | 🌐 C# | 📅 2019-07-22 - Composable CLI (Command Line) Argument Parser for .Net Core & .Net Framework 4.5+.

* [ICanHasDotnetCore](https://github.com/OctopusDeploy/ICanHasDotnetCore) ⚠️ Archived - Scans uploaded packages.config files or GitHub repository and determines whether the nuget packages target .NET Standard.

* [posh-dotnet](https://github.com/bergmeister/posh-dotnet) ⭐ 48 | 🐛 3 | 🌐 PowerShell | 📅 2017-11-27 - `PowerShell` tab completion for the [dotnet CLI](https://github.com/dotnet/cli) ⚠️ Archived.

* [X.Web.RSS](https://github.com/dncuug/X.Web.RSS) ⭐ 28 | 🐛 0 | 🌐 C# | 📅 2026-08-17 – Simple RSS Feed generator for .NET and .NET Core

* [NugetVisualizer](https://github.com/sepharg/NugetVisualizer) ⭐ 21 | 🐛 2 | 🌐 JavaScript | 📅 2018-01-19 - Visualize all of the nuget packages and their corresponding versions for a set of given git repositories or folders.

* [X.Web.Sitemap](https://github.com/dncuug/X.Web.Sitemap) ⭐ 5 | 🐛 3 | 🌐 C# | 📅 2024-11-25 – Simple sitemap generator for .NET and .NET Core

* [dotnetfiddle](https://dotnetfiddle.net) - .NET sandbox for developers to quickly try out code and share code snippets.

* [json2csharp](http://json2csharp.com) - Generate C# classes from JSON.

### Web Framework

* [ReactJS.NET](https://github.com/reactjs/React.NET) ⭐ 2,324 | 🐛 113 | 🌐 C# | 📅 2026-03-02 - .NET library for JSX compilation and server-side rendering of React components.
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET) ⭐ 708 | 🐛 29 | 🌐 C# | 📅 2021-07-28 - Predictable state container for .NET apps. Inspired by <https://github.com/reactjs/redux> ⭐ 61,507 | 🐛 51 | 🌐 TypeScript | 📅 2026-08-02.
* WebAssembly
  * [Blazor](https://github.com/SteveSanderson/Blazor) ⭐ 1,677 | 🐛 7 | 🌐 C# | 📅 2018-02-23 - UI framework running .NET in the browser via WebAssembly.
    * [Awesome Blazor](https://github.com/AdrienTorris/awesome-blazor) ⭐ 9,368 | 🐛 96 | 📅 2026-07-25 - Collection of awesome resources (samples, components, articles, videos and others) about Blazor.
    * [Blazor Redux](https://github.com/torhovland/blazor-redux) ⭐ 480 | 🐛 10 | 🌐 C# | 📅 2022-10-05 - Connecting a Redux state store with Blazor.
  * [Ooui](https://github.com/praeclarum/Ooui) ⭐ 1,621 | 🐛 110 | 🌐 C# | 📅 2022-12-07 - Small cross-platform UI library that brings the simplicity of native UI development to the web.

### Web Socket

* [SuperSocket](https://github.com/kerryjiang/SuperSocket) ⭐ 4,231 | 🐛 211 | 🌐 C# | 📅 2026-04-04 - Light weight, cross platform and extensible socket server application framework.
* [Fleck](https://github.com/statianzo/Fleck) ⭐ 2,439 | 🐛 83 | 🌐 C# | 📅 2024-07-03 - Fleck is a WebSocket server implementation in C#. Fleck requires no inheritance, container, or additional references.
* [SignalR Server](https://github.com/aspnet/signalr) ⚠️ Archived - Real-time web functionality for web apps, including server-side push.
* [websocket-manager](https://github.com/radu-matei/websocket-manager) ⭐ 455 | 🐛 34 | 🌐 C# | 📅 2020-12-31 - Real-Time library for ASP .NET Core.
* [WampSharp](https://github.com/Code-Sharp/WampSharp) ⭐ 388 | 🐛 36 | 🌐 C# | 📅 2025-08-26 - C# implementation of [The Web Application Messaging Protocol](http://wamp-proto.org/) - Protocol that provides messaging patterns of Remote Procedure Calls and Publish/Subscribe over WebSockets.

### Windows Service

* [Topshelf](https://github.com/Topshelf/Topshelf) ⚠️ Archived - Easy service hosting framework for building Windows services using .NET.
* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service) ⭐ 452 | 🐛 9 | 🌐 C# | 📅 2019-11-06 - Set up and run as Windows Service directly from .NET Core.

### Workflow

* [workflow-core](https://github.com/danielgerlag/workflow-core) ⭐ 5,913 | 🐛 219 | 🌐 C# | 📅 2026-07-15 - Lightweight workflow engine for .NET Standard.
* [WorkflowEngine.NET](https://github.com/optimajet/WorkflowEngine.NET) ⭐ 989 | 🐛 68 | 🌐 C# | 📅 2026-08-18 - Component that adds workflow in your application.
* [Wexflow](https://github.com/aelassas/Wexflow) ⭐ 839 | 🐛 0 | 🌐 C# | 📅 2026-07-17 - A high performance, extensible, modular and cross-platform workflow engine.
* [CoreWF](https://github.com/dmetzgar/corewf/) ⭐ 18 | 🐛 0 | 🌐 C# | 📅 2020-04-02 - Port of Windows Workflow Foundation (WF) to .NET Core.

## Roadmaps

* [ASP.NET Core Developer Roadmap](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap) ⭐ 19,633 | 🐛 4 | 📅 2026-01-29 - Roadmap to becoming an ASP.NET Core developer in 2019.

## Starter Kits

* [bitwarden-core](https://github.com/bitwarden/core) ⭐ 19,899 | 🐛 215 | 🌐 C# | 📅 2026-08-19 - The core infrastructure backend (API, database, etc) <https://bitwarden.com>.
* [aspnetcore-spa generator](https://github.com/aspnet/JavaScriptServices) ⚠️ Archived - Yeoman generator to build a brand-new ASP.NET Core single page application that uses Angular 2 / React / React With Redux / Knockout / Aurelia on the client.
* [AspNetCore-Angular2-Universal](https://github.com/MarkPieszak/aspnetcore-angular2-universal) ⭐ 1,444 | 🐛 109 | 🌐 TypeScript | 📅 2019-05-26 - Cross-platform - w/ server-side rendering for SEO, Bootstrap, i18n internationalization (ngx-translate), Webpack, TypeScript, unit testing w/ Karma, WebAPI REST setup, SignalR, Swagger docs, and more!
* [dotNetify](https://github.com/dsuryd/dotNetify) ⭐ 1,200 | 🐛 5 | 🌐 JavaScript | 📅 2025-07-19 - Simple, lightweight, yet powerful way to build real-time HTML5/C# .NET web apps.
* [ASP.Net Core Vue Starter](https://github.com/MarkPieszak/aspnetcore-Vue-starter) ⭐ 1,197 | 🐛 41 | 🌐 Vue | 📅 2019-10-16 - Asp.NETCore 2.0 Vue 2 (ES6) SPA Starter kit, contains routing, Vuex, and more!.
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) ⭐ 1,165 | 🐛 45 | 🌐 JavaScript | 📅 2022-11-22 - Opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors.
* [saaskit](https://github.com/saaskit/saaskit) ⭐ 1,126 | 🐛 31 | 🌐 C# | 📅 2023-08-15 - Developer toolkit for building SaaS applications.
* [generator-aspnet](https://github.com/OmniSharp/generator-aspnet) ⚠️ Archived - yo generator for ASP.NET Core.
* [Nucleus](https://github.com/alirizaadiyahsi/Nucleus) ⭐ 351 | 🐛 7 | 🌐 C# | 📅 2025-05-11 - Vue startup application template that uses ASP.NET Core API layered architecture at the back-end and JWT based authentication
* [react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) ⭐ 280 | 🐛 13 | 🌐 JavaScript | 📅 2018-05-22 - Starting point for building isomorphic React applications with ASP.NET Core 1, leveraging existing techniques.
* [serverlessDotNetStarter](https://github.com/pharindoko/serverlessDotNetStarter) ⭐ 54 | 🐛 2 | 🌐 C# | 📅 2023-02-11 starter kit for development and deployment of lambda functions in the AWS cloud based on serverless framework.
* [Arch](https://github.com/Arch) - The collection of .NET Core libraries that are created by software architects who embrace all the new stuff in .NET Core.
  * [AutoHistory](https://github.com/Arch/AutoHistory) ⭐ 791 | 🐛 26 | 🌐 C# | 📅 2023-04-04 - A plugin for Microsoft.EntityFrameworkCore to support automatically recording data changes history.

## Sample Projects

* Microservices & Service Mesh
  * [eShop](https://github.com/dotnet/eShop) ⭐ 10,780 | 🐛 185 | 🌐 C# | 📅 2026-08-18 - A reference .NET application implementing an eCommerce site.
  * [coolstore-microservices ](https://github.com/vietnam-devs/coolstore-microservices) ⭐ 2,531 | 🐛 32 | 🌐 C# | 📅 2023-03-07 - A Kubernetes-based polyglot microservices application with Istio service mesh
  * [Practical.CleanArchitecture](https://github.com/phongnguyend/Practical.CleanArchitecture) ⭐ 2,454 | 🐛 41 | 🌐 C# | 📅 2026-08-04 - Full-stack .Net 8 Clean Architecture (Microservices, Modular Monolith, Monolith), Blazor, Angular 18, React 18, Vue 3, BFF with YARP, Domain-Driven Design, CQRS, SOLID, Asp.Net Core Identity Custom Storage, OpenID Connect, Entity Framework Core, OpenTelemetry, SignalR, Hosted Services, Health Checks, Rate Limiting, Cloud Services (Azure, AWS, GCP).
  * [dotnetcore-microservices-poc](https://github.com/asc-lab/dotnetcore-microservices-poc) ⭐ 1,939 | 🐛 8 | 🌐 CSS | 📅 2025-09-16 -  simplified insurance sales system made in a microservices architecture using .NET Core (EF Core, MediatR, Marten, Eureka, Ocelot, RabbitMQ, Polly, ElasticSearch, Dapper) with blog post series.
  * [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) ⭐ 1,857 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-18 - Real-time trading platform demo showcasing reactive programming principles applied across the full application stack.
  * [clean-architecture-dotnet](https://github.com/thangchung/clean-architecture-dotnet) ⭐ 1,357 | 🐛 12 | 🌐 C# | 📅 2023-04-27 - Apply Minimal Clean Architecture with DDD-lite, CQRS-lite, and just enough Cloud-native patterns on eCommerce sample business domain
  * [practical-dapr](https://github.com/thangchung/practical-dapr) ⭐ 300 | 🐛 4 | 🌐 C# | 📅 2023-07-05 - Full-stack .NET microservices build on Dapr and Tye.
  * [magazine-website](https://github.com/thangchung/magazine-website) ⭐ 180 | 🐛 14 | 🌐 C# | 📅 2020-10-03 - Magazine website (using .NET Core, ASP.NET Core, EF Core) with DDD, CQRS, microservices, asynchronous programming applied.
  * [InMemoryCQRSReplication](https://github.com/Aaronontheweb/InMemoryCQRSReplication) ⭐ 148 | 🐛 10 | 🌐 C# | 📅 2026-04-22 - Akka.NET Reference Architecture - CQRS + Sharding + In-Memory Replication
  * [microservices-in-dotnetcore](https://github.com/horsdal/microservices-in-dotnet-book-second-edition) ⭐ 96 | 🐛 5 | 🌐 C# | 📅 2022-05-30 - The code sample from the second edition of [Microservices in .NET Core](https://www.manning.com/books/microservices-in-net-core-second-edition).
  * [distributed-playground](https://github.com/jvandevelde/distributed-playground) ⭐ 42 | 🐛 0 | 🌐 Shell | 📅 2016-04-16 - Distributed service playground with Vagrant, Consul, Docker & ASP.NET Core.
  * [DNC-DShop](https://github.com/devmentors) - Distributed .NET Core project and free course. (DDD, CQRS, RabbitMQ, MongoDB, Redis, Monitoring, Logging, CI, CD)
* Monoliths
  * [MusicStore](https://github.com/dotnet/aspnetcore/tree/master/src/MusicStore) ⭐ 38,375 | 🐛 4,108 | 🌐 C# | 📅 2026-08-19 - Sample MusicStore application that uses MVC and Entity Framework.
  * [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) ⚠️ Archived - A layered application architecture with monolithic deployment model.
  * [Practical ASP.NET Core](https://github.com/dodyg/practical-aspnetcore) ⭐ 10,408 | 🐛 177 | 🌐 C# | 📅 2026-08-14 - A daily updated micro samples of ASP.NET Core features and facilities.
  * [EquinoxProject](https://github.com/EduardoPires/EquinoxProject) ⭐ 6,775 | 🐛 6 | 🌐 C# | 📅 2026-04-14 - Full ASP.NET Core 2.0 application with DDD, CQRS and Event Sourcing.
  * [NorthwindTraders](https://github.com/JasonGT/NorthwindTraders) ⚠️ Archived - Northwind Traders is a sample application built using ASP.NET Core and Entity Framework Core.
  * [Clean Architecture Manga](https://github.com/ivanpaulovich/clean-architecture-manga) ⭐ 4,353 | 🐛 45 | 🌐 C# | 📅 2026-06-22 - Clean Architecture sample with .NET Core 3.0 and C# 8. Use cases as central organising structure, completely testable, decoupled from frameworks.
  * [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) ⭐ 3,061 | 🐛 13 | 🌐 C# | 📅 2024-02-27 - .NET Core REST API CQRS implementation with raw SQL and DDD using Clean Architecture.
  * [Practical.CleanArchitecture](https://github.com/phongnguyend/Practical.CleanArchitecture) ⭐ 2,454 | 🐛 41 | 🌐 C# | 📅 2026-08-04 - Full-stack .Net 8 Clean Architecture (Microservices, Modular Monolith, Monolith), Blazor, Angular 18, React 18, Vue 3, BFF with YARP, Domain-Driven Design, CQRS, SOLID, Asp.Net Core Identity Custom Storage, OpenID Connect, Entity Framework Core, OpenTelemetry, SignalR, Hosted Services, Health Checks, Rate Limiting, Cloud Services (Azure, AWS, GCP).
  * [AspNetAuthorizationWorkshop](https://github.com/blowdart/AspNetAuthorizationWorkshop) ⚠️ Archived - A workshop for moving through the various new pieces in ASP.NET Core Authorization
  * [allReady](https://github.com/HTBox/allReady) ⭐ 886 | 🐛 255 | 🌐 C# | 📅 2022-12-09 - Open-source solution focused on increasing awareness, efficiency and impact of preparedness campaigns as they are delivered by humanitarian and disaster response organizations in local communities. <http://www.htbox.org/projects/allready>
  * [StarWars](https://github.com/JacekKosciesza/StarWars) ⚠️ Archived - GraphQL 'Star Wars' example using GraphQL for .NET, ASP.NET Core, Entity Framework Core.
  * [Entropy](https://github.com/aspnet/Entropy) ⚠️ Archived - Chaotic experimental playground for new features and ideas - check here for small and simple samples for individual features.
  * [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext) ⭐ 502 | 🐛 5 | 🌐 JavaScript | 📅 2024-05-16 - West Wind Album Viewer ASP.NET 5 Sample.
  * [BikeSharing360 Suite of Apps from Microsoft](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/) Presented December Connect 2016 Conference, a compreshsive set of interworking apps for both enterprise users and the consumers (bike riders): [Mobile Apps](https://github.com/Microsoft/BikeSharing360_MobileApps) ⚠️ Archived, [Backend Services](https://github.com/Microsoft/BikeSharing360_BackendServices) ⚠️ Archived, [Websites](https://github.com/Microsoft/BikeSharing360_Websites) ⚠️ Archived, [Single Container Apps](https://github.com/Microsoft/BikeSharing360_SingleContainer) ⚠️ Archived, [Multi Container Apps](https://github.com/Microsoft/BikeSharing360_MultiContainer) ⚠️ Archived, [Cognitive Services Kiosk App](https://github.com/Microsoft/BikeSharing360_CognitiveServicesKioskApp) ⚠️ Archived,
    [Azure Bot App](https://github.com/Microsoft/BikeSharing360_BotApps) ⚠️ Archived.
  * [Orchard Core - Modular and Multi-tenant applications](https://github.com/OrchardCMS/OrchardCore.Samples) ⭐ 416 | 🐛 10 | 🌐 C# | 📅 2026-07-10 - Use Orchard Core Framework to create Modular and Multi-tenant applications.
  * [PhotoGallery](https://github.com/chsakell/aspnet5-angular2-typescript) ⭐ 345 | 🐛 4 | 🌐 C# | 📅 2019-03-25 - Cross-platform Single Page Applications with ASP.NET Core, Angular 2 & TypeScript <http://wp.me/p3mRWu-11L>.
  * [aspnet-servicediscovery-patterns](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) ⭐ 296 | 🐛 3 | 🌐 C# | 📅 2017-12-30 - Samples of implementing Service Discovery patterns with ASP.NET Core.
  * [DotNetClub](https://github.com/scheshan/DotNetClub) ⭐ 230 | 🐛 3 | 🌐 C# | 📅 2018-01-24 - Tiny club written in ASP.NET Core.
  * [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) ⭐ 154 | 🐛 2 | 🌐 C# | 📅 2018-08-23 - NLayerAppV3 N-Layered Architecture with .NET Core Preview 2.
  * [GenVue](https://github.com/herbat73/GenVue) ⭐ 134 | 🐛 3 | 🌐 C# | 📅 2018-11-27 - a hostable, web application that lets confidential users upload and share private files build on Vue.js, Vuetifyjs and NetCore WebAPI stack
  * [JustA.ML](https://github.com/mustakimali/JustA.ML) ⭐ 89 | 🐛 3 | 🌐 C# | 📅 2026-04-26 - A web application that lets you share files/URL/text between your devices written in ASP.NET Core 2.0. Open source, live at <https://justa.ml>
  * [CoreCodeCamp](https://github.com/shawnwildermuth/CoreCodeCamp) ⭐ 74 | 🐛 4 | 🌐 HTML | 📅 2022-08-01 - An Open Source Website for running small, local development events.
  * [guidance-identity-management-for-multitenant-apps](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps) ⚠️ Archived - How to manage user identities in a multitenant app on Microsoft Azure, using Azure Active Directory for authentication.
  * [PokeR](https://github.com/halomademeapc/pokeR) ⭐ 46 | 🐛 8 | 🌐 TypeScript | 📅 2023-02-04 - Realtime scrum poker using SignalR and Angular in ASP.NET Core's SPA hosting.  Includes Docker support. [Demo](https://planning.halomademeapc.com)
  * [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch) ⭐ 37 | 🐛 1 | 🌐 C# | 📅 2017-02-12 - ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger.
  * [MegaMine](https://github.com/Nootus/MegaMine) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2017-10-22 - Open source mining solution that helps miners in extracting Gold, Quartz, Granite etc. This solution is built using ASP.NET Core and AngularJS utilizing multiple light weight components in a Microservices way.
  * [cloudscribe](https://github.com/cloudscribe/cloudscribe) - ASP.NET Core Multi-tenant web application foundation.

## Articles

* Basic knowledge
  * The comparison between .NET Core and Nodejs at [here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/), [here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2) and [here](https://github.com/thinktecture/nodejs-aspnetcore-webapi) ⭐ 45 | 🐛 1 | 🌐 JavaScript | 📅 2016-04-02
  * [Microsoft architectural overview of comprehensive BikeSharing360 suite of demo apps with related videos](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)
  * [Porting a .NET Framework library to .NET Core](https://www.codeproject.com/Articles/1190475/Porting-a-NET-Framework-library-to-NET-Core)
  * [The 68 things the CLR does before executing a single line of your code](http://mattwarren.org/2017/02/07/The-68-things-the-CLR-does-before-executing-a-single-line-of-your-code/)
  * [Understanding ASP.NET Core Initialization](http://developer.telerik.com/featured/understanding-asp-net-core-initialization/)
  * [Why you should join .NET Core and ASP.NET Core train](https://codingblast.com/why-you-should-join-asp-net-core/)
* Cloud Development
  * [Configuring the AWS SDK in .NET Core](https://aws.amazon.com/blogs/developer/configuring-aws-sdk-with-net-core/)
  * [Serverless Architecture using C# and AWS Amazon Gateway Api/Lambda](https://www.codeproject.com/Articles/1178781/Serverless-Architecture-using-Csharp-and-AWS-Amazo)
  * [Using C# and .NET Core in Amazon Web Services (AWS) Lambda](https://aws.amazon.com/blogs/compute/announcing-c-sharp-support-for-aws-lambda/)
* Configuration and deployment
  * [.NET project structure](https://gist.github.com/davidfowl/ed7564297c61fe9ab814)
  * [Adding Travis CI builds to a .NET Core app](http://andrewlock.net/adding-travis-ci-to-a-net-core-app/)
  * [ASP.NET Core 1.0 - Configure ApplicationInsights](http://social.technet.microsoft.com/wiki/contents/articles/35918.asp-net-core-1-0-configure-applicationinsights.aspx)
  * [haproxy, nginx, Angular 2, ASP.NET Core, Redis and Docker](http://tattoocoder.azurewebsites.net/legion-of-heroes-haproxy-nginx-angular2-aspnetcore-redis-docker/)
  * [Project.json to MSBuild conversion guide](http://www.natemcmaster.com/blog/2017/01/19/project-json-to-csproj/)
  * [Publishing a .NET project with Appveyor and NuGet](https://few-lines-of-code.blogspot.com/2016/03/publishing-net-project-with-appveyor.html)
  * [The New Configuration Model in ASP.NET Core](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/)
* Entity Framework Core
  * [A very good example about EF Core](https://github.com/rowanmiller/Demo-EFCore) ⭐ 114 | 🐛 0 | 🌐 C# | 📅 2017-05-12
  * [.NET Core Data Access](https://blogs.msdn.microsoft.com/dotnet/2016/11/09/net-core-data-access/)
  * [Connect to Postgres with EF Core](http://en.otomatikmuhendis.com/2017/05/05/connect-to-postgres-with-ef-core/)
* Miraculous
  * [Getting started with Orchard Core as a NuGet package](http://www.ideliverable.com/blog/getting-started-with-orchard-core-as-a-nuget-package)
  * [How to export HTML to PDF in ASP.NET Core](https://code.msdn.microsoft.com/How-to-export-HTML-to-PDF-c5afd0ce)
  * [Vue.js server side rendering with ASP.NET Core](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
* Security
  * [A walk-through for an ASP.NET Authorization Lab](https://github.com/blowdart/AspNetAuthorizationWorkshop) ⚠️ Archived
  * [.NET Continuous Delivery Microservices](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [ASP.NET Core 2.0 Authentication and Authorization System Demystified](https://digitalmccullough.com/posts/aspnetcore-auth-system-demystified.html)
  * [Authentication in ASP.NET Core](https://stormpath.com/blog/authentication-asp-net-core)
* Testing
  * [Selenium with .NET Core](http://www.dotnetcatch.com/2016/11/23/selenium-with-net-core/)

- [InfoQ .NET articles](https://www.infoq.com/dotnet) -  Collection of best .NET articles on InfoQ site

## Books

* [.NET Core in Action](https://manning.com/books/dotnet-core-in-action)
* [ASP.NET Core Application Development: Building an application in four sprints (Developer Reference)](https://www.amazon.com/ASP-NET-Core-Application-Development-application/dp/1509304061)
* [ASP.NET Core in Action](https://www.manning.com/books/asp-net-core-in-action)
* [ASP.NET Core 1.0 High Performance](https://www.amazon.com/ASP-NET-Core-1-0-High-Performance/dp/1785881892)
* [Building Microservices with ASP.NET Core: Develop, Test, and Deploy Cross-Platform Services in the Cloud](https://www.amazon.com/Building-Microservices-ASP-NET-Core-Cross-Platform/dp/1491961732)
* [C# 6 and .NET Core 1.0: Modern Cross-Platform Development](https://www.amazon.com/NET-Core-1-0-Cross-Platform-Development/dp/1785285696)
* [C# in Depth 4](https://www.amazon.com/C-Depth-Jon-Skeet/dp/1617294535)
* [Dependency Injection in .NET Core, 2nd edition](https://www.manning.com/books/dependency-injection-in-dot-net-second-edition)
* [Essencial C# 7.0](https://www.amazon.com/Essential-7-0-Addison-Wesley-Microsoft-Technology/dp/1509303588)
* [Exploring .NET Core with Microservices, ASP.NET Core, and Entity Framework Core - free eBook sampler](https://www.manning.com/books/exploring-dot-net-core)
* [Microservices in .NET Core: with C#, the Nancy framework, and OWIN middleware](https://www.amazon.com/Microservices-NET-Core-framework-middleware/dp/1617293377)
* [Professional C# 6 and .NET Core 1.0](https://www.amazon.com/Professional-NET-Core-Christian-Nagel/dp/111909660X)
* [The little ASP.NET Core](https://www.recaffeinate.co/book)

## Videos

* [Channel9](https://channel9.msdn.com) - MSDN
* [Channel9](https://www.youtube.com/channel/UCsMica-v34Irf9KVTh6xx-g) - YouTube
* [Microsoft Learning Center](https://dotnet.microsoft.com/learn/aspnet)
* [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)

## Podcasts

* [.NET Rocks](https://www.dotnetrocks.com)
* [Merge Conflict](http://www.mergeconflict.fm/)
* [The sound of .NET](http://thesoundof.net/?q=.NET+Core)

## Community

* [.NET Foundation](http://forums.dotnetfoundation.org)
* [.NET Blog](https://devblogs.microsoft.com/dotnet/)
* [/r/CoolGithubProjects](https://www.reddit.com/r/coolgithubprojects)
* [ASP.NET](https://forums.asp.net)
* [Channel9](https://channel9.msdn.com)
* [Awesome .NET open source & community resources](https://discoverdot.net)
* [Slack](http://tattoocoder.com/aspnet-slack-sign-up)
* [BuiltWithDot.Net](https://builtwithdot.net)
* [awesome-copilot](https://github.com/github/awesome-copilot) ⭐ 38,001 | 🐛 68 | 🌐 Python | 📅 2026-08-19
* Stack Overflow
  * [.NET Core](https://stackoverflow.com/questions/tagged/.net-core)
  * [CoreCLR](https://stackoverflow.com/questions/tagged/coreclr)
  * [ASP.NET Core](https://stackoverflow.com/questions/tagged/asp.net-core)
  * [ASP.NET Core MVC](https://stackoverflow.com/questions/tagged/asp.net-core-mvc)
  * [ASP.NET Core 1.0](https://stackoverflow.com/questions/tagged/asp.net-core-1.0)
  * [Entity Framework Core](https://stackoverflow.com/questions/tagged/entity-framework-core)
* [Trending .NET repositories on GitHub today](https://github.com/trending?l=csharp)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [thangchung](http://weblogs.asp.net/thangchung) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
