FROM jodogne/orthanc:latest

WORKDIR /root/

RUN wget http://lsb.orthanc-server.com/plugin-dicom-web/mainline/libOrthancDicomWeb.so
RUN mv ./libOrthancDicomWeb.so /usr/local/share/orthanc/plugins/
