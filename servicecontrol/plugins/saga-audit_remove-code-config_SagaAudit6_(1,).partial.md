When the plugin is configured via code the endpoint has a direct reference to it. Removing the dll from the bin directory will prevent the endpoint from starting unless the configuration code is also removed. Rather create a configurable option in the config with which the plugin can be enabled or disabled. Configure this option during deployment to disable it in production.

snippet: SagaAudit_Configurable