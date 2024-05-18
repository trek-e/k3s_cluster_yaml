# k3s_cluster_yaml
YAML files for my Turing pi rockfish cluster.

metalib_l2.yaml - the configuration for metalib to enable local ethernet interface
metalib_l2_adv - the l2 advertisement file, no major changes from default other than namespace
radarr_deployjment - The deployment file for the radarr application
radar_service - the service yaml file for the radarr service using metalib to consume local IP
radarr_pvc - the pvc needed for the configuration data