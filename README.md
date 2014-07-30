<!--
#
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
# 
# http://www.apache.org/licenses/LICENSE-2.0
# 
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#  KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.
#
-->


CordovaDeploy cli
===

extracted from the **Apache Cordova for Windows Phone 8**

[Original Repository](https://git-wip-us.apache.org/repos/asf?p=cordova-wp8.git)

So, it works only on windows

### Install

```
npm install cordova-deploy-windows-phone
```

### Usage

```
$cordovadeploy

Usage: CordovaDeploy [ -devices  BuildOutputPath -d:DeviceIndex -uninstall ]
    -devices : lists the devices and exits
    BuildOutputPath : path to the built application, typically Bin/Debug/ or Bin/Release/
    -d         : index of the device to deploy, default is 0
    -uninstall : will uninstall the application before re-installing it, removing all app documents a
nd temp files
examples:
  CordovaDeploy -devices
  CordovaDeploy Bin/Debug
  CordovaDeploy Bin/Release -d:1
```
