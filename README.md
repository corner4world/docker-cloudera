Docker-Cloudera

By default the Cloudera Manager isn't enabled, but it's not needed.

If you must enable it, run docker ps to get the container name and then execute on the command line

    docker exec -ti {your_cloudera_container_name} /home/cloudera/cloudera-manager --express