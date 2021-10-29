# Remotely

## Tonton Jo - 2021
Join me on Youtube: https://www.youtube.com/c/tontonjo

If you find this usefull, please think about
<a href="https://www.buymeacoffee.com/tontonjo"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png"></a>
and to [Subscribe to my youtube channel](http://youtube.com/channel/UCnED3K6K5FDUp-x_8rwpsZw?sub_confirmation=1)

## Sources: 
[Github Remotely](https://github.com/lucent-sea/Remotely)  
[Docker Hub Remotely](https://hub.docker.com/r/translucency/remotely)  

## Docker command:  
```shell
docker run -d \
--name remotely \
--restart unless-stopped \
-p 5000:5000 \
-v /path/to/data/:/remotely-data \
translucency/remotely:latest
```
