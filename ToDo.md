# Todo list, and state of development. 
have been following this guide:
https://www.youtube.com/watch?v=liV3c9m_OX8
and reviewing this example:
https://github.com/techno-tim/techno-tim.github.io/tree/master/reference_files/traefik-portainer-ssl/traefik

[x] Get traefik routing to work
[x] Verify that cert is recived from letsencrypt staging before setting to production.
[ ] clean up the comments and such. especially the enviroment variables used in nextcloud.yaml
[ ] Modify or find new container to update ROOT_DOMAIN to point to traefik. (cf domain is set so *.ROOT_DOMAIN goes to ROOT_DOMAIN)