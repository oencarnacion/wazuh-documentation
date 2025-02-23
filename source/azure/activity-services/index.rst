.. Copyright (C) 2021 Wazuh, Inc.

.. meta::
  :description: Discover how Wazuh can help you to monitor your Microsoft Azure activity and services in this section of our documentation.

.. _azure_activity_services:

Monitoring activity and services
================================

The Wazuh ``azure-logs`` module for Azure provides capabilities to monitor all the activity and the services of our infrastructure.

From a wider perspective, the Microsoft Azure infrastructure resources can be divided into three types of logs:

- **Activity logs** keep track of the operations performed on a resource from outside of the infrastructure.
- **Resource logs**, previously known as **Diagnostic logs**, provides insight about the operations performed within an Azure resource.
- **Azure Active Directory logs** contains the history of sign-in activity and audit information about the changes made to the Azure AD for a given tenant domain.


.. topic:: Contents

    .. toctree::
       :maxdepth: 2

       prerequisites/index
       services/index
       active-directory/index
