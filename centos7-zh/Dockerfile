FROM centos:7

LABEL maintainer="Centos7 chinese base Maintainers; sanyZhang 5385139@qq.com"



RUN   yum -y update \
        && yum install -y kde-l10n-Chinese glibc-common \
        && cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
        && localedef -c -f UTF-8 -i zh_CN zh_CN.utf8

ENV LC_ALL zh_CN.UTF-8