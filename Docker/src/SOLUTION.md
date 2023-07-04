## Part 1. Ready-made docker

- `docker pull nginx`
![img.png](pictures/pull_nginx.png)


- Check `nginx` for exist
![img.png](pictures/check_image_nginx.png)


- Run `nginx`
![img.png](pictures/run_nginx.png)


- Check `nginx` if it`s running
![img.png](pictures/ps_nginx.png)


- Inspect `nginx`
![img.png](pictures/inspect_nginx.png)

- Size: 141838643, port: 80, где ip хз


- Stopping `nginx` and `ps`
![img.png](pictures/stop.png)
![img.png](pictures/ps_nginx stop.png)

- Mapping
![img.png](pictures/mapping.png)

- Start page `nginx`
![img.png](pictures/nginx_start_page.png)


- Restart `nginx`
![img.png](pictures/restart_nginx.png)


- Check restart
![img.png](pictures/check_restart.png)


## Part 2. Operations with container

- Read the `nginx.conf` configuration file inside the docker image with the `exec` command
![img.png](pictures/nginx_conf.png)



- Copied nginx.conf
![img.png](pictures/docker_cp.png)


- Reloaded `nginx` (Чтобы достучаться с локальной машины нужно замаппить порты)
![img.png](pictures/reload_nginx.png)



- Stopped and checked stop
![img.png](pictures/stopping.png)


- Removed image and stopped container
![img.png](pictures/rmi.png)


- Import image and run
![img_1.png](pictures/import.png)



## Part 3. Mini Web-server

- Web-server on C
![img.png](pictures/serv_on_c.png)

- New nginx.conf with fastcgi add-on
![img.png](pictures/nginx_conf_for_server.png)

- Actions inside the container
  ![img.png](pictures/ations_inside_container.png)

- Page in browser with `Hello World`
![img.png](pictures/browser_helloworld.png)

## Part 4. Your own docker
 
- Building docker container 
![img.png](pictures/img.png)
- Running container
![img.png](pictures/img_1.png)


























































