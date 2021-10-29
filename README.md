# Remotely

## Tonton Jo - 2021
Join me on Youtube: https://www.youtube.com/c/tontonjo  
If you find this usefull, please consider supporting my work: [Subscribe to my youtube channel](http://youtube.com/channel/UCnED3K6K5FDUp-x_8rwpsZw?sub_confirmation=1)  
<a href="https://www.buymeacoffee.com/tontonjo"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png"></a> <a href="https://www.infomaniak.com/goto/fr/home?utm_term=6151f412daf35"><img src="https://i.ibb.co/KjWSd95/banner-bleu.png"></a> </a> <a href="https://www.xvinlink.com/?a_fid=TontonJo"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/79/ExpressVPN-logo.svg/261px-ExpressVPN-logo.svg.png"></a>  
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
