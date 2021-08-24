# frp

[![frp](http://dockeri.co/image/snowdreamtech/frps)](https://hub.docker.com/r/snowdreamtech/frps)
[![frp](http://dockeri.co/image/snowdreamtech/frpc)](https://hub.docker.com/r/snowdreamtech/frpc)

Docker Image packaging for Frp.

(amd64, arm32v6, arm32v7, arm64v8, i386)

### [中文文档](https://www.itcoder.tech/posts/docker-frp/)

## Usage

start frps

```bash
docker run --restart=always --network host -d -v /etc/frp/frps.ini:/etc/frp/frps.ini --name frps snowdreamtech/frps
```

start frpc

```bash
docker run --restart=always --network host -d -v /etc/frp/frpc.ini:/etc/frp/frpc.ini --name frpc snowdreamtech/frpc
```

## Quick reference

* Where to file issues:

[https://github.com/snowdreamtech/frp/issues](https://github.com/snowdreamtech/frp/issues)

* Maintained by:

snowdream <sn0wdr1am@icloud.com>

* Supported architectures: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))

frpc:

[amd64](https://cloud.docker.com/u/snowdreamtechamd64/repository/docker/snowdreamtechamd64/frpc), [arm32v6](https://cloud.docker.com/u/snowdreamtecharm32v6/repository/docker/snowdreamtecharm32v6/frpc), [arm32v7](https://cloud.docker.com/u/snowdreamtecharm32v7/repository/docker/snowdreamtecharm32v7/frpc), [arm64v8](https://cloud.docker.com/u/snowdreamtecharm64v8/repository/docker/snowdreamtecharm64v8/frpc), [i386](https://cloud.docker.com/u/snowdreamtechi386/repository/docker/snowdreamtechi386/frpc)

frps:

[amd64](https://cloud.docker.com/u/snowdreamtechamd64/repository/docker/snowdreamtechamd64/frps), [arm32v6](https://cloud.docker.com/u/snowdreamtecharm32v6/repository/docker/snowdreamtecharm32v6/frps), [arm32v7](https://cloud.docker.com/u/snowdreamtecharm32v7/repository/docker/snowdreamtecharm32v7/frps), [arm64v8](https://cloud.docker.com/u/snowdreamtecharm64v8/repository/docker/snowdreamtecharm64v8/frps), [i386](https://cloud.docker.com/u/snowdreamtechi386/repository/docker/snowdreamtechi386/frps)

* Supported Tags:

[Frps](https://cloud.docker.com/u/snowdreamtech/repository/docker/snowdreamtech/frps/tags)

[Frpc](https://cloud.docker.com/u/snowdreamtech/repository/docker/snowdreamtech/frpc/tags)

## Sponsors

[![tencent cloud](https://upload-dianshi-1255598498.file.myqcloud.com/345-200-788d0ee3eed06e913b85ddb6b178f8b9960c4684.jpg](https://cloud.tencent.com/act/cps/redirect?redirect=1077&cps_key=d09c5e921f9fcf4ac9516564262f3b99&from=console)

[![aliyun](https://snowdreamtech.oss-cn-beijing.aliyuncs.com/aliyun/%E6%96%B0%E4%BA%BA-%E4%B8%BB/440-240%201.jpg)](https://www.aliyun.com/1111/new?userCode=dbgo15cy)

## Contact (备注：frp)

* Email: sn0wdr1am@icloud.com
* QQ: 3217680847
* QQ群: 82695646
* WeChat: sn0wdr1am86
* 微信群: 
![微信群](https://snowdreamtech.oss-cn-beijing.aliyuncs.com/snowdream/snowdreamtechwechatqun.png)]

## Website

1. [fatedier/frp](https://github.com/fatedier/frp)
1. [Snowdream Tech](http://www.snowdream.tech/)
1. [ITCoder](https://www.itcoder.tech/)

## License

Apache 2.0
