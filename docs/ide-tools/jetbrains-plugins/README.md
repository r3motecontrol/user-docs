---
description: Use this documentation to get started with the JetBrains plugin.
---

# JetBrains plugins

Snyk offers IDE integrations that allow you to use the functionality of Snyk in your Integrated Development Environment. This page describes the Snyk JetBrains plugins. For information about all of the IDE plugins and their use, see [Snyk for IDEs](https://docs.snyk.io/ide-tools) in the docs.

Snyk supports JetBrains plugins from version 2020.2 for [IntelliJ IDEA](https://snyk.io/lp/intellij-ide-plugin/) and [WebStorm](https://snyk.io/lp/webstorm-ide-plugin/) as well as Android Studio, AppCode, GoLand, PhpStorm, PyCharm, Rider, and RubyMine.

The Snyk JetBrains plugins provide analysis of your code, containers, and Infrastructure as Code configurations. The plugin is based on Snyk CLI, but not on the CLI only. The plugin supports product features in the CLI for Snyk Open Source and Snyk Container as well as for Snyk Code and Snyk IaC with some limitations.

Snyk scans for vulnerabilities and misconfigurations and returns results with security issues categorized by issue type and severity.

For open source, you receive automated algorithm-based fix suggestions for both direct and transitive dependencies. For containers, you can automate upgrades to the most secure base image to quickly resolve numerous vulnerabilities. This single plugin provides a Java vulnerability scanner, a custom code vulnerability scanner, an open-source security scanner, and an application security plugin.

Snyk scans for the following types of issues:

****[**Open Source Security**](https://snyk.io/product/open-source-security-management/) - security vulnerabilities and license issues in both direct and in-direct (transitive) open-source dependencies pulled into the Snyk Project. See also the [Open Source docs](https://docs.snyk.io/products/snyk-open-source).

****[**Code Security**](https://snyk.io/product/snyk-code/) and [**Code Quality**](https://snyk.io/product/snyk-code/) - security vulnerabilities and quality issues in your code. See also the [Snyk Code docs](https://docs.snyk.io/products/snyk-code).

****[**Container Security**](https://snyk.io/product/container-vulnerability-management/) - security vulnerabilities in your base images. See also the [Snyk Container docs](https://docs.snyk.io/products/snyk-container).

****[**Infrastructure as Code (IaC) Security**](https://snyk.io/product/infrastructure-as-code-security/) - configuration issues in your IaC templates: Terraform, Kubernetes, CloudFormation, and Azure Resource Manager. See also the [Snyk Infrastructure as Code docs](https://docs.snyk.io/products/snyk-infrastructure-as-code).

The JetBrains plugins also provide the [**Open Source Advisor**](https://snyk.io/advisor/) to help you find the best package for your next project. Information is provided on the package health of the direct dependencies you are using including popularity, maintenance, risk, and community insights.

After you complete the installation steps on this page and the [configuration](https://docs.snyk.io/ide-tools/jetbrains-plugins/configuration-environment-variables-and-proxy-for-the-jetbrains-plugins) and [authentication](https://docs.snyk.io/ide-tools/jetbrains-plugins/authentication-for-the-jetbrains-plugins) steps on the next two pages**,** you will continue by following the instructions in the other JetBrains plugins docs:

* [Run an analysis with the JetBrains plugins](https://docs.snyk.io/ide-tools/jetbrains-plugins/run-an-analysis-with-the-jetbrains-plugins)
* [JetBrains analysis results: Open Source](https://docs.snyk.io/ide-tools/jetbrains-plugins/jetbrains-analysis-results-snyk-open-source)
* [JetBrains analysis results: Snyk Code](https://docs.snyk.io/ide-tools/jetbrains-plugins/jetbrains-analysis-results-snyk-code)
* [JetBrains analysis results: Snyk IaC Configuration](https://docs.snyk.io/ide-tools/jetbrains-plugins/jetbrains-analysis-results-snyk-iac-configuration)
* [JetBrains analysis results: Snyk Container](https://docs.snyk.io/ide-tools/jetbrains-plugins/jetbrains-analysis-results-snyk-container)
* [How Snyk Container and Kubernetes JetBrains integration works](https://docs.snyk.io/ide-tools/jetbrains-plugins/how-snyk-container-and-kubernetes-jetbrains-integration-works)
* [Filter JetBrains results](https://docs.snyk.io/ide-tools/jetbrains-plugins/filter-jetbrains-results)
* [Troubleshooting for the JetBrains plugin](https://docs.snyk.io/ide-tools/jetbrains-plugins/troubleshooting-for-the-jetbrains-plugin)

## **Install the JetBrains plugin**

The Snyk JetBrains plugin is available for installation on the [JetBrains marketplace](https://plugins.jetbrains.com/plugin/10972-snyk-vulnerability-scanner).

Install using the IDE plugins library:

1. Open the **Preferences** window in the IDE.
2. Navigate to the **Plugins** tab.
3. In the **Plugins** tab, search for **Snyk**.
4. Select the **Snyk vulnerability scanning** plugin.
5. Click on the **Install** button.
6. When the installation is complete, restart the IDE.

![Select the Snyk vulnerability scanning plugin](<../../.gitbook/assets/Screen Shot 2022-03-09 at 5.06.13 PM (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)

Continue with the steps on the JetBrains [configuration](https://docs.snyk.io/ide-tools/jetbrains-plugins/configuration-environment-variables-and-proxy-for-the-jetbrains-plugins) page.

## Support and feedback

If you need help, submit a [request](https://support.snyk.io/hc/en-us/requests/new) to Snyk Support.

Snyk continuously strives to improve the plugins experience. If you would you like to share your feedback about the Snyk Eclipse plugin [schedule a meeting](https://calendly.com/snyk-georgi/45min?month=2022-01).