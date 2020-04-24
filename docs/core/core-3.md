name: core-setup-title
class: title, shelf, no-footer, fullbleed
background-image: linear-gradient(135deg,#279be0,#036eb4)
count: false

# CloudBees Pipeline Template Catalogs

---
name: pipeline-template-catalog

# Pipeline Template Catalogs

Pipeline Template Catalogs help ensure that Pipeline jobs conform to organizational standards.

Benefits of using Pipeline Template Catalogs include:

* Providing developers with a simplified and directed experience for configuring Pipeline in “domain specific” terms that make sense for an organization. Thus, developers can focus on shipping products.
* Organizing Pipelines per projects and/or teams. Similar-looking jobs that only differ in a few aspects can be easily parameterized on a per job basis. When you change a template, all the jobs created from that template get updated automatically.

When combined with Pipeline Shared Libraries, Pipeline Template Catalogs provide an easy way to make your organization's Pipelines reusable — boosting cross-team collaboration, saving time and reducing errors.

???
Pipeline Template Catalogs help ensure that Pipeline jobs conform to organizational standards and when used in combination with Shared Libraries provide reusable Pipelines — boosting cross-team collaborations, saving time and reducing errors.

Pipeline Shared Libraries and Pipeline Template Catalogs can 'live' in the same source code repository.

---
name: pipeline-template-catalog-lab-link

# Lab - Import Pipeline Template Catalog

The Pipeline Template Catalog lab instructions are available at: 
[https://github.com/cloudbees-days/core-rollout-flow-workshop/blob/master/labs/pipeline-template-catalog/pipeline-template-catalog.md](https://github.com/cloudbees-days/core-rollout-flow-workshop/blob/master/labs/pipeline-template-catalog/pipeline-template-catalog.md)

---
name: github-reporting

# CloudBees GitHub Reporting .badge-red[PRE-RELEASE]

Whereas OSS github-branch-source plugin displays only build-level statuses, the CloudBees GitHub Reporting plugin provides more detailed Jenkins Pipeline events as corresponding GitHub statuses.

As the build runs, GitHub will surface status information about the build directly in GitHub, in real-time, alleviating the need to switch over to Jenkins to get an overview.