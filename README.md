# Chef Intermediate

* Building Custom Resources
* Writing Ohai Plugins
* Chef-Client Internals
* Implementing Chef Handlers
* Cookbook Style and Correctness
* Foodcritic
* Rubocop
* Introduction to ChefSpec

## Node Setup

This node is currently being managed as a Amazon Machine Instance (AMI). This AMI is managed by Chef through the Training AWS Account.

* CentOS 6.7 chef-essentials-4.0.0 (ami-11410d74)

> The the AMI was generated with [Packer](https://github.com/chef-training/chefdk-fundamentals-image) and adheres to the following [policy](https://github.com/chef-training/chefdk-fundamentals-image/blob/master/cookbooks/fundamentals/recipes/centos.rb). It is based on a Marketplace AMI so it cannot be made public. If you would like access to this AMI to deliver training please contact [training@chef.io](mailto:training@chef.io) the request that includes your Amazon Account Id.



## Reviewing & Feedback

There are two basic means of supplying feedback and/or updating the materials:

### Open a GitHub Issue

When you discover a typo, inconsistency, or an error with the content.

* Describe the issue with the content

* Include the version (e.g. v2.1.5) or commit SHA (e.g. 89f3ad132bf575a85973935d3e88ae66c10fcd67)

* Include a picture of the slide or handout page (Issues allow you to drag-and-drop images) and information that identifies the slide or page (e.g. slide/page title, slide/page number)

### Submit a Pull Request

When you have fixed a typo, inconsistency, or error with the content.

* Describe the issue that this pull request addresses. Sections and slides changed.

* Include the version (e.g. v2.1.5) or commit SHA (e.g. 89f3ad132bf575a85973935d3e88ae66c10fcd67) this change is based on.
