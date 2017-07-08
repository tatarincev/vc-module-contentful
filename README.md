# VirtoCommerce.Contentful (Preview!)
VirtoCommerce.Contentful module provides integration with https://contentful.com CMS service.
Key features:
* develop and publish CMS pages in Contentful and automatically publish to Virto Commerce CMS
* un-publish existing pages

# Documentation
Coming soon

# Installation
Installing the module:
* Automatically: in VC Manager go to Configuration -> Modules -> Contentful module -> Install
* Manually: download module zip package from https://github.com/VirtoCommerce/vc-module-contentful/releases. In VC Manager go to Configuration -> Modules -> Advanced -> upload module package -> Install.

# Settings
* In Contentful configure webhook to point to http://{URL}/admin/api/contentful/{STOREID}?api_key={VIRTO_API_KEY}, it should only apply for create, update and delete events.
* In Contentful create "page" entity with "Title", "Content" and "Permalink" properties (you can add additional properties like layout etc).

![image](https://user-images.githubusercontent.com/1566470/27984254-f057f266-6385-11e7-9a1a-fec1bfe67439.png)

# License
Copyright (c) Virtosoftware Ltd.  All rights reserved.

Licensed under the Virto Commerce Open Software License (the "License"); you
may not use this file except in compliance with the License. You may
obtain a copy of the License at

http://virtocommerce.com/opensourcelicense

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
implied. 
