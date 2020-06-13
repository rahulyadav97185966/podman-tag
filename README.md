# podman-tag

1) follow the below command to tag and push the podman image to docker hub (registry).

       #podman pull docker.io/httpd : we are using the httpd file for this scenario.
       #podman images : now chech whether the image is get pulled or not
       #podman tag ccbcea8a6757 docker.io/yadavsagar/httpd-image:test1 :using this we can tag the image (syntax is podman tag <image_name_or_id> <docker.io_username_reponame:tagname)

       #podman images : now you can see the tag is applied to image 
       #podman login docker.io : login to your docker hub or any registry
       #podman push docker.io/yadavsagar/httpd-image:test1 :now push the image using this command
