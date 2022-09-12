# deploy odoo
- odoo is accessible on port 80
- odoo and db containers are in odoo_network of type bridge
- To see if the containers are running:`docker-compose ps` 
- To start your Odoo instance, go in the directory of the `docker-compose.yml` and run : `console
docker-compose up -d`
