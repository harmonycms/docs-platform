# Project

## Overview

With the feature _Project_, we provide to every single end user a simple way to reflects which application they are trying to build. It used to bind add-ons to take advantage of automatic updates, along with easy installation and team collaboration.

_Project_ works by connecting the end user to is account. It consist of a secure two-way communication between Harmony Platform and the installed application, giving to the end user an all-in-one interface to view and manage is own installed application directly from the Harmony Platform website.

### Simplified app management

With a all-in-one interface for the _Project_ feature, we provide to the end user a simplified way to manage \(deploy, update, translate, ...\) each created project in an unique location in the Harmony Platform website.

This feature has been developed to simplify the way to install a project to your server by providing an unique ProjectID used by our [HarmonyFlex](https://docs.harmonycms.net/components/harmonyflex) tool to communicate between your application and the Harmony Platform using our OAuth2 API.

### Binded add-ons

When you've created at least one project in your account, you will be able to bind all add-ons \(extensions, packages, themes, translations\) available in the marketplace. The binded feature is very smart and will check the compatibility between the add-on you're trying to bind and the ones already binded in your project. It will also show you all dependencies who need to be installed for each add-on.

By binding this add-ons to your project, your are building your application. When you finish, you are ready to deploy/update your application to your server by using our [HarmonyFlex](https://docs.harmonycms.net/components/harmonyflex) tool.

### Settings manager

With _Project_, you also can store settings into a manager. The settings manager can store information such as the database connection parameters.  
By specifying this kind of settings, _Project_ will use a predefined [Stack](stack.md) and will tell to [HarmonyFlex](https://docs.harmonycms.net/components/harmonyflex) to install some dependencies needed to be able to connect to your database server. In this case, [HarmonyFlex](https://docs.harmonycms.net/components/harmonyflex) will also configure your `.env` file with the database connection parameters.

### Always up-to-date

The feature _Project_ constantly know which version of which add-ons are installed by communicating between Harmony Platform and your application by using our secured API.

By doing that we can inform you when a new version of an add-on, compatible with your application and dependencies is available on our Marketplace. You will be able to update this add-on manually using [Composer](https://getcomposer.org) or directly from the _Project_ interface.

## Read more

{% page-ref page="recipe.md" %}

{% page-ref page="stack.md" %}

