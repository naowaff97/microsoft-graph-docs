---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

Boolean securityEnabledOnly = true;

graphClient.contacts("{id}")
	.getMemberObjects(securityEnabledOnly)
	.buildRequest()
	.post();

```