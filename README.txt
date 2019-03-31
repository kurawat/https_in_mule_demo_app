To avoid SSL hostname verification due to self-signed certificateion set below JVM parameter in mule application run configuration -

-Dcom.ning.http.client.AsyncHttpClientConfig.acceptAnyCertificate=true


More info -

https://support.mulesoft.com/s/article/No-name-matching-xxxx-found-java-security-cert-CertificateException


