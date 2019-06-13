* [Aliyun CDN document](https://help.aliyun.com/product/27099.html?spm=5176.7933777.598288.ee6.4bd256f5s3wCHU)

* [Aliyun CDN名词解释](https://help.aliyun.com/document_detail/27102.html?spm=5176.208361.1107621.4.5c4557e05kHTMx)

* [CDN加速域名https中级CA证书的配置](https://help.aliyun.com/knowledge_detail/40094.html?spm=a2c4g.11186623.2.13.23043f62IIjPBJ)
* [配置HTTPS证书](https://help.aliyun.com/document_detail/27118.html?spm=a2c4g.11186623.2.19.265a2292cNfOIR#concept-rns-qvk-xdb)
* [如何制作CSR(Certificate Signing Request，简称 CSR)文件？](https://help.aliyun.com/knowledge_detail/42218.html?spm=5176.10695662.1996646101.searchclickresult.353133aaFfrs86)
* [CSR SAN(Subject Alternative Name)](https://geekflare.com/san-ssl-certificate/)

Generate CSR(Subject Alternative Name) with openssl configurations

`openssl.exe req  -nodes -newkey rsa:2048 -keyout myprivate.key -out mydomain.csr -config openssl_san.cnf`

Check generated CSR in with previous command

`openssl.exe req  -nodes -newkey rsa:2048 -keyout myprivate.key -out mydomain.csr -config openssl_san.cnf`

[openssl_san.conf](openssl_san.cnf)

