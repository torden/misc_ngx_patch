
# Just! The patch for dead modules working on nginx lastest version


## nginx_ajp_module-support-nginx-1.24.x-1.25.x.patch

> The last version of nginx_ajp_module cannot work with nginx between 1.24.x and 1.24.x. 
> So Just I made this patch. 
> As you know that project is currently inactive.

```bash
cd nginx-1.x.x/
wget https://raw.githubusercontent.com/torden/misc_ngx_patch/main/patches/nginx_ajp_module-support-nginx-1.24.x-1.25.x.patch
patch -p0 < nginx_ajp_module-support-nginx-1.24.x-1.25.x.patch
```


## ngx_small_light-nginx.1.24.x-1.25.x.patch

> The last version of nginx_small_light cannot work with nginx between 1.24.x and 1.24.x. 
> So Just I made this patch. 
> As you know that project is currently inactive.

```bash
cd nginx-1.x.x/
wget https://raw.githubusercontent.com/torden/misc_ngx_patch/main/patches/ngx_small_light-nginx.1.24.x-1.25.x.patch
patch -p0 < ngx_small_light-nginx.1.24.x-1.25.x.patch
```


## ngx_http_auth_crowd_module-support-nginx-1.24.x-1.25.x.patch

> The last version of ngx_http_auth_crowd_module cannot work with nginx between 1.24.x and 1.24.x. 
> So Just I made this patch. 
> As you know that project is currently inactive.

```bash
cd nginx-1.x.x/
wget https://raw.githubusercontent.com/torden/misc_ngx_patch/main/patches/ngx_http_auth_crowd_module-support-nginx-1.24.x-1.25.x.patch
patch -p0 < ngx_http_auth_crowd_module-support-nginx-1.24.x-1.25.x.patch
```


## nginx_http_image_filter_module-png-transparent_n_resizing-issue-nginx-1.xx.x-1.25.x.c.patch

> This Patch for problems that occur when resizing transparent png images.  
> I tested it on my service for a long time and found no problem. 
> Testing is required in additional environments.

```bash
cd nginx-1.x.x/
wget https://raw.githubusercontent.com/torden/misc_ngx_patch/main/patches/nginx_http_image_filter_module-png-transparent_n_resizing-issue-nginx-1.xx.x-1.25.x.c.patch
patch -p0 < nginx_http_image_filter_module-png-transparent_n_resizing-issue-nginx-1.xx.x-1.25.x.c.patch
```


---

plz feel free
