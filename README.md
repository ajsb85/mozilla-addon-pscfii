mozilla-addon-fii
=================

Addon that adds the PSC FII Certificate to the Firefox trusted root certificate store

```text
Certificate:
    Data:
        Version: 3 (0x2)
        Serial Number: 13 (0xd)
        Signature Algorithm: sha256WithRSAEncryption
        Issuer: CN=Autoridad de Certificacion Raiz del Estado Venezolano, C=VE, L=Caracas, ST=Distrito Capital, O=Sistema Nacional de Certificacion Electronica, OU=Superintendencia de Servicios de Certificacion Electronica/emailAddress=acraiz@suscerte.gob.ve
        Validity
            Not Before: Jan 25 16:10:00 2011 GMT
            Not After : Jan 22 23:59:59 2021 GMT
        Subject: C=VE, ST=Miranda, L=Baruta, O=Sistema Nacional de Certificacion Electronica, OU=Fundacion Instituto de Ingenieria, CN=PSC Publico del MppCTII para el Estado Venezolano/emailAddress=admin-pki@fii.gob.ve
        Subject Public Key Info:
            Public Key Algorithm: rsaEncryption
            RSA Public Key: (4096 bit)
                Modulus (4096 bit):
                    00:ab:4e:2f:e9:52:b2:58:33:2e:ac:39:91:3c:a2:
                    25:c6:b8:e2:a3:3c:a0:ed:ee:59:dd:75:cc:99:6c:
                    aa:ce:72:36:50:17:2e:3f:79:07:49:a6:59:d2:a1:
                    2b:f8:0f:53:29:2b:5e:8f:4d:61:23:82:85:f8:70:
                    58:5c:3a:33:15:d9:3e:41:73:cc:bd:d1:0e:f2:40:
                    af:af:6d:b3:1d:68:be:67:b1:6a:2e:69:34:54:d6:
                    a7:8f:79:c1:97:7c:9c:45:7d:df:01:04:a0:2f:68:
                    92:21:da:dc:ea:e9:b3:ea:2f:12:e9:79:eb:a9:ba:
                    cd:74:dc:8c:13:cc:3c:23:92:b2:af:c8:5e:9a:9c:
                    a4:4b:53:cf:6c:b6:25:13:02:b8:cb:e8:0a:04:d6:
                    51:90:62:6e:a2:4d:fd:a9:d6:11:0c:56:5f:16:3c:
                    7b:be:07:cd:c5:e3:91:14:c3:88:fb:a1:c4:aa:bf:
                    28:75:a7:d3:95:ae:fe:e9:19:0d:bc:93:f9:e8:eb:
                    72:0a:b5:1d:0a:1d:d4:94:5e:9d:6a:d6:af:30:0a:
                    9b:d2:e6:21:52:1d:5c:b9:bd:88:7b:15:36:e7:3f:
                    68:b3:b5:18:4d:45:62:87:02:ac:21:6f:ef:4b:a0:
                    ed:e1:86:ad:80:e7:f1:43:dd:02:68:21:1e:96:58:
                    c6:ff:8e:a7:97:6b:8a:a5:79:5a:8e:b4:40:34:36:
                    d6:06:b4:5d:52:66:09:52:b9:9f:1e:51:65:43:0f:
                    95:78:14:15:46:3c:41:b2:f2:55:40:36:64:1e:08:
                    04:48:ea:29:a6:83:2f:03:7a:49:51:03:07:ac:d5:
                    89:49:4e:a3:de:49:3d:2e:56:90:d6:02:56:ba:0e:
                    07:2d:8d:4d:e5:ed:92:a4:42:7c:7c:c3:b2:0d:68:
                    0f:a4:cd:55:1c:14:c5:44:43:35:02:1b:01:bb:91:
                    11:98:0a:a9:e9:fa:80:10:4b:6b:bd:f0:f8:9a:d7:
                    53:02:98:56:60:af:a9:68:6f:4d:1c:8b:57:47:27:
                    4f:a2:44:16:1f:fa:fe:b7:46:e0:a2:27:c7:2b:85:
                    6f:ba:78:ab:81:34:5d:a6:32:0b:78:54:ff:ae:de:
                    61:f4:83:c5:71:36:7e:74:d1:2d:b2:c4:e0:36:3f:
                    35:a0:f7:a7:c7:c7:70:e5:bf:c4:94:55:98:63:e8:
                    59:95:5c:b5:98:aa:cf:60:3f:39:b1:f9:c1:96:94:
                    68:21:a9:53:0d:0c:37:93:a3:1b:56:e8:f7:df:30:
                    eb:f5:08:1c:d8:0c:09:ef:65:78:9e:eb:9c:5d:36:
                    51:b2:58:43:fa:30:0a:2c:f9:dc:82:bf:6e:ed:a3:
                    09:38:a7
                Exponent: 65537 (0x10001)
        X509v3 extensions:
            X509v3 Basic Constraints: critical
                CA:TRUE, pathlen:1
            X509v3 Issuer Alternative Name: 
                DNS:suscerte.gob.ve, othername:<unsupported>
            X509v3 Subject Key Identifier: 
                AA:94:98:5B:01:C8:17:18:50:28:B5:F6:E1:5F:FB:FC:89:5E:69:AE
            X509v3 Authority Key Identifier: 
                keyid:AD:BB:22:1D:C6:E0:D2:01:A8:FD:76:50:52:93:ED:98:C1:4D:AE:D3
                DirName:/CN=Autoridad de Certificacion Raiz del Estado Venezolano/C=VE/L=Caracas/ST=Distrito Capital/O=Sistema Nacional de Certificacion Electronica/OU=Superintendencia de Servicios de Certificacion Electronica/emailAddress=acraiz@suscerte.gob.ve
                serial:0A

            X509v3 Key Usage: critical
                Certificate Sign, CRL Sign
            X509v3 Subject Alternative Name: 
                DNS:150.187.108.110, othername:<unsupported>, othername:<unsupported>
            X509v3 CRL Distribution Points: 
                URI:http://www.suscerte.gob.ve/lcr/CERTIFICADO-RAIZ-SHA384CRLDER.crl
                URI:ldap://acraiz.suscerte.gob.ve

            Authority Information Access: 
                OCSP - URI:http://ocsp.acraiz.suscerte.gob.ve

            X509v3 Certificate Policies: 
                Policy: 2.16.862.3.1.2
                  CPS: http://www.suscerte.gob.ve/dpc

    Signature Algorithm: sha256WithRSAEncryption
        21:9d:21:db:63:15:bd:d1:0e:58:6f:3d:e1:12:3a:f8:63:dc:
        96:7f:9f:96:b1:4f:2d:82:9b:02:1c:fe:8b:e4:d9:60:3c:2b:
        e8:98:40:02:90:cb:50:d1:47:f4:50:46:1b:e0:46:1e:9d:87:
        5f:94:89:32:69:ae:e0:9f:fc:0e:60:dd:eb:63:0e:67:ab:ff:
        b8:e4:68:60:9a:4c:14:cf:d3:32:74:6b:52:f2:9e:1d:0f:71:
        a3:2c:30:1d:6e:6b:5d:d4:77:26:f0:2e:2f:72:db:1c:7c:1e:
        d3:47:28:9e:33:7a:b3:f6:99:4a:c4:b4:c0:b9:02:b3:c1:2b:
        33:e9:d5:1f:38:55:85:3b:2e:08:c2:f8:d4:bb:61:24:40:27:
        31:44:f5:b3:af:af:cb:47:48:0e:41:50:15:c3:d6:09:c4:2c:
        cb:46:40:36:78:1c:5b:6b:dc:6e:b8:2b:30:49:53:94:88:3f:
        b2:09:ae:58:87:50:2b:c9:5b:28:4b:c1:92:b8:51:b8:9f:b3:
        3a:20:a0:67:b7:e2:69:d4:60:d2:53:6c:3b:c8:19:b5:61:7b:
        69:8e:af:06:1e:23:b2:45:9a:97:b4:b4:6a:ee:d8:c5:e8:5a:
        13:ec:3b:99:0e:40:a8:33:fb:94:db:60:61:77:d5:ab:52:c6:
        e4:75:d9:f2:52:91:47:31:27:c6:13:cc:66:7c:db:e2:65:53:
        c3:16:a2:b0:dd:ee:26:db:1c:c1:92:ff:88:2b:5e:51:43:0d:
        a8:f8:7f:9a:38:41:c4:85:14:5d:1f:b5:12:7d:7a:8f:04:5d:
        cc:89:50:62:d2:ce:79:c1:c1:be:f7:43:4e:16:05:7c:e0:f3:
        78:28:f5:83:b9:df:90:e9:1d:35:af:bf:89:63:b0:e9:59:50:
        e9:13:2c:0a:63:61:97:93:cb:cd:4f:b6:fc:46:46:26:27:a4:
        6e:30:2a:fa:9a:9b:c0:f9:ea:dc:85:a1:e3:36:2b:54:70:99:
        be:44:97:99:6c:3e:c2:14:bd:2b:d9:7a:88:16:8c:a4:a4:d0:
        91:20:32:91:c0:43:3a:b8:f1:13:3e:cf:48:56:d7:e9:50:04:
        26:73:eb:95:b4:e8:28:18:50:be:e0:3c:9a:54:e1:22:18:8c:
        c1:87:17:83:f8:ae:09:11:63:5f:81:3d:99:5a:9a:74:95:10:
        60:1a:9d:d7:38:2e:98:e0:4f:48:7b:14:05:48:ad:8b:76:25:
        ed:cd:3d:af:4e:71:c7:46:b8:d8:bb:7b:30:6e:df:9c:9f:b8:
        2c:18:90:df:ff:f0:a8:55:36:2d:a5:42:4d:4f:cd:e2:71:8c:
        cb:cd:fa:ac:e2:b6:ae:ce
        
```

