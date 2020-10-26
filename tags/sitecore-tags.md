# Official Sitecore images on tsigningacr202010261516.azurecr.io
This document provides a list of the images and tags available on the official Sitecore container registry hosted at scr.sitecore.com. 
The Sitecore container images are structured in namespaces according to product line:  
- **[sxp](#sxp):** Contains all *Sitecore Experience Platform (SXP)* image repositories. Primary platform repositories are found at the root.  
- **[sxp/nonproduction](#sxp/nonproduction):** Images for SXP supporting roles intended for development and testing. No production support is provided for images labeled as nonproduction. 
- **[sxc](#sxc):** Contains all *Sitecore Experience Commerce (SXC)* image repositories. Primary SXC repositories are found at the root.  
- **[sxc/nonproduction](#sxc/nonproduction):** Images for SXC supporting roles intended for development and testing. No production support is provided for images labeled as nonproduction..  
- **[sxp/modules](#sxp/modules):** Contains image repositories for SXP-specific modules.  
- **[tools](#tools):** Tools to support Sitecore products 
## demo 
Images in this namespace are built from the Sitecore.Demo.DevOps and Sitecore.Demo.Platform GitHub repositories are meant to support non-production training, experimentation, and demonstration scenarios. Support for these images is community-driven and not provided by Sitecore Support. 
### lighthouse-id
Tag                    | Architecture    | OS      | Digest                                                                  | CreatedTime          | LastUpdateTime      |
---------------------- | --------------- | ------- | ----------------------------------------------------------------------- | -------------------- | --------------------|
10.0.0-ltsc2019        | amd64           | windows | sha256:aabb96b90c8d0c677d1c30887d59a2ceddfd8304fbf75d2b7ab5553bd803895d | 10/26/2020 15:34:45  | 10/26/2020 15:34:45 |
10.0.0-ltsc2019-1000.0 | amd64           | windows | sha256:aabb96b90c8d0c677d1c30887d59a2ceddfd8304fbf75d2b7ab5553bd803895d | 10/26/2020 15:34:26  | 10/26/2020 15:34:26 |
### lighthouse-init
Tag                    | Architecture    | OS      | Digest                                                                  | CreatedTime          | LastUpdateTime      |
---------------------- | --------------- | ------- | ----------------------------------------------------------------------- | -------------------- | --------------------|
10.0.0-ltsc2019        | amd64           | windows | sha256:869b294d08631c0c6a40ef54fa89d0649c1865875af46f2f31f83814435cc8c6 | 10/26/2020 15:35:47  | 10/26/2020 15:35:47 |
10.0.0-ltsc2019-1000.0 | amd64           | windows | sha256:869b294d08631c0c6a40ef54fa89d0649c1865875af46f2f31f83814435cc8c6 | 10/26/2020 15:35:31  | 10/26/2020 15:35:31 |
### lighthouse-mssql
Tag                    | Architecture    | OS      | Digest                                                                  | CreatedTime          | LastUpdateTime      |
---------------------- | --------------- | ------- | ----------------------------------------------------------------------- | -------------------- | --------------------|
10.0.0-ltsc2019        | amd64           | windows | sha256:aff6d165b813c71c3578e025617492fcfe9ee28322074f4462dc9fd65a6592be | 10/26/2020 15:44:50  | 10/26/2020 15:44:50 |
10.0.0-ltsc2019-1000.0 | amd64           | windows | sha256:aff6d165b813c71c3578e025617492fcfe9ee28322074f4462dc9fd65a6592be | 10/26/2020 15:44:31  | 10/26/2020 15:44:31 |
### lighthouse-ps
Tag                    | Architecture    | OS      | Digest                                                                  | CreatedTime          | LastUpdateTime      |
---------------------- | --------------- | ------- | ----------------------------------------------------------------------- | -------------------- | --------------------|
10.0.0-ltsc2019        | amd64           | windows | sha256:73acfaf348ebfd6fd38f0a460584f3349f4dd35730827c52f82ce9c96933c3b4 | 10/26/2020 15:45:32  | 10/26/2020 15:45:32 |
10.0.0-ltsc2019-1000.0 | amd64           | windows | sha256:73acfaf348ebfd6fd38f0a460584f3349f4dd35730827c52f82ce9c96933c3b4 | 10/26/2020 15:45:17  | 10/26/2020 15:45:17 |
### lighthouse-solr
Tag                    | Architecture    | OS      | Digest                                                                  | CreatedTime          | LastUpdateTime      |
---------------------- | --------------- | ------- | ----------------------------------------------------------------------- | -------------------- | --------------------|
10.0.0-ltsc2019        | amd64           | windows | sha256:df963385cf2fb0b40214f10a9afa42cf3375385f4841ff4250f1312d2591b645 | 10/26/2020 15:46:41  | 10/26/2020 15:46:41 |
10.0.0-ltsc2019-1000.0 | amd64           | windows | sha256:df963385cf2fb0b40214f10a9afa42cf3375385f4841ff4250f1312d2591b645 | 10/26/2020 15:46:25  | 10/26/2020 15:46:25 |
### lighthouse-xp0-cd
Tag                    | Architecture    | OS      | Digest                                                                  | CreatedTime          | LastUpdateTime      |
---------------------- | --------------- | ------- | ----------------------------------------------------------------------- | -------------------- | --------------------|
10.0.0-ltsc2019        | amd64           | windows | sha256:59dd316e6f4c23db3f30e6515cfe8a08646c630cca73824575891af3228b46da | 10/26/2020 15:51:30  | 10/26/2020 15:51:30 |
10.0.0-ltsc2019-1000.0 | amd64           | windows | sha256:59dd316e6f4c23db3f30e6515cfe8a08646c630cca73824575891af3228b46da | 10/26/2020 15:51:14  | 10/26/2020 15:51:14 |
### lighthouse-xp0-cm
Tag                    | Architecture    | OS      | Digest                                                                  | CreatedTime          | LastUpdateTime      |
---------------------- | --------------- | ------- | ----------------------------------------------------------------------- | -------------------- | --------------------|
10.0.0-ltsc2019        | amd64           | windows | sha256:25e1b69474af0e438e54136b7106a64245bdbe334e0c2f20852fe92f12f7fe6f | 10/26/2020 15:54:05  | 10/26/2020 15:54:05 |
10.0.0-ltsc2019-1000.0 | amd64           | windows | sha256:25e1b69474af0e438e54136b7106a64245bdbe334e0c2f20852fe92f12f7fe6f | 10/26/2020 15:53:49  | 10/26/2020 15:53:49 |
### lighthouse-xp0-xconnect
Tag                    | Architecture    | OS      | Digest                                                                  | CreatedTime          | LastUpdateTime      |
---------------------- | --------------- | ------- | ----------------------------------------------------------------------- | -------------------- | --------------------|
10.0.0-ltsc2019        | amd64           | windows | sha256:1aec6a756ad4a3d3122ca27517a48ea620b9acb02575c6bc5b4b001f6be5e25b | 10/26/2020 15:58:08  | 10/26/2020 15:58:08 |
10.0.0-ltsc2019-1000.0 | amd64           | windows | sha256:1aec6a756ad4a3d3122ca27517a48ea620b9acb02575c6bc5b4b001f6be5e25b | 10/26/2020 15:57:52  | 10/26/2020 15:57:52 |
### lighthouse-xp0-xdbsearchworker
Tag                    | Architecture    | OS      | Digest                                                                  | CreatedTime          | LastUpdateTime      |
---------------------- | --------------- | ------- | ----------------------------------------------------------------------- | -------------------- | --------------------|
10.0.0-ltsc2019        | amd64           | windows | sha256:b0493b8020d052fa6537e10a9790a47da4c8017083df3d0cc2e0cbdf7e055cb0 | 10/26/2020 15:59:54  | 10/26/2020 15:59:54 |
10.0.0-ltsc2019-1000.0 | amd64           | windows | sha256:b0493b8020d052fa6537e10a9790a47da4c8017083df3d0cc2e0cbdf7e055cb0 | 10/26/2020 15:59:40  | 10/26/2020 15:59:40 |
 
*This listing was automatically generated on October 26, 2020.*
