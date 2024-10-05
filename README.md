# media-gallery
Easy-to-implement media gallery server with a client sdk and optional admin panel

File uploads were never easy. Projects like https://github.com/pingdotgg/uploadthing attempt to simplify the complexity of file uploads in form of a SAAS app (that might not be for everyone). However, solutions like these only provide a more general approach to file uploading. When creating cms-like admin panels for a variety of projects I came across the need for a cms-like media-gallery like e.g. Wordpress has. Implementing these, although not difficult, was annoying at best as you are not shipping any features and are only improving the admin experience. 

## General idea
media-gallery is a self-hosted file management solution. The client app (if not using the middleware solution) interacts directly with the media-gallery except for grabbing the initial token. media-gallery supports a variety of storage soltions (currenly only s3(amazon, minio etc.) and local path) and databases (sqlite, postgres, mariadb, mongodb). 

![grafik](https://github.com/user-attachments/assets/bfe07ea8-838c-4dd8-a785-fd8bed1aea7d)
![grafik](https://github.com/user-attachments/assets/f5ba232f-020d-4c89-9141-293aef45d661)
