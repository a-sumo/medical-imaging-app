docker run -p 8042:8042 \
  -e ORTHANC__DICOM_WEB__ENABLE=true \
  -e ORTHANC__DICOM_WEB__ROOT="/dicom-web/" \
  -e ORTHANC__NAME="OrthancWithDICOMWeb" \
  -e VERBOSE_ENABLED=true \
  jodogne/orthanc-plugins