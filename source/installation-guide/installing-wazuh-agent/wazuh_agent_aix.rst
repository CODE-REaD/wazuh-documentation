.. Copyright (C) 2019 Wazuh, Inc.

.. _wazuh_agent_aix:

Install Wazuh agent on AIX
==============================

The Wazuh agent for AIX can be downloaded from our :doc:`packages list<../packages-list/index>`. You can choose installation or a deployment:

  a) Installation:

    .. code-block:: console

      # rpm -ivh wazuh-agent-3.9.0-1.aix.ppc.rpm

    .. note:: With only installation, the next step is to register and configure it to communicate with the manager. For more information about this process, please visit the :doc:`user manual<../../user-manual/registering/index>`.

  b) Deployment:

    You can automate the agent registration and configuration using variables. 

    .. code-block:: console

      # WAZUH_MANAGER_IP="10.0.0.2" rpm -ivh wazuh-agent-3.9.0-1.aix.ppc.rpm  

    .. note:: See the following document for additional deployment options: :doc:`configuration provisioning variables <configuration_provisioning_variables>`.   

