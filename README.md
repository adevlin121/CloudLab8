-s
makes curl mute

-X GET
sets default request type to be get

-H 'Accept: application/json'
sets the words within the quotation marks as the header 

use curl to do "/"

GET /containers                     List all containers
GET /containers?state=running      List running containers (only)
GET /containers/<id>                Inspect a specific container
GET /containers/<id>/logs           Dump specific container logs
POST /containers                    Create a new container
PATCH /containers/<id>              Change a container's state
DELETE /containers/<id>             Delete a specific container
DELETE /containers                  Delete all containers (including running)
GET /images                         List all images
POST /images                        Create a new image
PATCH /images/<id>                  Change a specific image's attributes
DELETE /images/<id>                 Delete a specific image
DELETE /images                      Delete all images