# Run gixy command line tool for static nginx analysis:
# https://github.com/yandex/gixy
#
# Usage:
# 	docker run --rm -it \
# 		-v /etc/nginx:/etc/nginx \
#		r.j3ss.co/gixy /etc/nginx/nginx.conf
#
FROM python:3.10.10-alpine

RUN pip install gixy

ENTRYPOINT ["gixy"]
