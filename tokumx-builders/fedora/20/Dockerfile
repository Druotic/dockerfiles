FROM fedora:20
RUN yum install -y patchutils gcc gcc-c++ glibc-devel rpmdevtools git cmake ccache zlib-devel libpcap-devel pcre-devel buildbot-slave valgrind-devel readline-devel boost-devel make
WORKDIR /data
CMD buildslave start && tail -f twistd.log
