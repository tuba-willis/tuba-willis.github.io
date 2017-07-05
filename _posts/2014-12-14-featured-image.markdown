---
layout: post
title:  "How to build an API Endpoint for results query and access"
date:   2017-07-07
---

<p class="intro"><span class="dropcap">
I</span>n this blog i describe the pocess i would undertake to design an API Endpoint for UTAMU students results query and access</p>
<h3>API design</h3>
A well-designed web API should aim to support:
<ol>
<li>Platform independence</li> Client applications should be able to utilize the API that the web service provides without requiring how the data or operations that API exposes are physically implemented. This requires that the API abides by common standards that enable a client application and web service to agree on which data formats to use, and the structure of the data that is exchanged between client applications and the web service.
<li>Service evolution</li> The web service should be able to evolve and add (or remove) functionality independently from client applications. Existing client applications should be able to continue to operate unmodified as the features provided by the web service change. All functionality should also be discoverable, so that client applications can fully utilize it.
</ol>
<h4>Decide the Style of the API</h4>
While designing an API, one of the first things to consider is creating a style guide. This serve as a set of rules and best practices for creating controllers, defining routes, and other aspects of the API. It also provide answers to the big questions such as serialization of entities, mapping Data Transfer Objects (DTOs) if needed, repositories, domain services, database/entity validation, DTO validation, and any third party technologies used, it's maintained regularly and referred back to when needed.

<h4>Defining operations in terms of HTTP methods</h4>
The HTTP protocol defines a number of methods that assign semantic meaning to a request. The common HTTP methods used by most RESTful web APIs are:
<ul>
<li>GET</li>To retrieve a copy of the resource at the specified URI. The body of the response message contains the details of the requested resource.
<li>POST</li>To create a new resource at the specified URI. The body of the request message provides the details of the new resource. Note that POST can also be used to trigger operations that don't actually create resources.
<li>PUT</li>To replace or update the resource at the specified URI. The body of the request message specifies the resource to be modified and the values to be applied.
<li>DELETE</li>To remove the resource at the specified URI.
</ul>
<h4>Characteristics of a well-designed API</h4>
In my design i would be considerate of the following characteristics of a well-designed API:
<ul>
<li>Easy to read and work with:</li> A well designed API will be easy to work with, and its resources and associated operations can easily understood by end consumers.
<li>Hard to misuse:</li> Implementing and integrating with an API with good design will be a straightforward process, and writing incorrect code will be a less likely outcome.
<li>Complete and concise:</li> A complete API will make it possible for developers to make full-fledged applications against the data you expose.
</ul>
