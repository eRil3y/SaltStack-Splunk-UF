# SaltStack-Splunk-UF
SaltStack configuration for Splunk Universal Forwarder on Windows OS

- Created this config to install Windows Universal Forwarders through SaltStack. Marked where to change or input certain fields to match your Splunk environment. Couldn't find any other openly available configs for SaltStack that were simple and easy. This is just enough to install and configure the Universal Forwarder to connect to Splunk and its Deployment Server. Can push out custom configs through Deployment Server Apps and server classes after install.
- Save config as .sls file and place it under your windows repo directory in SaltStack. Add to top file targeting the windows machines you want to deploy to and reapply the top file.
