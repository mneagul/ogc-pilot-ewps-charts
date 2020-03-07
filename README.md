# Installing

helm install mariantest1 ogc-pilot-ewps \
 --set persistence.storageClass=nfs-provisioner \
 --set ingress.host=wps.marian.ogc-pilot-2020.sage.ieat.ro \
 --set image.repository=mneagul/ewps-pilot-ewps \
 --set image.tag=latest
